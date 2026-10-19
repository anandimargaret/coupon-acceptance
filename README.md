# Will the Customer Accept the Coupon?

This project explores survey data from 12,684 driving scenarios to understand which drivers accept coupons for nearby businesses (bars, coffee houses, restaurants, and carry-out) and which drivers ignore them.

**Full analysis:** [coupon_analysis.ipynb](coupon_analysis.ipynb)

## Key Findings

**Overall, 57% of coupons were accepted**, but this varied a lot by type. Coupons for carry-out food and inexpensive restaurants were accepted more than 70% of the time, while bar and expensive restaurant coupons were accepted less than half the time.

**People accept coupons for places they already go.** This was the clearest pattern in the data:
- Regular bar-goers accepted 77% of bar coupons. People who never go to bars accepted only 19%.
- Regular coffee drinkers accepted 66% of coffee house coupons. People who never go accepted only 19%.

**Timing and convenience matter.** Coffee house coupons were most likely to be accepted:
- in the mid-morning (10AM) or early afternoon
- when the driver had no urgent destination
- when friends were in the car
- when the coupon lasted a full day instead of 2 hours
- when the coffee house was less than 15 minutes away

The best coffee house audience, regular coffee drinkers with no urgent destination in the morning or early afternoon, accepted 77% of coupons.

**Some things made no difference.** A driver's gender and whether they have children did not affect coffee house coupon acceptance.

## Recommendations

1. Target coupons at people who already visit that type of business.
2. Send coffee house coupons mid-morning or early afternoon, when drivers aren't rushing home or to work.
3. Give coupons a 1-day expiration rather than 2 hours.
4. Only offer businesses that are a short drive away.

## Next Steps

- Build a model to predict whether a specific driver will accept a coupon.
- Test these recommendations with real customers, since this data comes from a survey about imagined situations.
- Explore the remaining coupon types in more depth.

## Data

Data comes from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation) and was collected through a survey on Amazon Mechanical Turk.
