# 📊 Advanced Database Project

## 🏗️ Project Architecture

This repository is organized to reflect a complete database system lifecycle, including schema design, transactions, optimization, and data warehousing.

```
advanced-db-project/   (root - main branch)
│
├── docs/                     # 📄 Shared documentation
│   ├── EERD.png              # Entity-Relationship Diagram (M1)
│   ├── star-schema.png       # Data Warehouse Schema (M4)
│   └── report.md             # Final project report (M5)
│
├── sql/                      # 🗄️ SQL Server scripts
│   ├── 01-schema/            # Database schema (M1)
│   │   ├── create_tables.sql
│   │   └── constraints.sql
│   │
│   ├── 02-seed/              # Sample data (M3)
│   │   └── insert_data.sql   # 20–50 rows per table
│   │
│   ├── 03-queries/           # Basic queries (M1)
│   │   └── basic_queries.sql
│   │
│   ├── 04-transactions/      # Transactions & recovery (M2)
│   │   ├── transactions.sql
│   │   └── recovery_demo.sql
│   │
│   ├── 05-concurrency/       # Concurrency control (M2)
│   │   ├── session_a.sql
│   │   └── session_b.sql
│   │
│   ├── 06-stored-proc/       # Stored procedures (M3)
│   │   └── book_appointment.sql
│   │
│   ├── 07-window-functions/  # Analytical queries (M3)
│   │   └── window_queries.sql
│   │
│   ├── 08-optimization/      # Performance tuning (M4)
│   │   ├── indexes.sql
│   │   └── tuning_queries.sql
│   │
│   └── 09-datawarehouse/     # Data warehouse & ETL (M4)
│       ├── dwh_schema.sql
│       ├── etl.sql
│       └── analytical_queries.sql
│
├── mongodb/                  # 🍃 NoSQL part (M5)
│   └── prescriptions_queries.js
│
├── screenshots/              # 📸 Required submission assets
│   ├── transactions/
│   ├── concurrency/
│   └── optimization/
│
├── run_all.sql               # ▶️ Master script to run all SQL files (M5)
└── README.md                 # 📘 Project documentation
```



---

## 📌 Notes

* Each module (M1 → M5) represents a milestone in the project.
* The structure separates concerns clearly:

  * Schema & data
  * Transactions & concurrency
  * Advanced SQL features
  * Optimization
  * Data warehousing
* MongoDB is included for NoSQL integration.

---

## 👥 Team

Project developed as part of the Advanced Database course.
