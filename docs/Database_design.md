# Database Design

## Current Tables

### organizations_organization

| Column | Type | Constraints |
|---|---|---|
| id | bigint | Primary Key |
| name | varchar(150) | NOT NULL |
| email | varchar(254) | NOT NULL, UNIQUE |
| created_at | timestamp | NOT NULL |

## Relationships

Currently:

Organization

Future relationships:

Organization
├── Users
├── Subscriptions
├── Invoices
├── Payments
└── Usage Records