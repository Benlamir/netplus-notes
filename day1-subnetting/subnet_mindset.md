# Subnetting Mindset
subnetting mindset - day1:

1. find te host bits = 32 - prefix (1s)
2. total adresses = 2^(host bits)
3. usable hosts = total adresses - 2
4. block size = 256 - mask-octet (first octet that isn’t 255 and isn’t 0 at the end.)
5. next subnet = network + block size
6. broadcast = next subnet - 1
7. first usable = network + 1
8. last usable = broadcast - 1
9. always check with ipcalc to confirm
10. think in powers of 2
