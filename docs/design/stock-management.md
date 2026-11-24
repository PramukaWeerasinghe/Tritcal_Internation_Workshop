# POS stock deduction — technical design
Requirement: REQ-003
Rule: successful sales reduce stock.
Reject quantities <= 0 and sales above stock.
Design choice: queued update.
Expected: stock 10, sale 2 -> stock 8.
