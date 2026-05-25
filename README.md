# Border Customs Operations Suite

Wave:
- Portfolio next-20 completion batch

Source candidates represented:
- `AIBorderCustomsOperationsAssistant`
- `AIBorderCustomsOperationsOperations`
- `AIBorderCustomsOperationsAnalytics`
- `AIBorderCustomsOperationsWorkflow`

This suite is a runnable merged app with one login, one dashboard, one feature-first sidebar, PostgreSQL-backed records/documents/notifications/audit, role behavior, and smoke coverage.

## Local Run

```bash
cd /Users/erolakarsu/projects/merged/border-customs-operations-suite
./start.sh
```

Local URL:
- `http://127.0.0.1:4910`

Seeded users:
- `admin@border-customs-operations.local / admin123`
- `manager@border-customs-operations.local / manager123`
- `analyst@border-customs-operations.local / analyst123`

## Validation

```bash
cd /Users/erolakarsu/projects/merged/border-customs-operations-suite/frontend
npm run typecheck
SMOKE_BASE_URL=http://127.0.0.1:4910 npm run smoke
```
