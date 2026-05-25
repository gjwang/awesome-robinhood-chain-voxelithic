# Awesome Robinhood Chain [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of projects, tools, and resources for Robinhood Chain (EVM, chain id 4663).

## Contents

- [DeFi](#defi)
- [DEXs](#dexs)
- [Infrastructure](#infrastructure)
- [Tokenized Equities](#tokenized-equities)
- [Developer Tools](#developer-tools)
- [Resources](#resources)

## DeFi

- **[production]** [Voxelithic](https://voxelithic.xyz) — liquidity aggregation layer, reads every venue into one book
- **[production]** [Pons](https://pons.exchange) — token launchpad (pump.fun equivalent for RH Chain)

## DEXs

- **[production]** [Uniswap v4](https://app.uniswap.org) — singleton concentrated liquidity (live on 4663)
- **[production]** [Uniswap v3](https://app.uniswap.org) — concentrated liquidity pools
- **[production]** [Ramses](https://ramses.exchange) — ve(3,3) DEX with concentrated liquidity
- **[production]** [Giga](https://giga.exchange) — concentrated liquidity
- **[production]** [Up Exchange](https://up.exchange) — constant product AMM

## Infrastructure

- [Blockscout](https://robinhoodchain.blockscout.com) — block explorer with contract verification
- [GeckoTerminal](https://www.geckoterminal.com/robinhood/pools) — DEX analytics and charts
- [DexScreener](https://dexscreener.com/robinhood) — pair explorer and trending

## Tokenized Equities

On-chain tokenized versions of major equities, trading during US market hours:

| Token | Underlying | Address |
|-------|-----------|---------|
| SPY | S&P 500 ETF | `0x8f93d4a6e9fa3fcc829ff1fbfc61e4c653b0bdc4` |
| NVDA | NVIDIA | `0xc38a2737ca75f56e1b76ef5694e6e0d4495d00e8` |
| TSLA | Tesla | `0xb3f3fd4b2340ea04597fec04bd2be2acb6e8b6ea` |
| AAPL | Apple | `0xb1e1b78cc1d3b1f03aaa20cb9b03c7ff5eaee0ad` |
| AMZN | Amazon | `0x16d9d5e3c0e5e15e01efbb0de7dc7001f3cc8f32` |
| COIN | Coinbase | `0x36f5b5b81e51db83ae8e3e8e6f438dead12e21bf` |

These are Stylus/WASM contracts — standard `ERC-20` interface, non-standard VM execution.

## Developer Tools

- [Foundry](https://book.getfoundry.sh) — smart contract development
  - v4 fork tests require `evm_version = "cancun"` for transient storage
  - RPC requires browser User-Agent header (Cloudflare protection)
- [USDG](https://robinhoodchain.blockscout.com/address/0x5fc5621f79e4a3f20f1c42e7bc2c32ae0fda149a) — native stablecoin (6 decimals)
- [WETH](https://robinhoodchain.blockscout.com/address/0x4200000000000000000000000000000000000006) — wrapped ETH

## Resources

- RPC endpoint: `https://rpc.mainnet.chain.robinhood.com`
- Chain ID: `4663`
- Block time: ~100ms (Arbitrum Orbit)
- Native currency: ETH
- State retention: ~10 minutes for `eth_call` overrides

## Contributing

PRs welcome. Add a maturity tag (`**[production]** / **[beta]** / **[experimental]**`) to new entries.

## License

CC0 1.0

// updated: iteration 7

// updated: iteration 8

// updated: iteration 9

// updated: iteration 11

// updated: iteration 12
