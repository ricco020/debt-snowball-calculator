# Debt snowball vs avalanche calculator

Free, single-file calculator: enter your debts (balance, APR, minimum payment) and the extra you can pay each month. It shows, for the snowball (smallest balance first) and the avalanche (highest APR first):

- the month you are debt-free and the number of months,
- the total interest paid,
- the month each debt is cleared,
- the full month-by-month plan, downloadable as CSV for Excel or Google Sheets.

Use it online: https://ricco020.github.io/debt-snowball-calculator/

Model: interest added monthly at APR / 12, minimums paid on every debt, extra plus freed minimums rolled to the target debt, constant total monthly outlay. Fixed APR, no fees, no new charges. Results checked against an independent Python implementation.

Runs fully in the browser, no tracking, no network calls. MIT licence.
