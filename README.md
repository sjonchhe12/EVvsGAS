| Element | In this example |
|:---|:---|
| **1. Topic / Question** |Do EV have lower fuel costs in comparison to gas vehicles? |
| **2. Hypothesis** |EVs have significantly lower annual fuel costs than gas vehicles of the same class|
| **3. Outcome / Metric / Test Statistic** | Mean difference in annual fuel cost between EVs and gas vehicles   |
| **4. Units of Analysis** | one vehicle model year|
| **5. Data Source(s)** | https://fueleconomy.gov/feg/download.shtml#:~:text=(Documentation)-,Unzipped%20CSV%20File,-(Documentation)|
| **6. Why this data works** | Both EVS and gas cars are in the same file with pre calculated fuel cost column|
| **7. Uncertainty Metric** | Median annual fuel cost. CLT doesnt apply to medians, so we use bootstrapping|
| **8. Null Hypothesis** | There is no difference in annual fuel cost between EVs and gas vehicles|

