# Changelog

## 2026-11-19

- Ticket distribution and weighted winner selection no longer debit a ticket.
- Added an explicit empty-confirmation `input_button` helper. The selected actual emptier is charged one ticket only when that button is pressed.
- Added a one-charge-per-cycle guard; repeated confirmation cannot charge another person before a new wash starts.
- Removed automatic refund/debit behavior from manual selection changes. A selection may be changed to the actual emptier before confirmation.
- Updated setup guidance and the flow diagram to match the confirmation-based accounting.
