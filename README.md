# demo-stock-management
Ledger-style stock management system built with React Router

This demo system implements ledger-style stock management with React Router and is built on an ASP.NET Core Web API on top of a SQL Server database with Entity Framework.

## Quick start

The quickest way to start the app is with Docker Compose from the repository root
```
docker compose up --build
```

## Key features
- No quantity tracking
- Full transaction ledger
- IN transactions set initial stock quantity by batch number
- OUT transactions update stock with necessary reductions
- FEFO (first expired, first out) item picking
- No picking of expired items
- Optional stock handling rule-based business logic