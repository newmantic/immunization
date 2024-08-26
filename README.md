# immunization

Immunization is a strategy used in fixed income portfolio management to protect the portfolio from interest rate risk. The primary goal of immunization is to ensure that the value of assets is sufficient to meet liabilities, regardless of changes in interest rates. This is typically achieved by matching the duration of assets with the duration of liabilities.

Duration:
Duration measures the sensitivity of a bond's price to changes in interest rates. It represents the weighted average time until the bond's cash flows are received.

Present Value (PV):
The present value of future cash flows is the current value of those cash flows, discounted at the appropriate interest rate.

Immunization:
Immunization occurs when the duration of assets equals the duration of liabilities, and the present value of assets equals the present value of liabilities. This ensures that small changes in interest rates will not affect the ability of the portfolio to meet its liabilities.


1. Present Value (PV) of Cash Flows
The present value (PV) of a series of cash flows is given by:
PV = sum(CF_t / (1 + r)^t for t in 1 to T)
Where:
CF_t is the cash flow at time t.
r is the discount rate.
T is the total number of periods.

2. Macaulay Duration
The Macaulay duration (D) of a bond is given by:
D = sum(t * (CF_t / (1 + r)^t) for t in 1 to T) / PV
Where:
t is the time in years when each cash flow CF_t is received.
r is the yield to maturity (discount rate).
PV is the present value of the cash flows.

4. Immunization Condition
For a portfolio to be immunized, the following two conditions must be satisfied:
1) Present Value Match:
The present value of assets should equal the present value of liabilities:
PV_assets = PV_liabilities
2) Duration Match:
The duration of assets should equal the duration of liabilities:
D_assets = D_liabilities


Consider you have a portfolio with assets and liabilities that you want to immunize against interest rate changes:
Calculate the Present Value:
Compute the present value of the asset and liability cash flows using the present value equation.
Calculate the Duration:
Compute the duration of the asset and liability cash flows using the Macaulay duration equation.
Check Immunization:
Ensure that both the present value and duration of the assets match the present value and duration of the liabilities. If they do, the portfolio is immunized.
