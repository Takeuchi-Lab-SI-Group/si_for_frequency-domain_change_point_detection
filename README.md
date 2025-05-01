# Change Point Detection in the Frequency Domain with Statistical Reliability

This is the official repository for the paper [Change Point Detection in the Frequency Domain with Statistical Reliability](https://openreview.net/forum?id=FNRdaHz3qN), which has been accepted in Transactions on Machine Learning Research (TMLR).

## Installation & Requirements

This package has the following dependencies:

- Python (version 3.11.10 or higher, we use 3.11.10)
   - sicore (version 2.4.5 or higher, we use 2.4.5)
   - numpy (version 1.26.4 or higher, we use 1.26.4)
   - scipy (version 1.14.1 or higher, we use 1.14.1)
   - numba (version 0.60.0 or higher, we use 0.60.0)
   - tqdm (version 4.67.0 or higher, we use 4.67.0)

Please install the following dependencies by pip.

```
pip install sicore # note that numpy is automatically installed by sicore
pip install scipy
pip install numba
pip install tqdm
```

## Reproducibility

To reproduce the results shown in the paper, please see the following instructions after the installation.

For reproducing Figure 5 (type I error rate).

```
sh experiment_fpr.sh
```

For reproducing Figure 6 (power).

```
sh experiment_tpr.sh
```
