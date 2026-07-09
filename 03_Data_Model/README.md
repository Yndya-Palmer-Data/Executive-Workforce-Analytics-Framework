# Data Model

## Overview

The Workforce Analytics Framework combines data from multiple enterprise personnel systems into a unified reporting model that enables leadership to monitor workforce readiness, staffing, retention, and manpower allocation.

The purpose of the data model is to organize workforce information into meaningful business entities that support executive dashboards and strategic decision-making.

## Example Data Sources

- Defense Civilian Personnel Data System (DCPDS)
- Full-Time Support Management Control System (FTSMCS)
- General Fund Enterprise Business System (GFEBS)
- Other Human Resources and Personnel Systems

## Example Data Entities

- Personnel
- Organization
- Position
- Unit
- Vacancy
- Readiness
- Recruiting
- Retention

## Sample Relationships

- One Organization contains many Units.
- One Unit contains many Personnel.
- One Position may be Filled or Vacant.
- Personnel belong to one Organization and one Position.
- Workforce metrics are aggregated by Organization, Unit, and Reporting Period.

## Business Value

A well-designed data model provides a single source of truth that supports accurate reporting, trusted analytics, and consistent executive decision-making.
