# Tukar Interface

An open source interface for Tukar -- a protocol for decentralized exchange of Ethereum tokens.

- Website: [tukar.xyz](https://tukar.xyz/)
- Twitter: [@tukarxyz](https://twitter.com/tukarxyz)
- Email: [support@tukar.xyz](mailto:support@tukar.xyz)

## Unsupported tokens

Check out `useUnsupportedTokenList()` in [src/state/lists/hooks.ts](./src/state/lists/hooks.ts) for blocking tokens in your instance of the interface.

You can block an entire list of tokens by passing in a tokenlist like [here](./src/constants/lists.ts) or you can block specific tokens by adding them to [unsupported.tokenlist.json](./src/constants/tokenLists/unsupported.tokenlist.json).

## Contributions

For steps on local deployment, development, and code contribution, please see [CONTRIBUTING](./CONTRIBUTING.md).

## Accessing Tukar V2

The Tukar Interface supports swapping, adding liquidity, removing liquidity and migrating liquidity for Tukar protocol V2.
