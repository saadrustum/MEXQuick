# Frequently Asked Questions (FAQ)

Good morning — I'm here to help you with the docs.

What is this page about? What should I read next? Can you give an example?

`Ctrl` `i`

AIBased on your context

Send

![FAQ image](<.gitbook/assets/image (45)>)

<details>

<summary>Q1: What is the difference between Rhythm Contracts and regular short-term contracts?</summary>

A1: Rhythm Contracts use a fixed-round trading mechanism, with all users opening and settling positions uniformly, eliminating unfair advantages caused by latency.

</details>

<details>

<summary>Q2: What is the maximum loss?</summary>

A2: The maximum loss is equal to the investment amount. There are no margin calls or liquidations.

</details>

<details>

<summary>Q3: How is price fairness guaranteed?</summary>

A3: We use multi-source aggregated prices, updated every 500ms, and exclude outliers that deviate from the median price by ±5%.

</details>

<details>

<summary>Q4: What are the green and red countdowns?</summary>

A4: The green countdown indicates the order window, where users can submit orders; the red countdown indicates the position holding period, awaiting centralized settlement.

</details>

<details>

<summary>Q5: Can I close my position early?</summary>

A5: No. Rhythm Contracts require the red countdown to expire, and the system will settle the position uniformly.

</details>

<details>

<summary>Q6: Will the platform bet against me?</summary>

A6: No. Profits and losses are settled through user-to-user matching or liquidity pools. The platform does not profit from user losses.

</details>

<details>

<summary>Q7: How is the transaction fee charged?</summary>

A7: A fixed 10%. Users can choose to pay with MQT to enjoy a 50% discount (i.e., 5%).

</details>

Last updated 5 days ago
