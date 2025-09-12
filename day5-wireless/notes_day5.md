# Day 5 – Wireless & Security

## Concepts Learned
- Wi-Fi standards:
  - 802.11b → 11 Mbps, 2.4 GHz (obsolete)
  - 802.11g → 54 Mbps, 2.4 GHz
  - 802.11n → up to 600 Mbps, 2.4/5 GHz (MIMO)
  - 802.11ac → multi-Gbps, 5 GHz (MU-MIMO, wider channels)
  - 802.11ax (Wi-Fi 6) → up to 9.6 Gbps, efficiency improvements
- Bands:
  - 2.4 GHz = longer range, more interference, only 1/6/11 are non-overlapping
  - 5 GHz = shorter range, higher speeds, no overlap (just crowding)
- Wireless security:
  - WEP = weak (RC4, easily cracked)
  - WPA = TKIP (better than WEP, still weak)
  - WPA2 = AES/CCMP (current standard)
  - WPA3 = newest, strongest
- Authentication:
  - PSK = shared password
  - Enterprise = RADIUS server for per-user login

## Labs Completed
- Scanned nearby Wi-Fi networks with WiFi Analyzer
- Identified channels and overlapping SSIDs
- Confirmed best practice: use channels 1, 6, or 11 (2.4 GHz), auto is fine for 5 GHz
- Verified my router was using 20 MHz width on 2.4 GHz and channel 44 on 5 GHz
- Noted that 802.11b can be disabled without breaking modern devices

## Flashcards Added
- Which 2.4 GHz channels don’t overlap? → 1, 6, 11
- Max speed of 802.11b? → 11 Mbps
- Max speed of 802.11g? → 54 Mbps
- Which Wi-Fi standard introduced WPA3? → 802.11ax (Wi-Fi 6)
- WEP weakness? → RC4, easily cracked
- WPA2 uses what encryption? → AES (CCMP)
- WPA2-PSK vs WPA2-Enterprise? → PSK = shared password, Enterprise = RADIUS
- 2.4 GHz vs 5 GHz difference? → 2.4 = range/interference, 5 = speed/crowding
