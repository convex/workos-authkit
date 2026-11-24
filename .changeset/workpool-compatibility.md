---
"@convex-dev/workos-authkit": patch
---

Update the backfill component to Workflow 0.5 and support Workpool 0.4.16 and 0.5.x.

Workpool 0.5 requires Convex 1.47 or later. If upgrading from Workpool
earlier than 0.4.15, first deploy Workpool 0.4.15 and run
`npx convex run --component workOSAuthKit/backfillWorkflow/workpool migrations:backfillPendingStartIds`
for each installed instance, adjusting the component path for custom names.
