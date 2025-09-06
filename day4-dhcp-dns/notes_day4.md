# Day 4 – DNS

## Concepts Learned
- DNS record types:
  - A = IPv4 address
  - AAAA = IPv6 address
  - CNAME = Alias → Canonical name
  - NS = Authoritative name servers
- CNAME is used for flexibility and load balancing (e.g., accounts.youtube.com → www3.l.google.com)
- Traceroute relies on DNS to resolve hostnames before mapping the path
- DNS uses both TCP and UDP on port 53:
  - UDP for most queries
  - TCP for zone transfers and large responses

## Labs Completed
- Resolved A & AAAA records for youtube.com
- Checked CNAME record for accounts.youtube.com
- Queried NS records for youtube.com
- Ran traceroute to youtube.com (validated DNS resolution + hop path)

## Flashcards Added
- DNS ports (53 TCP/UDP)
- A, AAAA, CNAME, NS record definitions
- When DNS uses TCP vs UDP
