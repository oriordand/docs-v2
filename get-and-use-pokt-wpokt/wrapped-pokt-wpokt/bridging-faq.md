# Bridging FAQ

### How can I swap my POKT for wPOKT? <a href="#how-can-i-swap-my-pokt-for-wpokt" id="how-can-i-swap-my-pokt-for-wpokt"></a>

**Before getting started, note that the end-to-end wrapping process is expected to take \~30 mins, and that minting wPOKT will cost gas (in ETH).**

Prepare to wrap your POKT by connecting Ledger, SendWallet, or NodeWallet to the bridge. The official POKT wallet does not have built in support for wPOKT, but you can import the official wallet to any of the supported options. See the specific wallet’s documentation for instructions on How-To import.

* If you don’t have a wallet, you can learn more about your wrapping POKT wallet options below:
  * [Ledger wallet](https://support.ledger.com/hc/en-us/articles/12976051037853-Pocket-POKT-?docs=true)
  * [SendWallet](https://www.sendwallet.net/)
  * [NodeWallet](https://docs.decentralizedauthority.com/nodewallet)
* Prepare to mint your wPOKT by connecting your Ethereum wallet. Make sure your Ethereum wallet has some ETH for gas fees. If you don’t have enough gas, the bridge app will tell you.
* You will not be able to initiate the wrap transaction until you have connected both wallets.
* Specify the amount of POKT tokens to wrap into wPOKT tokens, then click Wrap.
* After \~30 minutes, if you’ve completed all the steps, you will receive your wPOKT.

{% hint style="info" %}
**Note**

You will be required to sign 2 transactions, first to deposit your POKT and then to mint your wPOKT. We recommend you keep the modal open and stay in the app until both transactions have been confirmed. If you leave the app before both transactions complete, it will remain pending until you return and finish them.

If you’re wondering why wPOKT isn’t in your wallet after 30 minutes, double check you’ve completed both transactions.
{% endhint %}

### What wallets are approved for wrapping POKT? <a href="#what-wallets-are-approved-for-wrapping-pokt" id="what-wallets-are-approved-for-wrapping-pokt"></a>

You can use:

* [Ledger](../pokt-wallets/)
* [SendWallet](https://sendwallet.net/)
* [NodeWallet](https://docs.decentralizedauthority.com/nodewallet)

What about the official POKT Wallet?

* The official POKT wallet does not have built in support for wPOKT, but you can import the official wallet to any of the supported options. See the specific wallet’s documentation for instructions on How-To import.

### Why haven’t I received my wPOKT yet? <a href="#why-havent-i-received-my-wpokt-yet" id="why-havent-i-received-my-wpokt-yet"></a>

* **Where did my minting pop-up go?** If you navigate away, the pop-up will disappear until the 2nd transaction is ready to be minted. If it’s not appearing, try refreshing your browser after the 30m waiting period.
* **Are you looking in the right place?** First check that you’re looking at the correct blockchain. wPOKT lives on the Ethereum blockchain, so you will not see wPOKT in your Ethereum wallet unless you are connected to the Ethereum RPC. You can easily connect your wallet to the Ethereum RPC via Pocket Network using this [site](https://rpclist.info/). To cross-check, you can also search your ETH wallet address on [Etherescan](https://etherscan.io/) to see if the wPOKT balance appears there.
* **Have you waited long enough?** An end-to-end wrapping of POKT is expected to take approximately 30 minutes. In some cases, it may take up to an hour.
* **Have you added the wPOKT token address to MetaMask?** If your MetaMask wallet isn’t auto-populating the wPOKT address, you’ll need to add it manually. Follow instructions [here](https://support.metamask.io/hc/en-us/articles/360015489031-How-to-display-tokens-in-MetaMask#h\_01FWH492CHY60HWPC28RW0872H). The wPOKT address is 0x67f4c72a50f8df6487720261e188f2abe83f57d7 and it should autopopulate once it’s pasted in.

If you have confirmed you’re looking in the right place and you have waited a little longer, but you still do not see your tokens, please contact us for support on our [Discord server](https://discord.com/channels/553741558869131266/1159177817574088724).

### How can I unwrap my wPOKT back to POKT? <a href="#how-can-i-unwrap-my-wpokt-back-to-pokt" id="how-can-i-unwrap-my-wpokt-back-to-pokt"></a>

Before getting started, note that the end-to-end unwrapping process is expected to take upwards of 30 mins.

* Prepare to burn your wPOKT by connecting your Ethereum wallet to the bridge. Make sure your Ethereum wallet has some ETH for gas fees. If you don’t have enough gas, the bridge app will tell you.
* Prepare to unwrap your POKT by connecting your Ledger, SendWallet, or NodeWallet.
* You will not be able to initiate the unwrap transaction until you have connected both wallets.
* Specify the amount of wPOKT tokens to unwrap into POKT tokens, then click Unwrap.
* After \~30 minutes, you should receive your POKT.

### Why haven’t I received my POKT yet? <a href="#why-havent-i-received-my-pokt-yet" id="why-havent-i-received-my-pokt-yet"></a>

* **Are you looking in the right place?** Make sure you are checking your POKT wallet for the balance, not your Ethereum wallet.
* **Have you waited long enough?** An end-to-end unwrap of POKT is expected to take approximately 30 minutes. If it has not been 30 minutes or it has only recently turned 30 mins, please try waiting a little longer.

If you have confirmed you’re looking in the right place and you have waited a little longer, but you still do not see your tokens, please contact us for support on our discord: discord.gg/pokt

### Why does the bridge take up to 30 mins? <a href="#why-does-the-bridge-take-up-to-30-mins" id="why-does-the-bridge-take-up-to-30-mins"></a>

* **Pocket Network block times.** Pocket Network blocks complete every 15 minutes. Depending on when you sign the transaction, it may take up to 15 minutes for your transaction to appear on-chain.
* **Bridge validation time.** The wPOKT bridge verifies your request between chains. It takes up to 10 minutes to reach consensus and start a transaction on-chain.
* **Ethereum block times.** Ethereum blocks complete every 12 seconds. For large balances, it is common to wait for up to 32 blocks before proceeding with a transaction.
