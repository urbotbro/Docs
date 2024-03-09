# 📈 Buy Token

### **FAQ**

<details>

<summary>How can I change my gas settings?</summary>

In our Telegram bot, you have the option to select from our 3 preset gas strategies or specify a custom tip (optional). Please refer to the screenshot tutorial below to locate these options, and visit our Adaptive Gas page for further details.

</details>

### Interface

{% tabs %}
{% tab title="Telegram Bot (  Easy Mode )" %}
<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption><p>Buy Tokens - Easy Mode</p></figcaption></figure>

{% hint style="info" %}
In Easy Mode, transactions are sent privately by default.
{% endhint %}

* **Wallet Balances** - Displays the ETH and USDC balance on each of your 3 Bro Token wallets, for each of the integrated blockchains.&#x20;
* **Bro X** - Opens a small popup window to the Buy Tokens screen on Bro Bot X, our integrated trading terminal.&#x20;
* **Select Wallets** - Choose which wallets you want to buy with. You can enable multiple wallets to buy with many at once.&#x20;
* **Buy With** - Choose whether you are buying with ETH or USDC. All selected wallets should have sufficient balance.&#x20;
* **Buy Amount** - Choose from preset ETH amounts to buy with, or enter a custom amount.&#x20;
* **Custom Buy Amount** - Click the button once to enable it, then click the button again to enter your custom value.&#x20;
* **Enter Token Address** - Enter the address of the token you want to buy. After entering, your buy will immediately be triggered.

***

<figure><img src="../.gitbook/assets/image (13).png" alt=""><figcaption><p>Buy Token</p></figcaption></figure>

* **Buy Tokens** - Return to the buy menu.&#x20;
* **Chart & Scan** - Display the token's chart and scan for token heuristics (e.g., honeypot check).&#x20;
* **Support Ticket** - Open a support ticket related to this specific transaction.&#x20;
* **Main Menu** - Return to the main menu.


{% endtab %}

{% tab title="Telegram Bot ( Expert Mode )" %}
<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption></figcaption></figure>

* **Wallet Balances** - Shows the ETH and USDC balance on each of your 3 BRO Token wallets, for each of the integrated blockchains.
* **Swap Summary** - Quotes the expected amount you will receive from your trade based on our meta-aggregation engine.
* **Token Summary** - Useful information about the token you are buying. <mark style="color:yellow;">The honeypot detector is only indicative, and does not detect all honeypots</mark>.
* **BRO BOT** - Opens a small popup window to the Buy Tokens screen on BRO BOT, our integrated trading terminal.
* **PrivateTX** - Choose whether or not to [send the transaction privately](broken-reference).
* **Failguard** - [Simulate the transaction](broken-reference) to reduce the chance of failure.
* **Frontrun** - This setting is deprecated and will be removed. Use the **Gas Settings** instead.
* **Select Wallets** - Choose which wallets you want to buy with. You can enable multiple wallets to buy with many at once.
* **Buy With** - Click the BUY WITH ⇄ heading to toggle between buying with ETH or USDC.
* **Buy Amount** - Click the ⇄ ETH button to toggle between preset amounts, or click the ✎ ETH button to enter a custom amount. <mark style="color:yellow;">Click the button once to enable it, then click the button again to toggle or enter your custom value</mark>.
* **Slippage** - Auto-slippage is recommended, since it finds the lowest slippage possible for your swap to succeed. Otherwise, ⇄ toggle between the presets or ✎ enter a custom slippage %.
* **Receive Token** - Receive (i.e. buy) USDC, or ✎ enter a custom token address to buy.
* **SEND TX** - Submit the transaction to the network.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Buy Is Executed</p></figcaption></figure>

* **Buy Tokens** - Return to the buy menu.
* **Chart & Scan** - Show the token's chart, and scan for token heuristics (e.g. honeypot check)
* **Support Ticket** - Open a support ticket in relation to this specific transaction.
* **Main Menu** - Return to the main menu.
{% endtab %}

{% tab title="Bro Bot " %}
<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Buy panel</p></figcaption></figure>

* **PAY** - The amount of ETH you would like to swap with. Upon entering, the transaction will be simulated to estimate the amount you will receive.
* **RECEIVE** - The address of the token you are buying.
* **Buy Settings** - an expandable panel that reveals additional buy settings you can configure.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Buy Panel ( Setting Expanded ) </p></figcaption></figure>

* The simulation panel shows: **NAME -** The name & symbol of the ERC20 token **DEX** - The pool that the trade will be routed through. **AMOUNT** - The amount of token that you are expected to get. **SLIP** - The minimum amount of token you will get.
* The expanded Buy Settings reveals: **Use Private Transaction** - Choose whether or not to [send the transaction privately](https://learn.unibot.app/concepts/private-transactions). **Frontrun Other Traders** - Pay a higher priority gas fee for a chance to frontrun other transactions. **Slippage** - Specify your desired slippage with the slider, or use Autoslippage.

{% hint style="info" %}
The transaction will be automatically resimulated if you change the any of the Buy Settings.
{% endhint %}

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Honeypot detected</p></figcaption></figure>

* **Honeypot Detector** - When entering a token contract, Unibot will automatically check whether it is a honeypot (i.e. scam token). A red bug indicates that the token should be avoided! You can click the icon to view more details about the token.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Buy Transaction Pending</p></figcaption></figure>

* **Pending Notification** - A notification will be shown in the top-right of your screen when the transaction is broadcast.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Buy Transaction Success</p></figcaption></figure>

* **Success Notification** - A notification will be shown in the top-right of your screen when the transaction is included in the Ethereum network.
{% endtab %}
{% endtabs %}



***
