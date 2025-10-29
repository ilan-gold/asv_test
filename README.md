To reproduce:

```
cd benchmark_suite
conda create -n asv_test python=3.12 asv py-rattler -c conda-forge
conda activate asv_test
asv run main^! --verbose
```
