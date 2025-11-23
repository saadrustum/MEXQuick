# Product Specifications

![](<../../../.gitbook/assets/image (4)>)

## Parameter Category

illustrate

### Transaction cycle

The fixed period is 10 minutes. Each contract enters this period after the order is placed. Users can close the position early or wait for automatic settlement upon maturity.

### Leverage mechanism

Leverage is adjusted dynamically and increases naturally as the cycle approaches. Users lock in the current leverage ratio when placing an order.

### Admission Fee Formula

Entry Fee = Underlying Price ÷ Leverage. This amount represents the user's maximum potential loss.

### Backing Assets

Initially supports BTC/USDT and ETH/USDT, with plans to expand to other high-volatility and popular assets.

### Pricing mechanism

MEXQuick multi-source aggregated pricing system is updated every 500 ms and eliminates outliers that deviate from the median price by ±5%.

### Transaction fees

Temporarily waived, but may be charged later without further notice.

### Settlement Fee

Fixed at 10% of profits and cannot be waived.

### Closing method

* Manual closing: Lock in current profits or reduce losses at any time.
* Automatic settlement: The system settles the position at the end of the period.

### Trading Hours

24/7 non-stop trading.

***

### Parameter Description and Examples

* Dynamic Leverage Amplification:\
  At the beginning of a cycle, leverage is relatively low (e.g., hundreds of times). As the remaining time to maturity decreases, leverage automatically increases to thousands of times or more. Users can choose to enter early and trade cautiously, or pursue high-volume trading near maturity based on risk appetite.
* Entry Fee Calculation Example:

Example 1:

{% code title="Example 1" %}
```
BTC Price = 60,000 USDT
Leverage = 100x
Entry Fee = 60,000 ÷ 100 = 600 USDT
```
{% endcode %}

Example 2:

{% code title="Example 2" %}
```
BTC Price = 60,000 USDT
Leverage = 6,000x
Entry Fee = 60,000 ÷ 6,000 = 10 USDT
```
{% endcode %}

In Example 2, a 10 USDT entry fee provides exposure to 1 BTC's price movements, with a fixed maximum loss of 10 USDT.

* Transparent Fees:\
  Handling (transaction) fees are temporarily 0, reducing transaction costs. The settlement fee is fixed at 10% of profits and is deducted directly at settlement.

Last updated 6 days ago
