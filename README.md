# THRYX Token Launches — Clanker V4 on Base

Four ancient-language tokens launched via [Clanker V4](https://clanker.world) on **Base mainnet**. 80% LP fee share to the THRYX treasury. Anti-sniper fee curve enabled by default (66.6% start fee → 4.17% over a 15s decay).

> Token names from ancient/dead languages — no AI-slop names. Each one is a thematic anchor for one corner of the THRYX onchain surface.

## Launches

| Name | Symbol | Address | Theme |
|---|---|---|---|
| Aletheia | ALETH | [`0x1896354e4729C689B27CbDFdE5F8192eD0115B07`](https://basescan.org/token/0x1896354e4729C689B27CbDFdE5F8192eD0115B07) | Greek — truth unconcealed. The cleanest signal in the noise. |
| Mnemosyne | MNEM | [`0x6358208342Be88A6D8bDC7c00D09fB43C49DdB07`](https://basescan.org/token/0x6358208342Be88A6D8bDC7c00D09fB43C49DdB07) | Greek — mother of the Muses, goddess of memory. The chain forgets nothing. |
| Huginn | HUGIN | [`0x75BB9e3eB32747D7A9eEEf8467f5f4C44C977B07`](https://basescan.org/token/0x75BB9e3eB32747D7A9eEEf8467f5f4C44C977B07) | Old Norse — Odin's raven of thought. Scouts every realm, returns each dusk. |
| Custos | CUSTOS | [`0x3EFf9f255B5a1891a8003A2Bf46dE45247a8aB07`](https://basescan.org/token/0x3EFf9f255B5a1891a8003A2Bf46dE45247a8aB07) | Latin — guardian. The watcher at every gate. |

Token admin / fee-claimant: `0x7a3E312Ec6e20a9F62fE2405938EB9060312E334`.

## Trade

Find each token on Clanker World using the addresses above, or trade directly on Uniswap V4 via Base.

## Companion onchain surface

These tokens sit alongside 14 utility contracts deployed by the same project:
- DeadManSwitch: https://github.com/lordbasilaiassistant-sudo/deadman-switch
- Keeper-bounty patterns: https://github.com/lordbasilaiassistant-sudo/keeper-bounty-lab
- Onchain primitives lab: https://github.com/lordbasilaiassistant-sudo/onchain-primitives-lab

Project home: https://thryx.fun

## Reward claim

```bash
PRIVATE_KEY=$THRYXTREASURY_PRIVATE_KEY npx clanker-sdk rewards --chain base
```

## License

MIT (manifest data only — token contracts are deployed via Clanker V4 and follow the standard Clanker license model).
