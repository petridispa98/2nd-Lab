# 2nd-Lab

Ο gem5 χρησιμοποιεί τα παρακάτω χαρακτηριστικά μνήμης επεξεργαστή: </br>
L1 instruction cache με size=32768B, assoc=2 και block_size=64B </br>
L1 data cache με size=65536B, assoc=2 και block_size=64B </br>
L2 cache με size=2097152B, assoc=8 και block_size=64B </br>

Στον φάκελος spec_results υπάρχουν τα output των gem5 simulations για κάθε benchmark. Μέσα στον κάθε φάκελο υπάρχει αρχείο info.txt που περιέχει τις πληροφορίες: sim_seconds, cache.overall_miss_rate::total για κάθε είδος cache.

Scaling 1GHz vs 2GHz: </br>
specbzip: 1.91 </br>
spechmmer: 1.995 </br>
speclibm: 1.501 </br>
specsjeng: 1.37 </br>
specmcf: 1.967 </br>
