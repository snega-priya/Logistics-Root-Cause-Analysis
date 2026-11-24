
# Logistics Root-Cause Analysis
## Management Report

### 1. Executive Summary

This project investigates a decline in on-time delivery (OTD)
for a simulated Kolkata freight logistics company.

OTD declined from 55.33% to 41.36%,
a decrease of 13.96 percentage points.

Warehouse processing time increased by 1.00 hours.

### 2. Root-Cause Findings

The warehouse counterfactual estimates that maintaining the
earlier warehouse processing time would increase post-period
OTD to 54.87%.

The estimated contribution is 96.71%
of the simulated OTD decline.

This is a designed simulation result and not independent
evidence of real-world causality.

### 3. Supporting Evidence

- Hub delay rates differ significantly (chi-square test).
- Route delay rates differ significantly (chi-square test).
- Service-type delay rates differ significantly (chi-square test).
- Vehicle age has a weak positive correlation with delivery time.
- Weekly shipment volume has no significant correlation with OTD.
- Regression R-squared: 0.749.

### 4. Recommendations

| Owner | Recommended action | Proposed target |
|---|---|---|
| Warehouse Manager | Monitor arrival-to-dispatch time | Reduce average processing time by 20% |
| Fleet Manager | Introduce preventive maintenance | Reduce vehicle-related delays |
| Route Manager | Review lowest-performing routes | Improve OTD on five weakest routes |
| Hub Managers | Investigate hub bottlenecks | Improve OTD at three weakest hubs |

Targets are proposed management targets, not measured outcomes.

### 5. Early Warning System

A rolling four-week OTD monitor was developed.
Its alert threshold compares rolling OTD with the initial
eight-week baseline.

The system is a prototype and has not been validated
to provide four weeks of advance warning.

### 6. Limitations

- Data is simulated, not actual company data.
- Statistical association does not prove causation.
- Festive effects were not independently modelled.
- Early-warning lead time has not been validated.
- Route and service differences require further investigation.

### 7. Conclusion

The simulated analysis identifies warehouse processing
as the dominant designed driver of the OTD decline.
Other operational differences provide additional areas
for investigation. Real operational records are required
to validate these findings.
