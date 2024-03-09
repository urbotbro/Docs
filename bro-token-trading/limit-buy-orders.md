# 📥 Limit Buy Orders

### FAQ

<details>

<summary>Why didn't my limit order trigger?</summary>

A limit order might not have triggered due to various reasons:

* The limit order factors in the price impact of your potential swap. Even if the market price moved near the trigger, your order could move the price out of the trigger range.
* Swaps for that token may have been executed before yours in the block, influencing the token price and resulting in your order failing.

</details>

<details>

<summary>What is the maximum expiry time for a limit order?</summary>

There is no limit on the expiry time you can use.

</details>

<details>

<summary>How is the token's USD price computed?</summary>

Every block, limit orders undergo trigger checks by computing the USD price of the token:

* The reserves of the token trading pair and your token input amount are utilized to determine the equivalent ETH amount for your tokens.
* The USD price of ETH is calculated based on the USDC-WETH Uniswap pool.
* These two results are then used to compute the equivalent USD price of your tokens.

</details>

***

### Interface

{% tabs %}
{% tab title="Telegram Bot " %}
<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption><p>Main screen (no token address entered)</p></figcaption></figure>

* **Token** - The contract address of the token you intend to limit buy.&#x20;
* **Amt** - The amount of ETH you want to buy with.&#x20;
* **Expire** - The duration in hours before the order expires and is automatically canceled.&#x20;
* **Delete Order** - Each limit order you create is presented in a numbered list under Existing Orders. To delete a limit order, simply enter its list number.&#x20;
* **Select Wallets** - Choose which wallets you want to buy with in parallel.&#x20;
* **Add Order** - Choose from preset percentage price decreases or enter a custom percentage. After inputting, your limit order will be created but not triggered.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Main screen (token address entered)</p></figcaption></figure>

\
Limit Buy Summary - This summary appears when a token address is entered.

* Current token price and market capitalization.
* The current amount of tokens you would receive for your inputted amount.
* Example percentage price decreases and their equivalent market capitalization and token price.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>After creating at least one limit order</p></figcaption></figure>

**Existing Orders** - Each new limit order you create is added to this list, providing a summary of each order.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Delete order</p></figcaption></figure>

**Select Order To Delete**: Entering "2" in the Existing Orders example above would delete the limit order for 0.25 ETH.

***

<figure><img src="../.gitbook/assets/fff&#x26;text=Coming+Soon.png" alt=""><figcaption><p>Limit order is triggered</p></figcaption></figure>

* **Buy Limit** - Return to the buy limit menu.&#x20;
* **Support Ticket** - Open a support ticket related to this specific transaction.&#x20;
* **Main Menu** - Return to the main menu.
{% endtab %}

{% tab title="Bro Bot " %}
<figure><img src="../.gitbook/assets/fff.png" alt=""><figcaption><p>Limit buy panel</p></figcaption></figure>

* **PAY** - Specify the amount of ETH you would like to swap with.&#x20;
* **EXPIRATION** - Set the duration in hours before the order expires and is automatically canceled.&#x20;
* **RECEIVE** - Enter the address of the token for which you are creating a limit order. Upon entering, details of the token will be automatically presented, including its name, symbol, price, and market capitalization.&#x20;
* **TRIGGER PRICE (% CHANGE)** - Use the slider to specify the percentage price decrease that should occur for the limit order to trigger.&#x20;
* **Create Limit Buy Order** - After clicking, your limit order will be created but not triggered. Your Open Orders panel will immediately update and include your new limit order.

***

<figure><img src="../.gitbook/assets/fff.png" alt=""><figcaption><p>Open orders</p></figcaption></figure>

**Delete Order** - Click the trash icon next to the limit order you wish to delete. Deletion occurs immediately and without confirmation.
{% endtab %}
{% endtabs %}

