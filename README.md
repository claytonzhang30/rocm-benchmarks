# ROCm Benchmarks

Benchmark suite for AMD GPU workloads.

## Benchmarks
- Matrix multiplication (GEMM)
- Flash attention kernels
- Memory bandwidth (HBM2e)
- FP16 vs BF16 throughput

## Run
```bash
python bench_gemm.py --sizes 1024,2048,4096
python bench_attention.py --seq-len 4096 --heads 32
```

## Results
Tested on MI300X — see `results/` for detailed comparisons.
