# Nationwide Auto & Home Insurance Claims Analysis

This project is a portfolio-ready SQL analytics case study simulating a nationwide insurance company operating across ~40 U.S. states. It includes customers, Auto & Home policies, and multi-year claims data with realistic approval and denial logic.

The goal of this project is to demonstrate data analytics skills using PostgreSQL, including schema design, data modeling, joins, aggregations, and KPI analysis.

--- Project Structure

- `schema.sql` – Creates all database tables:
  - customers
  - policies (Auto & Home)
  - customer_policies (bridge table)
  - claims (multi-year claims data)

- `mock_data.sql` – Inserts realistic synthetic data:
  - ~800 customers across multiple states
  - ~1,300 policies
  - 2,500 claims from 2021–2025
  - Logical approval/denial outcomes

- `analysis.sql` – Advanced analytical SQL queries including:
  - Customer segmentation by state
  - Policy type comparisons (Auto vs Home)
  - Claims trends over multiple years
  - Approval rate analysis
  - Loss ratio calculations
  - High-cost denied claims for risk insight

---Tech Stack

- PostgreSQL (cloud-ready, e.g., Supabase)
- SQL (DDL, DML, joins, aggregations, KPI calculations)

Skills demonstrated:
- Relational schema design with PK/FK constraints
- Multi-table joins and bridge tables
- Aggregations (SUM, AVG, COUNT)
- Conditional filtering and grouping
- Multi-year trend analysis
- Insurance risk and KPI analysis (loss ratio, approval rates)

---How to Run (Click-and-Run)

1. Create a PostgreSQL database (local or cloud).
2. Run the schema file to create tables:
   ```sql
   \i schema.sql
