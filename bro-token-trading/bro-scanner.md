# 📡 BRO Scanner

### Token Deployment Scanner

{% hint style="info" %}
The token deployment scanner shows newly created tokens in real-time.
{% endhint %}

{% tabs %}
{% tab title="Telegram Bot" %}
{% hint style="info" %}
To access the token deployment scanner in the Telegram Bot, [click here](https://t.me/unibotscanner).
{% endhint %}

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Token quick-buy screen</p></figcaption></figure>

* **Token** - Clicking the token name opens a link to the GeckoTerminal graph for that token. New tokens will not have a graph until liquidity has been added by the **Deployer**.
* **CA** - Opens an Etherscan link to the token page.
* **Owner** - Opens an Etherscan link to the wallet that created the token.
* **Launch Method** - The detected function that will likely be used to start trade.
* **Launch Method ID** - The function signature to use in the [Method Sniper](broken-reference) **Launch Func**.
* **Tax** - The detected buy tax for the token.
* **Skip Blocks** - The number of blocks to wait before sniping in the [Method Sniper](broken-reference).
* **Max Buy** - The detected anti-whale max buy amount for use in the [Method Sniper](broken-reference).
* **Status** - Flags indicating whether or not the following is true:\
  Token is deployed to ETH network; token is verified on Etherscan; liquidity is added and locked.
* **Import to Method Sniper** - Click this button to auto-populate the settings for this token in the [Method Sniper](broken-reference).

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Honeypot check</p></figcaption></figure>

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Tokenomics</p></figcaption></figure>
{% endtab %}

{% tab title="Bro Bot " %}
<figure><img src="../.gitbook/assets/fff.png" alt=""><figcaption><p>Token deployment scanner</p></figcaption></figure>

* **Fingerprint** - Click the Fingerprint icon to open the [Token Scan](broken-reference) popup, which provides a **Honeypot** detector and **Tokenomics** analyser. The popup includes additional **Deploy Data** when accessed via the scanner (shown below).&#x20;
* **Token** - Clicking the token name opens the [graph of that token](broken-reference). New tokens will not have a graph until liquidity has been added by the **Deployer**.
* **Deployer** - Opens an Etherscan link to the wallet that created the token.
* **Balance** - The amount of ETH remaining in the **Deployer**'s wallet. Their balance could be indicative of the amount of liquidity they will add for trading.

***

<figure><img src="../.gitbook/assets/fff.png" alt=""><figcaption><p>Deploy data (click fingerprint icon)</p></figcaption></figure>

If the token contract is verified on Etherscan, **Deploy Data** shows:\
**Contract Readables** - Public values in the token contract which are useful for the [Method Sniper](broken-reference).\
**Enable Trading Function** - The function that will likely be used to start trading. The function signature, e.g. `0xc9567bf9` in the example above, would be used as the **Launch Func** in the [Method Sniper](broken-reference).
{% endtab %}
{% endtabs %}

### Trader Gains Scanner

{% hint style="info" %}
The gains scanner shows transactions where traders have taken profit by selling a token. Use this scanner to track who is selling a token, and how much remaining sell pressure there may be.
{% endhint %}

{% tabs %}
{% tab title="Bro Bot " %}
<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Trader gains scanner</p></figcaption></figure>

* **Fingerprint** - Click the Fingerprint icon to open the [Token Scan](broken-reference) popup, which provides a **Honeypot** detector and **Tokenomics** analyser.
* **Token** - Clicking the token name opens the [graph of that token](broken-reference).
* **Wallet** - Opens an Etherscan link to the wallet that sold the token.
* **Gains** - The total amount of ETH earned by the **Wallet** from selling this token.
* **Remain** - The additional amount of ETH the **Wallet** would make from selling all their remaining tokens.
{% endtab %}
{% endtabs %}

### Sniped Launches Scanner

{% hint style="info" %}
The sniped launches scanner tracks tokens which have just started trading and were sniped by traders. Use this scanner to identify highly contested snipes.
{% endhint %}

{% tabs %}
{% tab title="Telegram Bot" %}
{% hint style="info" %}
To access the token deployment scanner in the Telegram Bot, [click here](https://t.me/unibotscanner).
{% endhint %}

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Sniped launch</p></figcaption></figure>

* **Token** - Clicking the token name opens a link to the GeckoTerminal graph for that token.
* **CA** - Opens an Etherscan link to the token page.
* **LP** - The amount of ETH in the liquidity pool.
* **Owner** - Details of the token deployer:\
  Etherscan link to the token deployer; ETH balance of the deployer; number of transactions sent by the deployer.
* **Snipes** - Table of snipe transactions:\
  Etherscan link to the sniper; ETH spent on snipe; balance of the sniper; number of transactions sent by the sniper.
* **Token Fast Buy** - Click this button to open the quick-buy menu for this token.
{% endtab %}

{% tab title="Bro Bot" %}
<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Sniped launches scanner</p></figcaption></figure>

* **Fingerprint** - Click the Fingerprint icon to open the [Token Scan](broken-reference) popup, which provides a **Honeypot** detector and **Tokenomics** analyser. The popup includes additional **Snipes Data** when accessed via the scanner (shown below).&#x20;
* **Token** - Clicking the token name opens the [graph of that token](broken-reference).
* **Address** - Opens an Etherscan link to the token that was sniped.
* **Crosshair** - The number of snipe transactions targeting this token at launch.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Sniped data (click fingerprint icon)</p></figcaption></figure>

* **Top section** - Details of the trade start:\
  Block of trade launch; address of token deployer; amount of ETH liquidity added; number of snipe transactions.
* **Bottom section** - Table of snipe transactions: \
  Sniper address; ETH used to buy; number of transactions the sniper address has.
{% endtab %}
{% endtabs %}

