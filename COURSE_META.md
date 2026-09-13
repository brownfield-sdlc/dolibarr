# Dolibarr — Demo Estate Metadata

## Role in Course
Legacy baseline — PHP/MySQL ERP, 416 tables, inline SQL (SQL injection risks).

## Estate Inventory
- Language: PHP
- Database: MySQL (tested on Docker, not yet)
- Tables: 416
- Testing: PHPUnit (may be sparse)
- CI/CD: (GitHub Actions present)
- Docs: Wiki-style

## Phase P Tasks
- [ ] Docker MySQL setup (mirrors DNN approach)
- [ ] Video 5: Record Dolibarr schema exploration
- [ ] Extract inline SQL patterns for analysis

## Metrics (Track Here)
| Metric | Baseline | Target |
|--------|----------|--------|
| Queries with raw SQL | TBD | Reduce by 50% |
| SQL injection risk score | TBD | A → B |
