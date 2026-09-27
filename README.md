# mainnet-proof

On 27 Sep 2026 this repository went through the full [Preemption](https://preemption.dev) cycle on Robinhood Chain
mainnet, with real ETH:

1. A scout staked a 0.005 ETH bond on `gh/fletrixx/mainnet-proof` and received a soulbound Claim Ticket.
2. The owner proved the repository with the one-time code in [`.preemption`](.preemption), then reclaimed the name at
   cost. The Scout Deed was minted to the owner.
3. The scout settled the lost bond and withdrew 90 % of it.
4. The owner sold the deed on the Preemption marketplace for 0.004 ETH and withdrew the proceeds, less the 1 % fee.

The scout, the owner and the buyer are Preemption team wallets. This was a test of the whole cycle, not user activity.

| Step | Amount | Time (UTC) | Transaction |
|---|---|---|---|
| Stake, 48 h window opens | 0.005 ETH | 19:59:08 | [0x91f06bdb…](https://robinhoodchain.blockscout.com/tx/0x91f06bdb880c0926d964a7262c20e5278735187790a276db2c79c712ba981dcb) |
| Claim Ticket minted | | 19:59:17 | [0xce0d0d11…](https://robinhoodchain.blockscout.com/tx/0xce0d0d11cb5d4265f50ba53ca6d5df63fcdc25a26ec003307039efd576edd1c6) |
| Owner verified through `.preemption` | | 20:01:35 | [0x077f253e…](https://robinhoodchain.blockscout.com/tx/0x077f253eea5c81f437df94a884a25f09a20c9da9e8c2c8dffed74ef5b68855ee) |
| Reclaimed at cost, deed minted | 0.005 ETH | 20:01:43 | [0xda09874e…](https://robinhoodchain.blockscout.com/tx/0xda09874e0ca922820c6dffe93182baad909ec077177257885353871dcfe5ba2f) |
| Scout settles the lost stake | | 20:02:55 | [0x773ad95d…](https://robinhoodchain.blockscout.com/tx/0x773ad95d0e732c9e8b31296569c73d1dc863bfc2053607dd0f2f85d157bb34ea) |
| Scout withdraws 90 % | 0.0045 ETH | 20:03:03 | [0x0d4031ee…](https://robinhoodchain.blockscout.com/tx/0x0d4031ee58d2d13d6bed219d05a96694e8b91660edc56b668cdf6c568586f782) |
| Owner approves the market | | 20:04:31 | [0x1cf02f36…](https://robinhoodchain.blockscout.com/tx/0x1cf02f362aea7afc3799d19863e6e82e48859685b6f9033f5ce1b28f8aa87aef) |
| Deed listed | 0.004 ETH | 20:04:35 | [0xe64608e8…](https://robinhoodchain.blockscout.com/tx/0xe64608e8f8dcf63bfaf9ccb8cd408de72c5572a7ab61efa901faf5c3245b04bc) |
| Deed sold | 0.004 ETH | 20:05:39 | [0xd390275d…](https://robinhoodchain.blockscout.com/tx/0xd390275d69f22fd547e77a6c37b1b13a41b035fcb31326a26799f94dc250d241) |
| Seller withdraws | 0.00396 ETH | 20:06:36 | [0x0905daf5…](https://robinhoodchain.blockscout.com/tx/0x0905daf5a9bc9cfc5371e6833918825c0f325983d0e97b84caded98f48b63ce4) |
