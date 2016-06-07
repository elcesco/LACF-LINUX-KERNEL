# LACF-LINUX-KERNEL

Bloom filter is used for set membership test. Later it is modified slightly as Length aware Bloom Filter to improve the efficiency of IP lookup. But one of the disadvantages of bloom filter is that deletion is not possible.

Cuckoo filter is later introduced with capability of deletion. As a variation of cuckoo filter, Length Aware Cuckoo Filter is used to improve the efficiency of IP lookup. It has advantage that data can be deleted from the filter.

Length Aware Cuckoo filter is implemented in LINUX KERNEL to prove that its performance is better than cuckoo filter.
