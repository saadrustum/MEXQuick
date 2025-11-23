# Profit & Settlement

![](<.gitbook/assets/image (34)>)

Ticket contracts use a fixed-period settlement and flexible liquidation model, allowing traders to lock in immediate profits or hold positions to maximize returns.

{% stepper %}
{% step %}
### Profit calculation formula

**Profit = (settlement price − entry price) × direction × position quantity**

* Settlement Price: The index price at contract expiration (or manual position closing).
* Entry Price: The index price at the time the user places an order.
* Direction: 1 for a call position, -1 for a put position.
* Position Size: Determined by the entry fee and leverage, i.e., the size of the underlying asset at entry.
{% endstep %}

{% step %}
### Settlement methods

* Automatic Settlement at Maturity\
  At the end of a fixed 10-minute period, the system automatically calculates the user's profit or loss based on the settlement price, deducting a fixed 10% profit settlement fee.
* Early Manual Settlement\
  Users can manually close their positions at any time during the period, with immediate settlement of their profit or loss. A 10% settlement fee will be charged.
{% endstep %}

{% step %}
### Profit calculation examples

Example 1 — Bullish Profit

* Entry Price: 60,000 USDT
* Leverage: 200x → Entry Fee = 300 USDT (Position Size: 1 BTC)
* Expiration Settlement Price: 60,150 USDT

Calculation:

{% code title="Example 1" %}
```
Profit = (60,150 - 60,000) × 1 × 1 = 150 USDT
Settlement Fee = 10% of 150 = 15 USDT
Final Profit = 150 - 15 = 135 USDT
```
{% endcode %}

Example 2 — Bearish Profit

* Entry Price: 60,000 USDT
* Leverage: 6,000x → Entry Fee = 10 USDT (Position Size: 1 BTC)
* Expiration Settlement Price: 59,990 USDT

Calculation:

{% code title="Example 2" %}
```
Profit = (59,990 - 60,000) × (-1) × 1 = 10 USDT
Settlement Fee = 10% of 10 = 1 USDT
Final Profit = 10 - 1 = 9 USDT
```
{% endcode %}
{% endstep %}
{% endstepper %}

Last updated 6 days ago.
