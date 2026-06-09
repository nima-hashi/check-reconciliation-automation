# Proposed Workflow

## Check Workflow

1. Login to bank account
2. Download paid check images
3. Extract:
   - Vendor
   - Amount
   - Date
   - Check Number
4. Save as structured data (whatever is smart)
5. Export (to whatever we use.. example: excel?)

## Invoice Workflow

1. Download invoices from email
2. Extract:
   - Vendor
   - Invoice Number
   - Amount
   - Date
3. Save as structured data

## Reconciliation Workflow

1. Compare invoice data against check data
2. Match records
3. Identify:
   - Missing invoices
   - Missing checks
   - Amount mismatches
4. Generate reconciliation report
