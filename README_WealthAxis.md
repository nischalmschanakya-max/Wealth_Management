# WealthAxis

### Interactive Personal Wealth-Planning & Investment Education Platform

**WealthAxis** is an academic/portfolio project that evolved into an interactive wealth-planning application for Indian investors.

It combines risk profiling, asset allocation, mutual-fund research, portfolio projections, goal planning, retirement modelling, tax illustrations, Monte Carlo simulation, ETF analysis and a conversational financial-education layer into a single browser-based experience.

> **Important:** WealthAxis is an educational decision-support project, not SEBI-registered investment advice. It does not execute trades or transactions, and projections are illustrative rather than guaranteed.

## Live Demo

**(https://nischalmschanakya-max.github.io/Wealth_Management/)**

Replace the link above with the final GitHub Pages URL.

## What WealthAxis Does

### 1. Risk Profiling
WealthAxis evaluates investor behaviour and financial capacity using a structured questionnaire inspired by NISM-style risk-profiling concepts.

The model separates:

- **Willingness to take risk** — reaction to market declines, investing experience, goals and drawdown tolerance.
- **Ability to take risk** — income stability, dependents and financial resilience.

The two dimensions are combined before the final investor tier is selected.

### 2. Asset Allocation
The resulting investor tier maps to a strategic allocation across:

- Equity
- Debt
- Hybrid
- Gold / Commodity

The allocation is designed around the investor's risk profile and investment horizon.

### 3. Mutual-Fund Research
The current public build contains:

- **121 research-scored funds**
- **223 additional discovery funds**
- **344 funds in the combined universe**

The research-scored layer contains the deeper metrics used by the recommendation engine, while the broader discovery catalogue expands the searchable universe without inventing missing performance statistics.

### 4. Fund Selection Engine
Research-scored funds are evaluated using factors including:

- Risk-tier suitability
- Category fit
- Return history
- Volatility
- Sharpe ratio
- Expense ratio
- Fund rating
- Equity style
- Debt-duration suitability
- Portfolio allocation needs

This is intended to demonstrate a transparent rule-based selection process rather than a black-box recommendation.

### 5. Portfolio Projection
WealthAxis estimates future corpus using:

- Initial investment
- Monthly SIP
- Expected portfolio return
- Investment horizon

It also compares portfolio growth with simpler reference assumptions.

### 6. Monte Carlo Simulation
The application runs portfolio simulations to illustrate a range of possible outcomes instead of presenting a single number as certain.

Outputs include:

- Bull scenario
- Base / median scenario
- Bear scenario
- Portfolio health indicators

### 7. Goal Planning
Users can model financial goals such as:

- Retirement
- Education
- Home purchase
- Marriage
- Travel
- Custom financial goals

The tool adjusts future goal costs for inflation and compares them against projected portfolio growth.

### 8. SIP Step-Up
The Step-Up calculator demonstrates how increasing a monthly SIP annually can materially affect long-term wealth creation.

Users can vary:

- Starting SIP
- Annual step-up
- Investment duration
- Expected return
- Optional lump-sum investment

### 9. Retirement Planning
The retirement module estimates:

- Retirement corpus requirements
- Inflation-adjusted expenses
- Withdrawal needs
- Longevity assumptions
- Corpus sustainability illustrations

### 10. Tax Planning
WealthAxis includes educational calculators and explanations for common Indian investment-tax concepts, including:

- Equity STCG
- Equity LTCG
- LTCG exemption
- Gold / commodity taxation
- Slab-based illustrations
- Post-tax projections

Tax calculations are simplified educational illustrations and should be verified against current tax rules before making financial decisions.

### 11. Portfolio Stress Testing
The Pro layer allows users to test a generated portfolio against illustrative shocks such as:

- 2008-style equity drawdown
- COVID-style equity drawdown
- High-inflation scenario
- Interest-rate shock

These scenarios are demonstrations, not forecasts.

### 12. Fund Comparison
Users can compare research-scored funds across:

- Category
- Risk
- Return
- Volatility
- Sharpe
- Expense
- Rating
- Portfolio fit

### 13. Explainable Recommendations
The **Explain My Strategy** layer shows why a portfolio was selected instead of simply displaying the final allocation.

The explanation connects:

**Risk score → investor tier → allocation → fund selection → projected outcome → key risks**

### 14. Multilingual Interface
The interface is designed to support multiple languages, with English, Hindi and Kannada UI coverage.

### 15. Responsive Design
The application is designed to work across:

- Desktop
- Laptop
- Tablet
- Mobile

The navigation switches into a compact menu before the top bar can overlap.

## Technology

WealthAxis is currently implemented as a self-contained web application using:

- HTML5
- CSS3
- Vanilla JavaScript
- Chart.js
- Browser-based calculations
- GitHub Pages for deployment

The project deliberately avoids a backend in the current academic/public build.

## Design Principles

### Transparency
Important calculations are intended to be explainable.

### No fabricated data
Where a fund does not have the research statistics required by the recommendation engine, WealthAxis does not invent them simply to increase catalogue size.

### Data consistency
Current macro/tax assumptions are maintained through shared data values so that the same figure can be reused across cards, calculations and explanations.

### Education first
The application focuses on helping users understand financial decisions rather than presenting itself as an execution or guaranteed-return platform.

## Data & Assumptions

The project uses a dated snapshot for macro and tax assumptions in the public build.

Examples include:

- RBI policy rate
- CPI inflation
- GDP reference
- PPF rate
- Equity capital-gains assumptions

Because financial rules and market conditions change, the values should be updated and re-validated before future releases.

## Project Status

WealthAxis began as an **academic project** and evolved through iterative AI-assisted development, testing and refinement.

The current release focuses on:

- Explainable wealth planning
- Indian mutual-fund research
- Risk-aware portfolio construction
- Financial education
- Responsive product design

Future iterations may add:

- A proper backend
- Versioned market-data pipelines
- Larger research datasets
- More advanced scenario analysis
- User accounts / saved plans
- Additional data-provider integrations

## Disclaimer

WealthAxis is an **independent educational project**.

It is:

- Not SEBI-registered investment advice
- Not a broker
- Not an execution platform
- Not a guarantee of investment returns

Past performance does not guarantee future results. Market values, tax rules, fund characteristics and other financial inputs can change.

Users should independently verify important information and consult a qualified professional where appropriate.

## Author

**Nischal M S**

MBA Student  
Interested in Wealth Management, Investment Analysis and Financial Planning
