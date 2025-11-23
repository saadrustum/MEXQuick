# Profit & Settlement

![Profit & Settlement](<.gitbook/assets/image (34)>)

Rhythm contracts utilize a fixed return rate and a unified settlement mechanism, allowing users to clearly identify potential returns and maximum risks before trading.

{% stepper %}
{% step %}
### Return calculation formula

* Correct prediction:
  * Settlement Amount = Investment Amount + Investment Amount × 90%
* Incorrect prediction:
  * Settlement Amount = 0
* Handling fee:
  * Fixed 10%
  * 50% discount on the handling fee when paying with MQT
{% endstep %}

{% step %}
### Settlement rules

* The opening price is locked after the green countdown period ends.
* The settlement price is determined after the red countdown period ends.
* Correct prediction: return of principal + fixed 90% return.
* Incorrect prediction: loss of investment amount.
{% endstep %}

{% step %}
### Return calculation example

* Investment Amount: 100 USDT
* Return Rate: 90%
* Position: Bullish
* Opening Price: 60,000 USDT
* If Settlement Price = 60,050 USDT → Settlement: 190 USDT\
  (100 USDT principal + 90 USDT return)
* If Settlement Price = 59,950 USDT → Settlement: 0 USDT\
  (incorrect prediction → loss of investment)
{% endstep %}
{% endstepper %}
