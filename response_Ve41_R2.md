Bias, Variance, and MSE of different methods when reward distribution is heavy-tailed. We set the reward distribution as each of the four families: Lomax, Generalized Extreme Value, Frechet, and T-Student. We select the parameter of each familiy such that they have finite mean and infinite variance.
| Distribution | Metric   | LSE        | LS     | IX     | ES     | PM     | OS     | SNIPS  | IPS-TR  |
|--------------|----------|------------|--------|--------|--------|--------|--------|--------|---------|
| Lomax        | Bias     | 1.511      | 1.617  | 4.671  | 2.584  | 0.5677 | 4.778  | 0.1058 | 0.9616  |
| Lomax        | Variance | 0.4641     | 0.5156 | 0.6819 | 84.07  | 187.6  | 0.3136 | 190.4  | 171.5   |
| Lomax        | MSE      | **2.746**  | 3.132  | 22.50  | 90.75  | 187.9  | 23.15  | 190.4  | 172.4   |
| GEV          | Bias     | 0.1204     | 0.2105 | 0.7073 | -2.861 | 0.2103 | 0.7220 | -6.751 | -5.4139 |
| GEV          | Variance | 0.0004     | 0.0004 | 0.0657 | 722.1  | 43.68  | 0.0054 | 2209   | 1604    |
| GEV          | MSE      | **0.0149** | 0.0447 | 0.5660 | 730.2  | 43.72  | 0.5268 | 2255   | 1633    |
| Frechet      | Bias     | 1.474      | 1.598  | 3.965  | 2.993  | 1.1863 | 5.309  | 0.2678 | 1.235   |
| Frechet      | Variance | 0.4842     | 0.5161 | 10.31  | 29.80  | 92.08  | 0.1344 | 132.8  | 80.58   |
| Frechet      | MSE      | **2.656**  | 3.068  | 26.03  | 38.75  | 93.49  |  28.31 | 132.9  | 82.10   |
| T-Student    | Bias     | 0.9914     | 1.072  | 3.688  | 2.086  | 0.7545 | 3.766  | 0.0029 | 0.7982  |
| T-Student    | Variance | 0.3270     | 0.3647 | 0.1986 | 24.69  | 79.09  | 0.2374 | 205.6  | 61.42   |
| T-Student    | MSE      | **1.310**  | 1.513  | 13.80  | 29.04  | 79.66  | 14.42  | 205.6  | 62.06   |


MSE of LSE for different values of $\lambda$ when reward has different heavy-tailed distributions.
![effect](https://github.com/user-attachments/assets/5cb1416d-4c27-4dc6-ad98-73277c43c16a)
