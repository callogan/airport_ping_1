# Airport Service API

There is API for tracking flights.

* Create new borrowing: borrowing the book results in making the record in the ledger about borrowing
creation and corresponding changes of the inventory.
* Get borrowing collection - glean a list of borrowings based on 2 criteria:
  - user ID (for admin only),
  - "is active" status for the borrowing (either the book is returned or not).