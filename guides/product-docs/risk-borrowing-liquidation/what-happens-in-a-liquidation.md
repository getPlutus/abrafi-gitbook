# What happens in a liquidation

1. **Warning.** As equity nears what your open positions need (maintenance margin), the bell warns you.
2. **Reducing.** Below maintenance margin, positions are closed through the order book in rounds, each with a liquidation fee, until the account is back above maintenance.
3. **Auction.** Only if every position is closed and you still owe more than your collateral covers is collateral sold, at an oracle-priced auction. Only enough is sold to repay what you owe; the rest stays yours.
4. **Finished.** The red strip and the dot on Collateral disappear once the account is healthy again.

Liquidation for markets with sessions waits for markets to reopen (weekend pause).
