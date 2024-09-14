# Turbin3 Builders Course

## Exercise 1

### Create a solana wallet and get some devnet founds from the faucet.

Create solana wallet public key + secret key with: 

- `yarn keygen`

The wallet created for the exercise:  
6J5hJx5LmCzgNRWRsvreCTCoTtVg3m777QAzMqYDsnb3

 Get some founds with: 

- `yarn airdrop`

The transaction requesting founds created: 
Success! Check out your TX here: [Airdrop proof](https://explorer.solana.com/tx/3Xxi2A9miULvu84PRqovvFbUZKqbCt2JK6YbT4HkohXBiv7FigFpmgqJpD3pY8PfdeQU8vNWxw1TqDy9S1REMcS1?cluster=devnet)

## Exercise 2 

### Create a script to transfer SOL balence from your wallet to another solana address with your wallet.

1. First of all set up the wallet you wallet from dev-wallet.json

2. Set your receiver address here: `const to = new PublicKey("<RECEIVER ADDRESS>");`



3. Run  `yarn transfer`

My transfer: 

Success! Check out your TX here: [Transfer](https://explorer.solana.com/tx/yWRbR2xcRSqhrN5q8nrpnixPwSKswzocb1C1T7xLbdayQuXwmj6aK2rm287tPt7jSApPhGMPt7FVYMtD76YXDvW?cluster=devnet)