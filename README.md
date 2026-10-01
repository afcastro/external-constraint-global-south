# External Constraint and Growth in the Global South

**Status:** planned

## Question
Is long-run growth in peripheral economies consistent with Thirlwall's balance-of-payments-constrained growth rate (g = x / π)?

## Premises
- Growth is bounded by the rate at which external accounts can finance imports.
- Income elasticity of imports differs systematically between core and periphery.

## Method
1. Data: World Bank WDI (GDP, exports, imports), UN Comtrade for composition.
2. Estimate income elasticity of imports by country (ARDL/cointegration for long series).
3. Compare actual growth with Thirlwall rate; panel specification across country groups.
4. Robustness: commodity-cycle windows, Thirlwall with capital flows.

## Deliverables
Actual vs. constrained growth scatter, elasticity table by country group.

## Stack
Python (pandas, statsmodels, linearmodels); WDI API.
