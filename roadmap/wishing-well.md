# Wishing Well

[Wishing Well](https://www.wishingwell.gold/) is a lottery game where players can choose how much they would like to win.

## Mechanics

Each round, players can make wishes for a set amount of DJINN. Only one player may wish for a specific amount, so if there is already a wish for that amount, try adding a few decimal places!

At the end of each round, a random amount from 0 to the prize pool is rolled. The highest wish under this amount is granted. The prize is then transferred automatically to the winner.

There may be a slight delay for the round to reset and the prize to be paid. Please be patient!

## Countdown

Each round has a countdown timer which starts at 24 hours. Each wish increases this countdown by 30 minutes. If there are over 100 wishes, this countdown is increased by 5 minutes instead. The coundown will never exceed 24 hours.

## Prize Pool Setup

The Wishing Well maintains a budget to set up a starting prize pool each round. The prize pool is set to 20% of the Wishing Well's balance at the start of each round.

Fees collected during a round are added directly to the prize pool.

At the end of each round, if the winning prize was less than the total fees collected, half the difference is collected as profit. The remaining pool is returned to the Wishing Well's balance and used to set up the next prize pool.

For now, this profit will be completely burned to combat inflation. As the ecosystem develops, this will eventually used to advance other projects.

## Randomness

The game currently relies on external randomness which is fed into the game via the automated game master. The game master generates a pseudo random bit stream which is fed into the game contract, which is then further hashed.

The contract has been set up in a way which will allow the integration of chainlink verifiable randomness to be integrated as soon as it is released on the binance smart chain!

## Contract

[0x76f9A5d3062682b05102049e679885379eba6AdD](https://bscscan.com/address/0x76f9a5d3062682b05102049e679885379eba6add)

