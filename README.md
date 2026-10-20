# Fashion Brand Carbon Footprint

A project where I'm putting the GHG Protocol into practice by building a simple emissions inventory for a fictional small British fashion brand.

## The brand

The brand is made up, but based loosely on the kind of small, design-led British label that makes most of its products in the UK and some overseas. It has:

- a studio and a shop in London
- a small product range (e.g. shirts, knitwear, a tweed jacket), with fabrics and finished goods bought from UK and overseas suppliers
- a small team who travel occasionally for work
- online orders delivered to customers in the UK

## Scope and approach

The inventory follows the GHG Protocol Corporate Standard and covers the calendar year 1 January to 31 December 2025.

| Scope | What's included | Status |
|---|---|---|
| Scope 1 | Gas used to heat the shop and studio | Done |
| Scope 2 | Electricity used in the shop and studio (location-based and market-based) | Done |
| Scope 3 | Purchased goods (fabrics and garments), inbound transport, business travel, deliveries to customers | To do |

Emissions are calculated as **activity data × emission factor**, and reported in kg CO2e and tCO2e.

## Results (Scopes 1 and 2)

| | t CO2e |
|---|---|
| Scope 1 | 8.84 |
| Scope 2, location-based | 4.26 |
| Scope 2, market-based | 5.56 |
| **Total, location-based** | **13.10** |
| **Total, market-based** | **14.40** |

- Gas heating is the largest source so far.
- The market-based figure is higher than location-based. The studio's renewable tariff (backed by REGOs) brings its electricity to zero, but the shop's landlord-supplied electricity has no supplier information, so it uses the UK residual mix, which is more than double the grid average.

## Limitations

- Energy use is estimated from benchmarks, not meter readings or bills.
- The studio uses the office benchmark, which probably underestimates electricity for workroom machines.
- The shop's market-based factor is CO2 only, because the residual mix source doesn't include other gases.
- Transmission and distribution losses (Scope 3 Category 3) aren't included yet.

## Data

- **Emission factors:** [DESNZ Greenhouse gas reporting: conversion factors 2025](https://www.gov.uk/government/publications/greenhouse-gas-reporting-conversion-factors-2025), condensed set. The file isn't included in this repo. To check the factors, download the condensed set and save it in `data/raw/`.
- **Activity data:** fictional, with assumptions documented on the Assumptions sheet of the workbook
- **Energy use:** estimated from floor area using median energy intensity (kWh per m²) from [ND-NEED 2026](https://www.gov.uk/government/statistics/non-domestic-national-energy-efficiency-data-framework-nd-need-2026), 2024 data
- **Residual mix:** calculated from the DESNZ [Fuel mix disclosure data table](https://www.gov.uk/government/publications/fuel-mix-disclosure-data-table/fuel-mix-disclosure-data-table)

Contains public sector information licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).
