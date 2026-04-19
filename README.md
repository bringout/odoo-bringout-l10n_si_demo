# bringout_l10n_si_demo — Slovenia Demo Localization

Minimal Slovenia (SI) localization **for demo / test-bed use only**.
NOT a production localization — it ships ~12 accounts and the four dominant
DDV tax rates. Use real `l10n_si` for actual Slovenian accounting.

## What's inside

* A minimal **chart of accounts template** (`bringout_l10n_si_demo.chart_template_si_demo`)
  with a dozen accounts covering bank/cash/receivables/payables/income/expense/
  tax payable/VAT-in/payroll payable.
* **DDV tax templates**:
  * `si_ddv_22` — 22% standard (sales + purchase)
  * `si_ddv_9_5` — 9.5% reduced
  * `si_ddv_5` — 5% super-reduced
  * `si_ddv_0_export` — 0% export

## Intended consumer

`odoo-bringout-multi_company_example_ba_hr_si_data` — the multi-company
test bed that loads this CoA onto `CompanySL-1`.

## License

AGPL-3
