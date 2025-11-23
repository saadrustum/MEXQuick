# Overview of the Dual Currency Model

![](<.gitbook/assets/image (66)>)

MEXQuick utilizes a dual-currency model: MUSD (stable anchor) + MQT (value capture).

* MUSD
  * An internal platform stablecoin pegged 1:1 to USDT.
  * Used solely for market-making pool staking and settlement purposes.
  * Not used for trade matching.
* MQT
  * The platform's ecosystem token.
  * Responsible for revenue distribution, fee deductions, governance, and ecosystem rights.
  * Achieves deflation and value capture through established mechanisms.

This model separates external compatibility at the trading layer from internal stability at the market-making layer:

* USDT is used for transaction settlement.
* MUSD is used for market-making participation.
* MQT is used for both revenue and equity.
