# GRLM-LTC-Exchange

## GRLM to LTC exchange example
### Exchange
1. A user (Bob) wants to transfer 60 GRLM into LTC.

2. Bob makes a request to the Exchange asking to transfer GRLM to LTC.
 - Bob gives the exchange his GRLM and his LTC wallet addresses.

3. The Exchange gives Bob a GRLM wallet address to transfer his 60 GRLM to.

4. Once the Exchange verifies the 60 GRLM has been transferred, it converts 60 GRLM to LTC at the current exchange rate.
 - It also moves the 60 GRLM from the temporary wallet into a main Exchange GRLM wallet.

5. At the current Exchange rate (E.G.: 1 LTC = 10 GRLM), Bob recieves some LTC into his account from the Exchange, minus a service charge.

### Security
1. An end user never directly interacts with any of the wallets holding LTC or GRLM.
 - So GRLM is sent to a temporary wallet.
 - And LTC is recieved from a temporary wallet.
 - And vice versa.

2. The Exchange converts all GRLM found inside the temporary wallet into LTC.
 - This is less security oriented and more best practices to ensure trustworthyness of the Exchange.