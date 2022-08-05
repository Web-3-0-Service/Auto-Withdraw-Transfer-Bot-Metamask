# ⚠️You can buy the script Python on [@discord](https://discord.gg/zE5nUjbbk8) ⚠️

<!-- ABOUT THE PROJECT -->
## `👻 About the project : `

The project represents script allowing you create a loop of constant/automatic requests to your wallet withdrawing the balance. At this moment it does it for only native token of the chain you use: ETH, MATIC, BNB, AVAX etc.

There are multiple usecases for this:
  1) You might need to redirect incoming transaction from multiple wallets to the main one.
  2) You might need to protect your account and set up script when you are not using the wallet, and shutting the script off only when you need to      make some transactions and back on when you are done.
  3) You might somehow disposed your private keys and want to protect other tokens you have on wallet. So emptying the wallet balance will prevent      scammers making any other transaction.

## `👻 Build With : `

* [Python](https://python.org/)
* [Web3](https://pypi.org/project/web3/)

## `👻 Getting Started : `

1. Buy it on the [@discord](https://discord.gg/zE5nUjbbk8) of Web-3.0 Service Agency

## `👻 Installation : `

2. Install Python
   Choose latest release for your OS https://www.python.org/downloads/
3. Enter your Wallets and Key in `loop.py`
   ```py
   private_key = "<Your_Private_Key"
   pub_key ="<Your_wallet>"
   recipient_pub_key = "<Recipient_wallet>"
   ```
4. Enter your gasPrice, gasLimit and chainId in `loop.py`
   ```py
    gasPrice = w3.toWei('30', 'gwei')
    gasLimit = 21000
    
    tx = {
            'chainId': 3,
   ```
   You can find your chain ID here: https://chainlist.wtf/.<br></br>
   Your current required gasPrice in gwei here: 
     * [Ethereum](https://etherscan.io/gastracker)
     * [Polygon](https://polygonscan.com/gastracker)
     * [Binance](https://bscscan.com/gastracker)
     * [Avalanche]( https://snowtrace.io/gastracker)

5. Add the Endpoint for the chain you chose.
   ```py
   w3 = Web3(Web3.HTTPProvider(<Moralis or Infura_endpoint_link>)
   ```
   Visit https://moralis.io or https://infura.io/ or any other endpoint you can find.

6. Run the script
   ```py
    python loop.py
   ```


<!-- USAGE EXAMPLES -->
## `👻 Example of script running : `
<img width="220" alt="image" src="https://user-images.githubusercontent.com/74835523/172040143-9e39478d-fc9c-4fe8-843c-bc27ecfeeea0.png">




<!-- CONTACT -->
## `👻 Contact : `

Camelotis - https://twitter.com/Camelotis98

Web 3.0 Service Agency discord - https://discord.gg/zE5nUjbbk8
