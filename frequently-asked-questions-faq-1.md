# Frequently Asked Questions (FAQ)

![](<.gitbook/assets/image (45)>)

<details>

<summary>What is a Ticket Contract?</summary>

A Ticket Contract is a short-term, highly leveraged trading product that allows users to speculate on the price movements of an underlying asset (such as BTC or ETH) within a fixed 10-minute period. Users pay a one-time fixed entry fee and receive returns based on the price difference at settlement, with no risk of margin calls.

</details>

<details>

<summary>How does a Ticket Contract differ from traditional spot trading?</summary>

Spot trading: Users buy or sell actual tokens at the current market price, requiring full capital investment.

Ticket Contracts: Users pay a smaller entry fee and receive a stake in the corresponding price fluctuations of a larger position, earning highly leveraged returns without holding the underlying asset.

</details>

<details>

<summary>How is my profit or loss calculated?</summary>

Profit or loss = (Settlement Price - Entry Price) × Direction × Position Size.

</details>

<details>

<summary>Are there any risks?</summary>

Yes, but the risk is manageable and limited to the entry fee. There is no margin call.

</details>

<details>

<summary>What is the maximum leverage?</summary>

The leverage of a Ticket Contract is dynamically adjusted. As the expiration date approaches, the leverage multiplier naturally increases, reaching thousands of times or even higher.

</details>

<details>

<summary>How are ticket contracts settled?</summary>

* Manual Settlement: Manually close a position at any time before expiration to lock in current profits and losses.
* Automatic Settlement: Wait for the period to expire, and the system will automatically settle profits and losses at the expiration price, deducting a fixed 10% profit settlement fee.

</details>

<details>

<summary>What happens if the market moves unfavorably?</summary>

If the price moves in the opposite direction of your prediction, the maximum loss is the entry fee, with no additional losses.

</details>

<details>

<summary>What assets are supported by ticket contracts?</summary>

Currently, we support mainstream trading pairs such as BTC/USDT and ETH/USDT, and will expand to include high-volatility and hot assets in the future.

</details>

<details>

<summary>Can ticket contracts be used for hedging?</summary>

Yes. For example, you can short a ticket contract while holding BTC to hedge against downside risk.

</details>

<details>

<summary>Can I close a position before expiration?</summary>

Yes. You can manually close a position at any time before the contract expires, and the system will immediately settle and pay out any remaining profits (minus a 10% settlement fee).

</details>

<details>

<summary>Is there a limit on the number of positions you can hold in ticket contracts?</summary>

Yes. The platform sets both individual and platform-wide position limits to prevent concentration risk.

</details>

<details>

<summary>Is there slippage with ticket contracts?</summary>

No. Ticket Contracts use a multi-source aggregated index price that doesn't rely on order book depth, thus avoiding slippage caused by insufficient liquidity.

</details>

<details>

<summary>What happens if the platform encounters extreme market conditions?</summary>

Risk protection mechanisms may be triggered, including liquidity pool hedging, suspension of new position openings, and automatic position reduction (ADL) to ensure user settlement security.

</details>

[Previous Risk Management](mexquick/innovative-contract-products/ticket-contract/risk-management.md) [Next Event Contract](mexquick/innovative-contract-products/event-contract/)

Last updated 6 days ago
