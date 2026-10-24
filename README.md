# Obligare US rules pack

Every federal and state filing obligation for US companies and nonprofits, as data: the schedule, the agency, the form, the fee, the penalty, the source page it was read from, and a plain English explanation. It is the pack that computes every calendar on [obligare.com](https://obligare.com).

- **File:** [`rules/us.json`](rules/us.json), 658 rules, version 2026.10.3, published October 22, 2026.
- **Live copy:** [obligare.com/rules/us.json](https://obligare.com/rules/us.json). This repository syncs from it every day, so each rule change shows here as a commit.
- **How the dates are computed and what is approximate:** [obligare.com/method](https://obligare.com/method).
- **What changed and when:** [obligare.com/changes](https://obligare.com/changes).

## What is in it

Federal filings from the IRS, the SSA, the Department of Labor, the EEOC, OSHA and FinCEN, including the Form 990 family. For every state and the District of Columbia: annual and biennial reports, franchise taxes, charitable solicitation registration, state income tax returns and estimates, employer filings (unemployment insurance, withholding reconciliation, paid family and medical leave, retirement savings mandates) and sales tax returns.

Each obligation has an `id` (for example `us.de.corp.report`), `jurisdiction`, `applies` (the profile conditions), `schedule` (one of ten schedule types), `agency`, `form`, `fee`, `penalty`, `severity`, `source` (the agency page) and `explain`. The top level carries `version`, `published` and `changes`.

## License

[Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). Use it, copy it, build on it, commercially or not. Credit it as:

> Obligare US rules pack, Alleviate Technologies, Inc., [obligare.com](https://obligare.com), CC BY 4.0

The pack states obligations as read from government sources. It is not legal or tax advice. Confirm a date with the agency or a professional before relying on it.

## Corrections

Found a wrong date, fee or rule? Open an issue with the agency page that shows it, or write to hello@obligare.com.
