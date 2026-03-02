This file has the purpose to explain every metric I compared while profilling my CUDA aplications.


## Memory workload
- Memory Bandwidth: Thoretical maximum data transfer rate between the GPUand its memory. Fixed by the hardware.
`Memory Bandwidth(GB/s)= (Memory Bus Width × Memory Clock Speed × 2) / 8`
- Memory Throughtput: Refers  to the actual data transfer rate achived during real-world operations. This can be optimed. 
- L1/TEX Hit Rate: hit rate in the L1 cache.
- L2 Hit Rate: hit rate in the L2 cache.