# Tokens

## ![](../.gitbook/assets/djinn32x32.png) [Djinn Gold \(DJINN\)](https://www.bscscan.com/token/0x24eacca1086f2904962a32732590f27ca45d1d99)

DJINN is the stable coin pegged to 1g of gold!

The protocol will attempt to adjust the supply of DJINN such that the price of the token remains at its pegged value. The protocol uses two additional tokens described below to expand and contract the overall supply of the token.

Supply expansion and contraction occurs in 4 hour phases called epochs. Each epoch allows for a 2% expansion or contraction based on the time weighted average price \(TWAP\).

## ![](../.gitbook/assets/djinnshare32x32.png) [Djinn Share \(DJINNS\)](https://www.bscscan.com/token/0xb0168Bca7dB2eFe53b9112c08aae36D744800645)

Shares can be staked in the protocol's boardroom in order to receive DJINN during supply expansion. Supply expansion is distributed proportionally to all staked board members.

Shareholders can withdraw from the boardroom only after 12 epochs \(48 hours\). Rewards from DJINN supply expansion are locked for 3 epochs \(12 hours\). Any actions by board members \(ie, depositing shares, withdrawing shares, claiming supply expansion rewards\) will reset both timers.

Total supply capped to 10,000.

## ![](../.gitbook/assets/djinnbond32x32.png) [Djinn Bond \(DJINNB\)](https://www.bscscan.com/token/0x2e976c9a80d0eeD5Bd80084365a87E59CFbb90A8)

When DJINN is below the peg, holders can buy bonds at a discount and redeem them later at a 1:1 ratio when the coin rises above peg.

The discount is proportional to the price of DJINN below the peg. If DJINN is at 0.09g of gold, the discount will be 10%. If DJINN is at 0.05g of gold, the discount will be 50%.

Each bond issued represents debt which must be repaid later during supply expansion. If there are outstanding bonds, 70% of expansion is saved to repay bond debt, the remaining expansion is then distributed to shareholders.

The maximum debt is 50% of the supply of DJINN. In other words the supply of bonds cannot exceed half the supply of DJINNS.

