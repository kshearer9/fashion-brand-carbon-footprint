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
| Scope 1 | Gas used to heat the shop and studio | To do |
| Scope 2 | Electricity used in the shop and studio (location-based and market-based) | In progress |
| Scope 3 | Purchased goods (fabrics and garments), inbound transport, business travel, deliveries to customers | To do |

Emissions are calculated as **activity data × emission factor**, and reported in kg CO2e and tCO2e.

## Data

- **Emission factors:** [DESNZ Greenhouse gas reporting: conversion factors 2025](https://www.gov.uk/government/publications/greenhouse-gas-reporting-conversion-factors-2025), condensed set. The file isn't included in this repo. To check the factors, download the condensed set and save it in `data/raw/`.
- **Activity data:** fictional, with assumptions documented on the Assumptions sheet of the workbook

Contains public sector information licensed under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).
