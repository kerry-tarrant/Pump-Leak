## Sensitivity analysis on pump and cotransporter parameters of a pump leak model
Authors: Zahra Aminzare, Alan Kay, Kerry Tarrant

## References: 
  1. Dela, A., Shtylla, B., & Pillis, L.D. (2022). "Supplementary Information Multi-method Global Sensitivity Analysis in Mathematical Models."
  2. https://github.com/an-do/MeFAST
  3. Dela, A., Shtylla, B., & Pillis, L.D. (2022). "Multi-method global sensitivity analysis of mathematical models"
  4. Aggarwal, M. (2019). Mathematical Modeling and Sensitivity Analysis for Biological Systems.
  5. Jansen, J.W. (1999). "Analysis of variance designs for model output."

## Information on notebooks:

### Runtimes:

  - 1967005/(206+(58.2/60)) = 9502.43961353 pump leak model runs per minute
    - Anaconda 2022.05
    - Windows 11
    - Ram: 16.0 GB (15.8 GB usable)
    - Processor: Intel(R) Core(TM) i7-8550U CPU @ 1.80GHz   1.99 GHz

  - (20**4)/(1717.98/60) = 5587.95795062 pump leak model runs per minute
    - Python 3.7.13
    - Ubuntu 18.04
    - Ram: 13.662199808 GB (13.00740096 usable)
    - Processor: Intel(R) Xeon(R) CPU @ 2.20GHz

### Requirements:

  - Statistical tools, such as scipy.stats.tukey_hsd used in MeFAST-pump_model.ipynb, require **Scipy 1.8.0 or greater** which in turn requires **Python 3.8 or greater**.