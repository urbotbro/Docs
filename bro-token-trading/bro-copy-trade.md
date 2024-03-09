# 🪞 BRO Copy Trade

###

{% hint style="info" %}
Copy Trade is only available through the Telegram Bot. It will be added to Bro Bot X at a later time.
{% endhint %}

### FAQ

<details>

<summary>Why didn't my Copy Trade trigger?</summary>

Copy Trade currently only supports copying Uniswap router functions (V2, V3, multicall, execute, etc.). Swaps made through custom functions or other routers such as 1inch are not supported for copy trading. We will enhance Copy Trade functionality over time.

</details>

<details>

<summary>Does Copy Trade also copy sells?</summary>

Currently, Copy Trade only copies buy transactions. Support for copying sell transactions will be added at a later time.

</details>

***

### Interface

{% tabs %}
{% tab title="Telegram Bot " %}
<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption><p>Main screen (no token address entered)</p></figcaption></figure>

* **Sniper Status** - Choose which wallets you want to enable for Copy Trade. All enabled wallets will copy trades in parallel. You need to add at least one address as described below before enabling wallets.&#x20;
* **Buy Amoun**t - Set the maximum amount of ETH you will use for a single copy trade. Your targeted trader's ETH amount is copied until it exceeds your Buy Amount.
* **Add Addresses** - Enter one or more ETH addresses separated by commas. After adding, your enabled wallets will be ready to copy trades.&#x20;
* **Remove Addresses** - Enter one or more ETH addresses separated by commas. After removal, trades from these addresses will be ignored.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Main screen (token address entered)</p></figcaption></figure>

**Add Addresses** - Enter the addresses of traders you want to copy, separated by commas. You can add multiple addresses at once.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>After creating at least one limit order</p></figcaption></figure>

* **Your Mirror List:** Displays the addresses you've added for Copy Trade in a list.
* **Sniper Status:** Toggling Copy Trade on/off for a wallet is done by clicking on it.&#x20;
* **Sniper Settings:** This summary is shown because at least one wallet is enabled.&#x20;

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Delete order</p></figcaption></figure>

* **Copy Trade** - Navigate back to the copy trade menu.&#x20;
* **Main Menu** - Return to the main menu.
{% endtab %}
{% endtabs %}

