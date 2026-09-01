# ENS Working Group Transactions

Historical transaction data from the ENS DAO Working Group multisigs, exported
from [SafeNotes](https://discuss.ens.domains/t/introducing-safenotes-a-new-standard-for-dao-spending-transparency/20245)
before the service was shut down. 1,056 transactions across 8 safes, July 2022
through July 2026, annotated from January 1, 2024 onward.

[`ens_wg_transactions.csv`](ens_wg_transactions.csv) — columns are `Date`,
`Safe`, `Amount` (negative is an outflow), `To/From`, `Category`, `Description`.
Rows before 2024 were never annotated and carry `Category = None`.

Note that `Internal Transfer` rows are movements between working group safes,
not spend.
