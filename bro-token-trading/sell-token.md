# 📉 Sell Token

### FAQ

<details>

<summary>Why isn't my token in the list of available tokens to sell?</summary>

In order for a token to appear in the list of sellable tokens, its balance must be worth at least 0.01 ETH. On the ETH network, selling tokens valued at less than 0.01 ETH will rarely justify the associated gas costs.

</details>

<details>

<summary>How can I change my gas settings?</summary>

In our Telegram bot, you have the option to select from our 3 preset gas strategies and specify a custom additional tip amount. Please refer to our Adaptive Gas tutorial for more information.

</details>

{% tabs %}
{% tab title="Telegram Bot" %}
<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption><p>Sell Panel</p></figcaption></figure>

{% hint style="info" %}
You can utilize this panel to conveniently monitor your portfolio performance. The value and price change percentage are automatically refreshed.
{% endhint %}

* **Hide Owned Honeypot Tokens** - Click the eye icon to toggle whether your owned honeypot tokens are hidden from the list.
* **Sell** - Opens a popup where you can configure and execute a sell for that token on the given wallet. Note that this button does not immediately sell your tokens when clicked.

***

<figure><img src="../.gitbook/assets/image (15).png" alt=""><figcaption><p>Sell panel (value and % change toggled)</p></figcaption></figure>

* **Value** - The "Value" column header can be clicked to toggle between ETH and USD denominations.
* **% Change** - Clicking the % change column header toggles between different timeframes.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Sell token popup</p></figcaption></figure>

Sell Settings - An expandable panel that reveals additional settings for selling. The expanded Sell Settings include:

* **Use Private Transaction:** Choose whether or not to send the transaction privately.
* **Frontrun Other Traders:** Opt to pay a higher priority gas fee for a chance to frontrun other transactions.
* **Slippage:** Specify your desired slippage using the slider, or utilize Autoslippage.
* **Amount to Sell:** Use the slider to specify the percentage of tokens to sell. The Amount Out simulation panel displays:
* **ETH Value:** The expected amount of ETH you will receive.
* **DEX:** The pool through which the trade will be routed.
* **USD Value:** The equivalent USD value of the ETH received.
* **AMOUNT:** The quantity of tokens you will sell.

{% hint style="info" %}
The Amount Out will be automatically re-simulated if you change any of the Sell Settings.
{% endhint %}

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Sell transaction pending</p></figcaption></figure>

* **Pending Notification** - A notification will appear in the top-right corner of your screen once the transaction is broadcasted.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Sell transaction success</p></figcaption></figure>

* **Success Notification** - A notification will appear in the top-right corner of your screen once the transaction is successfully included in the Ethereum network.
{% endtab %}

{% tab title="Bro Bot" %}
<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Sell panel</p></figcaption></figure>

{% hint style="info" %}
You can use this panel to conveniently track your portfolio performance. The value and price change % are auto-refreshed.
{% endhint %}

* **Hide Owned Honeypot Tokens** - Click the eye icon to toggle whether your owned honeypot tokens are hidden from the list.
* **Sell** - Opens a popup where you can configure and execute a sell for that token on the given wallet. This button does not immediately sell your tokens when clicked.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Sell panel (value and % change toggled)</p></figcaption></figure>

* **Value** - The "Value" column header can be clicked to toggle between ETH and USD denominations.
* **% Change** - The % change column header can be clicked to toggle between timeframes.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Sell token popup</p></figcaption></figure>

* **Sell Settings** - an expandable panel that reveals additional sell settings you can configure.
* The expanded Sell Settings reveals: **Use Private Transaction** - Choose whether or not to [send the transaction privately](https://learn.unibot.app/concepts/private-transactions). **Frontrun Other Traders** - Pay a higher priority gas fee for a chance to frontrun other transactions. **Slippage** - Specify your desired slippage with the slider, or use Autoslippage.
* **Amount to Sell** - Using the slider, specify the % of tokens to sell
* The **Amount Out** simulation panel shows: **ETH Value -** The amount of ETH you are expected to get. **DEX** - The pool that the trade will be routed through. **USD Value** - The amount of USD equivalent to the **ETH Value**. **AMOUNT** - The amount of token that you will sell.

{% hint style="info" %}
The Amount Out will be automatically resimulated if you change the any of the Sell Settings.
{% endhint %}

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Sell transaction pending</p></figcaption></figure>

* **Pending Notification** - A notification will be shown in the top-right of your screen when the transaction is broadcast.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Sell transaction success</p></figcaption></figure>

* **Success Notification** - A notification will be shown in the top-right of your screen when the transaction is included in the Ethereum network.
{% endtab %}
{% endtabs %}
