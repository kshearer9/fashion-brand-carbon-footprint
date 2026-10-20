# Fashion Brand Carbon Footprint

A project where I'm putting the GHG Protocol into practice by building a simple emissions inventory for a fictional small British fashion brand.

## The brand

The brand is made up, but based loosely on the kind of small, design-led British label that makes most of its products in the UK and some overseas. It has:

- a studio and a shop in London
- a small product range (e.g. shirts, knitwear, a tweed jacket), with fabrics and finished goods bought from UK and overseas suppliers
- a small team who travel occasionally for work
- online orders delivered to customers in the UK

All activity data (energy use, quantities, distances) is invented.

## Scope and approach

The inventory follows the GHG Protocol Corporate Standard, covering one reporting year.

| Scope | What's included | Status |
|---|---|---|
| Scope 1 | Gas used to heat the shop and studio | To do |
| Scope 2 | Electricity used in the shop and studio (location-based) | In progress |
| Scope 3 | Purchased goods (fabrics and garments), inbound transport, business travel, deliveries to customers | To do |

Emissions are calculated as **activity data × emission factor**, and reported in kg CO2e and tCO2e.

## Data

- **Emission factors:** UK Government GHG Conversion Factors for Company Reporting (DESNZ), 2026 edition
- **Activity data:** fictional, with assumptions documented in the notebook
