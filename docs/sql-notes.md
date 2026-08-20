# SQL Learning Journal

## Database

PostgreSQL 18

Database:

saas_billing

---

# 1. SELECT

## Concept

SELECT is used to retrieve data from a table.

## Basic Syntax

SELECT column1, column2
FROM table_name;

## Project Example

SELECT id, name, email
FROM organizations_organization;

## SELECT *

SELECT * returns all columns.

Example:

SELECT *
FROM organizations_organization;

## Best Practice

Prefer explicitly selecting required columns instead of using SELECT *
when the required columns are known.

---

# 2. Column Aliases

## Concept

An alias temporarily changes the name displayed for a column.

## Syntax

SELECT column_name AS alias_name
FROM table_name;

## Project Example

SELECT name AS company_name,
       email AS contact_email
FROM organizations_organization;