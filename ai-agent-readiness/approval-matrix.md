# Approval matrix

| Action (tool) | Risk | Autonomous when… | Otherwise approved by | SLA | Logged |
|---|---|---|---|---|---|
| create_refund_request | High | amount ≤ $100 and order delivered | Support lead | 4h | ✅ |
| post_draft_bill | Medium | no validation findings and total ≤ $2,500 | AP clerk | 1 business day | ✅ |
| release_payment | Critical | never | Controller | — | ✅ |
| grant_app_access | High | never for admin roles | App owner | 1 business day | ✅ |
