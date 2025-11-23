# Profit & Settlement

![](<.gitbook/assets/image (34)>)

Event contracts utilize a fixed return rate and automatic settlement mechanism, allowing users to clearly identify potential returns and maximum risks before trading.

#### Return Calculation Formula

(Direct link: https://giki-edu.gitbook.io/welcome-to-mexquick/mexquick/innovative-contract-products/event-contract/profit-and-settlement#return-calculation-formula)

Correct Prediction:

* Settlement Amount = Investment Amount + Investment Amount × 90%

Incorrect Prediction:

* Settlement Amount = 0

Handling Fee: Fixed 10%; 50% discount available for MQT deduction

{% stepper %}
{% step %}
### Settlement Rules

* Automatic settlement at the end of the period, determined by the system based on the entry price and the expiration price.
* Correct Prediction: Return of principal + fixed 90% return.
* Incorrect Prediction: Loss of investment amount.
{% endstep %}

{% step %}
### Return Calculation Example

* Investment Amount: 100 USDT
* Return Rate: 90%
* Direction: Bullish

Scenarios:

* Price at expiration is higher than the entry price → Settlement: 190 USDT (100 + 100 × 90%)
* Price at expiration is lower than the entry price → Settlement: 0 USDT
{% endstep %}
{% endstepper %}

Last updated 4 days ago
