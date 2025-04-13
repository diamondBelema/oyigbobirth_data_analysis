# Report on Oyigbo Hospital

## Overview

This report presents an analysis of deliveries, antenatal patients, and birth outcomes at Oyigbo Hospital between January 2, 2024, and January 8, 2025. The key aspects covered include delivery statistics, antenatal patient data, birth weight analysis, and delivery outcome analysis.

---

## Total Number of Deliveries

According to the data:

- **Total Deliveries**: 161 deliveries.
- **Antenatal Patients Deliveries**: 123 deliveries from hospital antenatal patients.
- **Non-Antenatal Patients Deliveries**: 38 patients who did not register for antenatal but delivered at the hospital.

The time frame for this data is from **January 2, 2024** to **January 8, 2025**.

---

## Total Number of Antenatal Patients

According to the data:

- **Total Antenatal Patients**: 498 patients.
- **Deliveries at the Facility**: 123 patients delivered at the hospital.
- **Deliveries Elsewhere**: 375 patients went to other facilities for delivery.

---

## Proportion of Women Registered for Antenatal and Delivered at the Facility

Out of the 498 women who registered for antenatal care:

- **Deliveries at the Facility**: 123 women delivered at Oyigbo Hospital.

This gives a proportion of **24.7%** of antenatal patients delivering at the facility.

---

## Birth Weight Comparison: Booked vs Unbooked Patients

To determine if there is any difference in birth weight between booked (those who registered for antenatal care) and unbooked (those who did not), a **t-test** was performed.

### T-Test Results:
- **T-statistic**: -3.53
- **P-value**: 0.00054

Since the p-value (0.00054) is much smaller than the commonly used significance level of 0.05, we reject the null hypothesis. This means there is a statistically significant difference in the birth weight between booked and unbooked patient deliveries.

### Conclusion:
The data suggests that booking status impacts birth weight, with booked patients likely having different birth weights compared to unbooked patients.

---

## Delivery Outcome Analysis

A **Chi-square test of independence** was conducted to assess if there is a relationship between the timing of booking (1st, 2nd, or 3rd trimester), maternal weight at booking (normal or overweight), and the delivery outcome (live birth or stillbirth).

### Data: Trimester & Weight Category vs Delivery Outcome

| Trimester & Weight Category     | Live Birth | Still Birth |
|---------------------------------|------------|-------------|
| First Trimester - Normal Weight | 18         | 0           |
| First Trimester - Over Weight   | 3          | 0           |
| Second Trimester - Normal Weight| 67         | 6           |
| Second Trimester - Over Weight  | 7          | 1           |
| Third Trimester - Normal Weight | 15         | 3           |
| Third Trimester - Over Weight   | 3          | 0           |

### Chi-Square Test Results:
- **Chi-square Statistic (X²)**: 4.09
- **Degrees of Freedom (df)**: 5
- **P-value**: 0.537

### How to Interpret the Results:
- The **Chi-square statistic** measures how much the observed data differs from expected values.
- The **degrees of freedom** depend on the number of categories in the table.
- The **p-value** indicates whether the differences in the table are statistically significant.

Since the **p-value (0.537)** is greater than the significance level of 0.05, we conclude that the differences in the table are likely due to chance.

### Conclusion:
There is no statistically significant relationship between the timing of booking, maternal weight, and the delivery outcome (live birth or stillbirth). These factors do not appear to significantly affect delivery outcomes in this dataset.

---

## Conclusion

In summary, the analysis of Oyigbo Hospital's data suggests:
1. A total of 161 deliveries, with 123 from antenatal patients.
2. Approximately **24.7%** of women who registered for antenatal care delivered at the hospital.
3. A **statistically significant difference** in birth weight between booked and unbooked patients.
4. **No significant relationship** between the timing of booking, maternal weight, and delivery outcomes.

This data provides valuable insights into the hospital's delivery patterns and patient care.

---
