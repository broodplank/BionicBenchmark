BionicBenchmark
===============

Shell script for developers to review their libc performance (string tests)

I created this extremely simple benchmark that's quick and realibly reads your string manipulation performance. 
It stores the score with your build id

A sample output of the script would be:

broodplank@Bulldozer ~/Desktop $ ./bench

>>>>>> Bionic Benchmark v1.0 <<<<<<
--------- by broodplank -----------

Waiting for device...
Device found

Preparing benchmark...

0 KB/s (68 bytes in 0.077s)
0 KB/s (30 bytes in 0.079s)

Finished preparation!


Starting benchmark...

Running Benchmark 1 of 5
>> MEMCMP....
>> MEMCMP....Done!

Running Benchmark 2 of 5
>> MEMCPY...
>> MEMCPY....Done!

Running Benchmark 3 of 5
>> MEMMOVE...
>> MEMMOVE...Done!

Running Benchmark 4 of 5
>> MEMSET....
>> MEMSET....Done!

Running Benchmark 5 of 5
>> STRLEN....
>> STRLEN....Done!


Benchmarks completed, pulling data to pc...

0 KB/s (72 bytes in 0.076s)
0 KB/s (72 bytes in 0.077s)
1 KB/s (72 bytes in 0.040s)
0 KB/s (72 bytes in 0.077s)
0 KB/s (72 bytes in 0.077s)

Processing data...

>>>>>>>>> Score <<<<<<<<<<<

- MEMCMP Score  : 7191
- MEMCPU Score  : 73483
- MEMMOVE Score : 71391
- MEMSET Score  : 85188
- STRLEN Score  : 16160

- Total Score   : 253413

>>>>>>>>>>>><<<<<<<<<<<<<<<

Saving to log
Done!

