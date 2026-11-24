# POS stock deduction — technical design
Requirement: REQ-003
Rule: successful sales reduce stock.
Reject quantities <= 0 and sales above stock.
Design choice: stock update method to be decided.
Expected: stock 10, sale 2 -> stock 8.
