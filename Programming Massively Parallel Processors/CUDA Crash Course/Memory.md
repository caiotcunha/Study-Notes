# Unified Memory
``` CUDA
cudaMallocManaged(&pointer,size)
```
CUDA takes care of the memory inside and outside of GPU. Transference occurs automatically.

# Prefetch

``` CUDA
cudaMemPrefetchAsync(a,bytes,gpuID);
```
CUDA starts to transfer data async to the GPU while the code runs.
``` CUDA
cudaMemPrefetchAsync(a,bytes,cpuID);
```
The same can occur to the cpu.