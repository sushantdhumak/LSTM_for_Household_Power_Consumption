---
### **Forecasting Household Electric Power Consumption using LSTM**
---

This dataset contains 2,075,259 one-minute measurements of electric power consumption in a single household over almost four years (December 2006 to November 2010). The data includes various electrical quantities and sub-metering values.

**Dataset Characteristics**

* Multivariate
* Time-Series

**Dataset Information**

The archive was gathered from a house in Sceaux, France, with some missing values present. Additional notes:

1. The active energy consumed every minute is represented by `(global_active_power * 1000 / 60 - sub_metering_1 - sub_metering_2 - sub_metering_3)`.
2. Missing values occur about 1.25% of the time, marked with a missing value between consecutive semi-colon attribute separators.

**Variables Table**

| Variable Name | Role | Type |
| --- | --- | --- |
| Date | Feature | Date |
| Time | Feature | Categorical |
| Global_active_power | Feature | Continuous |
| Global_reactive_power | Feature | Continuous |
| Voltage | Feature | Continuous |
| Global_intensity (Current) | Feature | Continuous |
| Sub_metering_1  *Sub-metering No. 1*   (kW-h) Energy sub-metering for kitchen | Feature | Continuous |
| Sub_metering_2  *Sub-metering No. 2*   (kW-h) Energy sub-metering for laundry room | Feature | Continuous |
| Sub_metering_3  *Sub-metering No. 3*   (kW-h) Energy sub-metering for electric water-heater and air-conditioner | Feature | Continuous |

**Dataset Link:**

https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption

---
