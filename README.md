# Bitcoin-Testnet-using-Python

Assignment 3

In this assignment, you will use the Bitcoin testnet to conduct Bitcoin transactions.

First create a private key, a public key, and a Bitcoin address on the testnet, using this
website: https://www.bitaddress.org/

To generate a testnet address, append ?testnet=true to the browser URL when you
access the website address above. You should see “TESTNET EDITION ACTIVATED”.

Save your Bitcoin address, and (securely) save your private key.
1. What is your Bitcoin address on testnet?
2. What is your public key?

You can receive coins on the testnet from a “faucet” that can send non-monetary coins to
your address. Use https://testnet-faucet.mempool.co/ to receive 0.005 coins.

3. What is this transaction ID?

Use https://blockstream.info/testnet to answer the following:

4. What is the transaction fee?
5. What is the block number that included this transaction?
6. Estimate how long did the transaction take to get included in a block

Using the Python Bit library (https://ofek.dev/bit), verify the following:

7. Your Bitcoin address on testnet, given your private key
8. Your balance in bitcoin (btc)

Also, using the Bit library, create a transaction and send 1 mBTC to the following address:
mh4SbUqFzWzC6KhfUtLmZ5ch3iFwVQURjM

9. What is the transaction ID for this new transaction?
10. What is the block number that includes this transaction?
11. What was the transaction fee?
12. Verify your new balance after the transaction.
