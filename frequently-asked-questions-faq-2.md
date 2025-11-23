# Frequently Asked Questions (FAQ)

![FAQ image](<.gitbook/assets/image (45)>)

<details>

<summary>Q1: What is an event contract?</summary>

A1: An event contract is a short-term price prediction product based on a binary options mechanism. Users can predict the price direction and receive a fixed return if their prediction is correct.

</details>

<details>

<summary>Q2: How is the return calculated?</summary>

A2:

* If the prediction is correct:
  * Settlement Amount = Investment Amount + Investment Amount × 90%
* If the prediction is incorrect:
  * Settlement Amount = 0

The handling fee is fixed at 10%, and payment with MQT is 50% off.

</details>

<details>

<summary>Q3: What is the maximum loss?</summary>

A3: The maximum loss is equal to the investment amount. There is no margin call or liquidation.

</details>

<details>

<summary>Q4: Can I close my position early?</summary>

A4: No. Event contracts are fixed-period products, and results are automatically settled at maturity.

</details>

<details>

<summary>Q5: Where does the price data come from?</summary>

A5: MEXQuick uses multi-source aggregated prices from multiple exchanges, updated every 500ms, and removes outliers to ensure fairness.

</details>

<details>

<summary>Q6: Will the platform bet against me?</summary>

A6: No. Profits and losses are settled through user-to-user matching or a neutral pool. The platform does not profit from user losses.

</details>

<details>

<summary>Q7: Are there any investment restrictions?</summary>

A7: Yes, the platform sets a single user holding limit and a platform total holding limit.

</details>

<details>

<summary>Q8: How is the handling fee charged?</summary>

A8: A fixed 10%. Users can choose to use MQT payment to enjoy a 50% discount.

</details>

Last updated 5 days ago
