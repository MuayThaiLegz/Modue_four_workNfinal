# Module 4 Project Folder

**This contains all the work I have done on this Module 4 final

---

## Technologies 
`print("We're heading to Jupyter!")`
---
*Built using Python 3.7.9 64-bi(On Jupyter Lab)


---

I Have been tasked with evaluating four new investment options for inclusion in the client portfolios. Legendary fund and hedge-fund managers run all four selections. To determine the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.


## Installation Guide and Examples

```
import pandas as pd
from pathlib import Path
import numpy as np
%matplotlib inline


nav_data_df = pd.read_csv(
    Path("./Resources/whale_navs.csv"), 
    index_col="date", 
    parse_dates=True, 
    infer_datetime_format=True
)
```
*Single line DataFrame and Path 


## Contributors

** This Loan Qualifier app was cntributed to by the entire UC Berkeley FinTech BootCamp 
[UC Berkeley Extension](https://bootcamp.berkeley.edu/fintech/)

