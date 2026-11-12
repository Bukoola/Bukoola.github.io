# Theatre Producer FP&A Dashboard

**An interactive Power BI dashboard that answers the three questions a West End producer's finance director asks every month: are we on budget, what is driving the variances, and where will the year land?**

> Status: in progress

<!-- Add a screenshot of the main dashboard page here, e.g.:
![Dashboard overview](screenshots/overview.png) -->

## The business

Touchgold Productions Ltd is a fictional producer with two West End shows, one show in its opening period and three touring productions. Its financial year runs January to December. The dashboard is built for the finance director, producers and shareholders.

## Questions it answers

1. **Are we on budget?** Actual vs budget by production, month and cost line.
2. **What drives the variances?** Box office, running costs and other lines broken down so the main causes are visible at a glance.
3. **Where will the year land?** A full-year latest estimate combining actuals to date with the forecast for the remaining months.

## Data and build

- **Data:** publicly sourced industry figures (Society of London Theatre, UK Theatre, Companies House filed accounts, Arts Council England, HMRC Theatre Tax Relief statistics), used to set realistic levels for the fictional company.
- **Model:** star schema with fact tables for actuals and budget, and dimensions for production, date and account.
- **Transformation:** Power Query (M).
- **Measures:** DAX for variance, variance %, year-to-date, and full-year latest estimate.
- **Design:** written for both finance and non-finance readers.

<!-- Add: 2–3 findings or features you're proud of once the build is finished,
e.g. "Tours ran 8% over budget, driven by get-in costs". -->

## Files

| Path | Contents |
| --- | --- |
| `*.pbix` | The Power BI file |
| `screenshots/` | Images of each dashboard page |
| `data/` | Source and prepared data files |
