| Element | In this example |
|:---|:---|
| **1. Topic / Question** |Do EV have lower fuel costs in comparison to gas vehicles? |
| **2. Hypothesis** |EVs have significantly lower annual fuel costs than gas vehicles of the same class|
| **3. Outcome / Metric / Test Statistic** | Mean difference in annual fuel cost between RVs and gas vehicles   |
| **4. Units of Analysis** | one vehicle model year|
| **5. Data Source(s)** | https://fueleconomy.gov/feg/download.shtml#:~:text=(Documentation)-,Unzipped%20CSV%20File,-(Documentation)|
| **6. Why this data works** | Both EVS and gas cars are in the same file with pre calculated fuel cost column|
| **7. Uncertainty Metric** | Median annual fuel cost. CLT doesnt apply to medians, so we use bootstrapping|
| **8. Null Hypothesis** | There is no difference in annual fuel cost between EVs and gas vehicles|


# Project Title
CYOH - EV vs Gas Vehicles comparison
## 1. Research Question

What are you investigating, and why does it matter?
- I am investigating if electric vehicles have a lower annual fuel cost in comparison to gas vehicles. Fuel costs are the most financial arguments against EV. Gas prices fluctuates often, and electricity prices varies by region. This comparison will help consumers to make the decision.

## 2. Hypothesis

State your null and alternative hypotheses clearly and succinctly.

Null hypothesis: There is no difference in mean annual fuel cost between EV and Gas vehicles of the same vehicle class.
Alternative hypothesis: EV have a lower mean annual fuel cost than gas vehicles within the same vehicle class. 

## 3. Data Description

Describe your data source(s):

* Where it comes from (URL, API, dataset name) - https://fueleconomy.gov/feg/download.shtml#:~:text=(Documentation)-,Unzipped%20CSV%20File,-(Documentation)
* What each observation represents (unit of analysis) - 
* Number of observations and key variables
* Any filtering, cleaning, or transformation steps

## 4. Methods

Summarize how you analyzed the data:

* The test statistic for your permutation test
* How you simulated or resampled under the null hypothesis
* The metric(s) for which you created bootstrap confidence intervals
* Why the CLT does not apply to at least one metric

## 5. Results

Present your main findings:

* Key summary statistics and visualizations
* Observed test statistic and p-value (if applicable)
* Bootstrap confidence intervals for relevant metrics

## 6. Uncertainty Estimation

Discuss your resampling results:

* How many resamples you used
* What the bootstrap or randomization distributions looked like
* How you interpret the interval estimates

## 7. Limitations

Briefly note any limitations in data, assumptions, or methods, including sources of bias or missing data.

## 8. References

List all datasets, tools, libraries, or papers you cited.

---

**Reminder:** Your README should be clear enough that someone unfamiliar with your work could understand what you studied, how you analyzed it, and what you found.
