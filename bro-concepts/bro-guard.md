# 🚨 BRO Guard

<details>

<summary>What is Fail Guard?</summary>

With Fail Guard enabled, before your transaction is broadcasted to the network it is simulated to ensure that it would not result an execution error. The purpose of Fail Guard is to avoid wasting gas on sending transactions that are predicted to fail.&#x20;

This setting adds some latency to your trade, as the simulation must be completed before executing the trade.

</details>

<details>

<summary>Why did my transaction fail even with Fail Guard on?</summary>

Fail Guard is not guaranteed to prevent all types of transaction errors.&#x20;

For example. consider a swap transaction with 5% slippage that is completely valid and simulates successfully. If there are transactions before you in the block which move the price out of the 5% range, your transaction will fail.&#x20;

</details>
