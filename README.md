# 2nd-Lab

Ο gem5 χρησιμοποιεί τα παρακάτω χαρακτηριστικά μνήμης επεξεργαστή: </br>
L1 instruction cache με size=32768, assoc=2 και block_size=64 </br>
L1 data cache με size=65536, assoc=2 και block_size=64 </br>
L2 cache με size=2097152, assoc=8 και block_size=64 </br>

Scaling 1GHz vs 2GHz: </br>
specbzip: 1.91 </br>
spechmmer: 1.995 </br>
speclibm: 1.501 </br>
specmcf: 1.967 </br>
