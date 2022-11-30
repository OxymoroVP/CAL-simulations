# LAB_02 REPORT - Design Space Exploration με τον gem5 

//todo: update lab2report.md <br>
//shortly: benchmarking and  <br>
<br>

<h3> SPEC CPU2006 Benchmarks στον gem5 </h3>

[system.cpu.dcache] L1 Data cache (size 64KB 2-way-associative): 

    size=65536
    assoc=2
    
[system.cpu.icache] L1 Instruction cache (size 32KB 2-way-associative):

    size=32768
    assoc=2


[system.l2] L2 cache (size 2MB 8-way-associative):

    size=2097152
    assoc=8    

[system] cache line size : 64B

    cache_line_size=64




| <b> command |  bzip      | mcf | hmmer | sjeng | libm |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| sim.seconds      | 1231       | 1231 | 1231 | 
| system.cpu.cpi   | 1231        | | |
| cpu.icache.overall_miss rate      | 1231       | | |
| cpu.dcache.overall_miss rate      | 1231       | | |
| cpu.l2cache.overall_miss rate      | 1231       | | |

