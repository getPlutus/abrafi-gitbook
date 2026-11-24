# How borrowing works

* **With USDaf collateral:** open and closed losses are paid from your USDaf. Nothing is borrowed.
* **With other collateral:** at each hourly check, any open loss is borrowed against your collateral and interest starts. Between checks, the Borrowing card shows what will be borrowed at the next check.
* **When a position closes at a loss:** it is paid from your USDaf first, then from what was borrowed for it. That amount stays owed. Your collateral is not sold.
* **When losses recover:** borrowing follows them back down hour by hour and the borrowed amount is returned.
* **Owing doesn't stop trading.** Copies keep following the strategy while interest runs.

Example: with $20,000 of BTCaf and no USDaf, a copy is down $6,000 at 11:00, so $6,000 is borrowed. At 12:00 it is down $9,000, so $3,000 more is borrowed. At 13:00 it is down $2,400, so $6,600 is returned. At 14:00 it is up $1,600 and the rest is returned, leaving only a few cents of interest owed.
