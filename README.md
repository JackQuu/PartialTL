# PartialTL

**Partial Transfer Learning for Causal Estimation**

R package implementing partial transfer learning (PTL) for causal effect estimation using source and target data, with bootstrap-based source detection.

## Dependencies

- **Imports:** MASS, DoubleML, ncvreg  
- **Suggests:** mlr3, mlr3learners, glmnet (for demos and custom learners)

## Main functions

| Function | Description |
|----------|-------------|
| `fit_PTL` | PTL causal estimate (homogeneous source, cross-fit + outcome reconstruction) |
| `fit_HPTL` | Heterogeneous PTL with multiple sources and covariate modules |
| `boot_detection` | Bootstrap-based source detection |
| `run_bootstrap_E_hat` | Bootstrap for nuisance function estimation |
| `DGP` | Data generating process for simulations |
| `RMSE` | Root mean squared error for evaluation |
| `f_0`, `g_0`, `f_k`, `g_k` | Nuisance functions for target and source models |
