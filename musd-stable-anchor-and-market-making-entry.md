# MUSD: Stable Anchor and Market Making Entry

![](<.gitbook/assets/image (50)>)

{% stepper %}
{% step %}
### Positioning and boundaries

* Stable Anchor: Pegged 1:1 to USDT, serving as a stable unit of account for the market-making layer.
* Limited Usage: Currently used only for market-making pool staking and revenue settlement, not as a trading medium.
* Fund Segregation: Trading funds (USDT) and market-making funds (MUSD) are managed separately to mitigate systemic risks associated with intersecting funding paths.
{% endstep %}

{% step %}
### Participation and Redemption

* Before participating in market making, users must convert USDT into MUSD in the Smart Market (MUSD ↔ USDT, two-way, low fees; MUSD → USDT, fixed fee of 1 USDT).
* Staking, reinvestment, and redemption are all denominated in MUSD; redemption can be converted back to USDT at any time.
{% endstep %}

{% step %}
### Why not use USDT directly for market making?

* Accounting and risk control stratification: Market making books are uniformly denominated in MUSD, facilitating independent accounting of net risk, net income, and reserves.
* Stable liquidity: The disturbance of short-term fluctuations on the trading side to the market making side is separated, avoiding the tail risk brought by the same pool of matching and hedging funds.
* Settlement consistency: At the time of daily settlement, market making income is uniformly transferred to MQT using MUSD as the voucher, improving process stability and transparency.
{% endstep %}

{% step %}
### Forward-looking planning (without changing the positioning of “market making certificates”)

* Cross-chain compatibility: supports multi-chain native issuance or asset mapping to improve capital accessibility.
* Ecological application: gradually expands to internal scenarios such as NFT, guild incentives, RWA settlement, etc.
* Compliance exploration: connects with the compliance framework in some jurisdictions and carries out payment/settlement functions (gradually activated depending on the implementation of supervision).
{% endstep %}
{% endstepper %}

Last updated 4 days ago
