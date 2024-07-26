<!--p align="center">
     <img width="1412" src="https://cdn.aleo.org/leo/banner.png">
</p-->

<h1 align="center">Deploying davyking_auction.aleo</h1>

* First I installed git
* Then i installed rust on my mac (curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh)
* Lastly i installed leo (curl -L https://raw.githubusercontent.com/AleoHQ/workshop/master/install.sh | sh )
## <a name='TableofContents'></a>Running the code

- [🍎 Overview](#-running code)

## 🍎 Overview
- Navigate to davyking_auction/
- I first tested the program
```bash
leo run place_bid aleo17673w3sp497ut7wg38uyrsyzqn3nnu552s56024a52jnmylsrsgssza5pa 100000u64 # to deploy to testnet(set the correct private key)
```
- I used my cli to build and deploy the program
```bash
leo deploy --network testnet # to deploy to testnet(set the correct private key)
```
-- Final result --
```bash
Leo ✅ Compiled 'davyking_auction.aleo' into Aleo instructions
📦 Creating deployment transaction for 'davyking_auction.aleo'...


Base deployment cost for 'davyking_auction.aleo' is 11.385475 credits.

+-----------------------+----------------+
| davyking_auction.aleo | Cost (credits) |
+-----------------------+----------------+
| Transaction Storage   | 2.778000       |
+-----------------------+----------------+
| Program Synthesis     | 7.607475       |
+-----------------------+----------------+
| Namespace             | 1.000000       |
+-----------------------+----------------+
| Priority Fee          | 0.000000       |
+-----------------------+----------------+
| Total                 | 11.385475      |
+-----------------------+----------------+

Your current public balance is 16.946387 credits.

? Do you want to submit deployment of program `davyking_auction.aleo.aleo` to network testnet via endpoint https://api.explorer.aleo.org/v1 using address aleo17673w3sp497ut7wg38uyrsyzqn3nnu552
✔ Do you want to submit deployment of program `davyking_auction.aleo.aleo` to network testnet via endpoint https://api.explorer.aleo.org/v1 using address aleo17673w3sp497ut7wg38uyrsyzqn3nnu552s56024a52jnmylsrsgssza5pa? · yes
✅ Created deployment transaction for 'davyking_auction.aleo'

Broadcasting transaction to https://api.explorer.aleo.org/v1/testnet/transaction/broadcast...

⌛ Deployment at13la3yr202tgc3ywzq7r26adyced4u2plpfw8tg9chq28vy7wxq8qhqymnh ('davyking_auction.aleo') has been broadcast to https://api.explorer.aleo.org/v1/testnet/transaction/broadcast.
```
