# 🎯 Token Sniper



{% hint style="info" %}
Token Sniper is currently exclusive to the Telegram Bot. Integration into Bro Token is planned for a later release.
{% endhint %}

### FAQ

{% hint style="info" %}
If you have First or Fail enabled and you fail to win the token snipe, you won't receive an alert. For more details, refer to the FAQ below.
{% endhint %}

<details>

<summary>How do I find tokens to snipe?</summary>

For new users, we recommend utilizing the Auto Sniper feature. This function automatically joins snipes for tokens that are popular among other Bro Bot snipers.

1. &#x20;Alternatively, we highly suggest subscribing to our Token Scanner Channel. This channel sends alerts for any new token deployments. If an alert includes the Method Sniper button, you can click it to conveniently add the token to your snipe list.&#x20;
2. Frequent updates on ongoing snipes from other Bro Bot snipers are also shared on the channel. Simply click Opt-in to effortlessly include the token in your snipe list.

</details>

<details>

<summary>Why didn't my Token Sniper work with First or Fail enabled?</summary>

Several factors could explain why your snipe didn't succeed with First or Fail enabled:

1. For First or Fail to trigger a successful snipe, the combined tip of all Bro Bot snipers must exceed the tip of non-Bro Bot sniper bundles.
2. The token owner might have initiated trading using a private transaction.
3. In rare cases (less than 10%), an Ethereum block may not qualify as an MEV (Miner Extractable Value) block, resulting in no successful sniper bundles.

</details>

<details>

<summary>What happens if Token Sniper and Auto Sniper trigger on the same token?</summary>

In the event of both Token Sniper and Auto Sniper being active, Token Sniper will take precedence, and only one snipe will occur.

</details>

### How to access

1. `/menu` in the [Telegram bot](https://t.me/RevoluzionAI\_Bot).
2. Click `Snipers (ERC-20)`.
3. Choose between `Token Sniper` or `Auto Sniper`.

### 💰Setting your tip/bribe

* The tip, also referred to as a bribe, is essential for achieving success in token snipes.&#x20;
* When the total tip contributed by all Bro Bot users sniping a token surpasses that of our competitors, the Bro Bot users secure the token snipe.&#x20;
* Thus, each Bro Bot sniper plays a crucial role in the collective success of our sniping efforts.

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Custom tip/bribe</p></figcaption></figure>

1. Click **Tip.**
2. You will be prompted to enter your custom amount in GWEI or ETH terms. E.g. `0.01 eth` or `60 gwei`.
3. If you enter in ETH terms, it will be automatically converted into the equivalent GWEI. Either way, you're done!

{% hint style="info" %}
The most important setting is the **Tip**! Usually snipers will tip at least 60 GWEI (i.e. 0.01 ETH) and even up to 600 GWEI (i.e. 0.1 ETH) or more for highly competitive snipes. Just remember that **every enabled wallet** pays the tip.
{% endhint %}

### Interface

{% tabs %}
{% tab title="Main Screen" %}
<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

* **Running Snipers** - Summary view of the sniper status for each of your wallets. You can click the wallet name to quickly toggle on 🟢 and off 🔴 status.
* Choose which type of sniper you want to access.\
  **Token Sniper** - Target specific token addresses for sniping.\
  **Auto Sniper** - Automatically snipe tokens which are popular with other Bro Bot snipers.\
  **Mirror Sniper** - Our [Copy Trade](broken-reference) feature which will be upgraded in the coming weeks.
{% endtab %}

{% tab title="Token Sniper" %}
<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The Token Sniper settings are applied to **all** the tokens you have added to your snipe list. You can update your settings at any time.
{% endhint %}

{% hint style="info" %}
The most important setting is the **Tip**! Usually snipers will tip at least 60 GWEI (i.e. 0.01 ETH) and even up to 600 GWEI (i.e. 0.1 ETH) or more for highly competitive snipes. Just remember that **every enabled wallet** pays the tip.
{% endhint %}

* **Tip** - Specify the tip you are willing to pay for the snipe. You will only pay this tip if the snipe is successfully bundled, but be mindful that every enabled wallet pays the tip. <mark style="color:yellow;">This is an important setting for snipers!</mark> You can specify it in many ways, here are some examples:\
  \- `100 GWEI`\
  \- `0.02 Eth`
* **Sniper On/Off** - Choose which wallets you want to snipe with. All enabled wallets will snipe together. You can adjust this even while you have an active list of tokens to snipe.
* **Max Spend Amt** - The maximum amount of ETH you will buy with, for each of your enabled wallets. Your ETH spent will always be whichever value is smaller: the **Max Spend Amt** or the ETH required to buy the **Max Wallet Size** of the token you are sniping (if relevant). <mark style="color:yellow;">This does not include your gas costs, which can be high for token sniping.</mark>&#x20;
* **Autosell** - Optionally choose to sell your tokens automatically when your specified rule is triggered. You can specify it in many ways, here are some examples:\
  \- `0.1 eth` (i.e. if the value of your position is worth that much ETH)\
  \- `500%`\
  \- `10 blocks`
* **First or Fail** - If enabled, you will only be included in the snipe if Bro Bot is **the first** (i.e. the winning) sniper for a given token. Having this enabled is a trade-off: there's less risk of you buying at a bad price, but you are less likely to succeed at buying.
* **Anti-Rug** - If the token owner tries to remove the liquidity from the token trading pair, automatically try to sell your tokens before them. <mark style="color:yellow;">It is not possible to protect you if the token owner uses a private transaction.</mark>&#x20;
* **Add Token To Snipe** - The address of the token you intend to snipe.
{% endtab %}

{% tab title="Auto Sniper" %}
<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Auto Sniper always uses **First or Fail**. This means that you will only be included in the snipe if Bro Bot is **the first** (i.e. the winning) sniper for a given token.
{% endhint %}

{% hint style="info" %}
The most important setting is the **Tip**! Usually snipers will tip at least 60 GWEI (i.e. 0.01 ETH) and even up to 600 GWEI (i.e. 0.1 ETH) or more for highly competitive snipes. Just remember that **every enabled wallet** pays the tip.
{% endhint %}

* **Tip** - Specify the tip you are willing to pay for the snipe. You will only pay this tip if the snipe is successfully bundled, but be mindful that every enabled wallet pays the tip. <mark style="color:yellow;">This is an important setting for snipers!</mark> You can specify it in many ways, here are some examples:\
  \- `100 gwei`\
  \- `0.02 eth`
* **Sniper On/Off** - Choose which wallets you want to snipe with. All enabled wallets will snipe together. You can adjust this even while you have an active list of tokens to snipe.
* **Max Spend Amt** - The maximum amount of ETH you will buy with, for each of your enabled wallets. Your ETH spent will always be whichever value is smaller: the **Max Spend Amt** or the ETH required to buy the **Max Wallet Size** of the token you are sniping (if relevant). <mark style="color:yellow;">This does not include your gas costs, which can be high for token sniping.</mark>&#x20;
* **Autosell** - Optionally choose to sell your tokens automatically when your specified rule is triggered. You can specify it in many ways, here are some examples:\
  \- `0.1 eth` (i.e. if the value of your position is worth that much ETH)\
  \- `500%`\
  \- `10 blocks`
* **Anti-Rug** - If the token owner tries to remove the liquidity from the token trading pair, automatically try to sell your tokens before them. <mark style="color:yellow;">It is not possible to protect you if the token owner uses a private transaction.</mark>&#x20;
* **Trigger** - The minimum number of Bro Bot snipers that must be specifically targeting a token in order for you to automatically participate in the snipe.
{% endtab %}
{% endtabs %}

