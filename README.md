# Mortgage Affordability Calculator

> How much home your income supports, before a lender ever runs the numbers.

**Live demo:** https://0xelitesystem.github.io/mortgage-affordability-calculator/

Not financial advice. This is an estimate from the numbers you enter, for learning and planning only.

Single HTML file. Runs in the browser with no build step, no server, no tracking, and no data leaving the page.

## What it does

- Solves the maximum home price from income, monthly debts, rate, term, and down payment
- Applies a front-end housing ratio and a back-end total-debt ratio, and takes the lower
- Breaks the monthly payment into principal and interest, property tax, insurance, and HOA
- Iterates because property tax scales with price, so the answer settles instead of guessing
- Shows the resulting front-end and back-end DTI with a pass or over marker

## What it is not

- Not a pre-approval or a quote. A lender uses your full credit profile and exact figures
- Not a guarantee of what you should borrow. The maximum is a ceiling, not a target

## Use it

Open the hosted page: https://0xelitesystem.github.io/mortgage-affordability-calculator/

Or download `index.html` and open it in any browser. It works offline.

## Privacy

Everything runs client-side. No analytics, no cookies, no network calls, no local storage.

## Related

- [loan-amortization-visualizer](https://github.com/0xelitesystem/loan-amortization-visualizer)
- [debt-payoff-planner](https://github.com/0xelitesystem/debt-payoff-planner)
- [net-worth-snapshot](https://github.com/0xelitesystem/net-worth-snapshot)

## License

MIT, copyright 0xelitesystem 2026.
