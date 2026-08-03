# Day 1 - August 2, 2026

## Contract: UniswapV2Pair.sol (SushiSwap v2-core)

## What I found:
- `function _safeTransfer()` - moves tokens
- `event Swap` - records swaps
- `event Mint` - records liquidity creation
- `event Burn` - records liquidity burning
- `event Sync` - records reserves

## What I didn't understand:
- `token.call(abi.encodeWithSelector(SELECTOR, to, value))` - I don't know what SELECTOR does

## Next steps:
- Investigate what SELECTOR is
- Find where `_safeTransfer()` is used inside `swap()`

## Evidence:
- Contract opened and reviewed
- Functions identified

## Time spent: 1 hour
