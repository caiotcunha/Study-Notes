Multicore CPU is optimized for sequenctial code performance. The amount of speedup you can achive depends on the portion of the code that can be parallized.

Message Passing Interface (MPI): Generally used for scalable cluster computing. MPI is a model where computing nodes in a cluster do not share memory; all data sharing and interaction must be done through explicit message passing.

CUDA: Use shared memory. Shared memory between CPU and GPU is still a little tricky. 

