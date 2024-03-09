# ⛽ Adaptive Gas



{% hint style="info" %}
Bro Token offers 3 gas strategies that dynamically adjust to other transactions on the network, guaranteeing that Bro Token user transactions are successful without paying excessive gas fees.
{% endhint %}

{% hint style="info" %}
The **Smart strategy** is the recommended option for most users and is selected by default.
{% endhint %}

<figure><img src="../.gitbook/assets/ffffff.png" alt=""><figcaption><p>Adaptive Gas Tutorial</p></figcaption></figure>

### FAQ

<details>

<summary>What do the gas strategies mean?</summary>

Bro Token's gas analyzer monitors the network to understand the distribution of gas prices and determine optimal gas price parameters. Users can select from three strategies:

1. Eco Mode: Maximizes gas savings, but may occasionally result in your transaction taking an additional block to be confirmed.
2. Smart Mode: Strikes a balance between Eco and Aggressive mode. Outperforms most competitors' gas prices without overpaying, ensuring your transaction is confirmed swiftly.
3. Aggressive Mode: Utilizes higher gas to frontrun and surpass the competition.

</details>

<details>

<summary>What is a Tip?</summary>

With the introduction of EIP-1559, the Ethereum network implemented the concept of a "**priority fee**" or tipping. Essentially, providing a tip incentivizes Ethereum validators to prioritize the inclusion of your transaction.

</details>

***

### Interface

{% hint style="info" %}
You can locate the **Gas Settings** within the Buy or Sell menus in the Telegram bot.
{% endhint %}

<figure><img src="../.gitbook/assets/ffffff.png" alt=""><figcaption><p>Gas Setting</p></figcaption></figure>

* Selecting any option between Eco, Smart, or Aggr will update your gas strategy to the chosen option.
* &#x20;Choosing Tip will prompt you to enter a custom tip amount, which will be added on top of your selected gas strategy.&#x20;
* Selecting Info displays the Info Summary below.

***

<figure><img src="../.gitbook/assets/ffffff.png" alt=""><figcaption><p>Gas Info Summary</p></figcaption></figure>

The Info Summary includes the following details:

* Descriptions of each gas strategy.
* The tip utilized by each gas strategy, continually updated by Bro Token's network gas analyzer.
* A summary of the tips employed by competitors, derived from cluster analysis. This information contributes to our gas strategies.
