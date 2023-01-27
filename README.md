# web3-react-native
The one package library for web3 and react native development

Overview
- Inspired by [create-react-native-dapp](https://github.com/cawfree/create-react-native-dapp) however not supported as much atm.
- Cool wallets such as Rainbow, Showtime and many more are built on RN.
- Create a npx type of package to install either a wallet or dapp creation in react native

```
npx create-web3-react-native@latest --wallet
npx create-web3-react-native@latest --dapp
```

Wallet Side
- Creates a simple Expo app with a random mnemonic seed phrase
- Uses WalletConnect SignV2 and Auth for connection
- Futher down the line could add more falg options to include packages such as `react-native-lens-ui-kit`

Dapp Side
- Will be supported via either `react-native-dapp`, `web3modalv2` (soon) or `connectkit`
- Uses wagmi / ethers depending on the wrapper

---

To test before making it one package
- [ ] WalletConnect Sign V2
- [ ] WalletConnect Auth V2
- [ ] Wagmi + react-native-dapp
- [ ] Wagmi + W3MV2
- [ ] Wagmi + ConnectKit

Later
- [ ] Wagmi + RainbowKit
- [ ] NotAWallet: a burner seed phrase wallet + account abstraction
- [ ] NotAWalletV2: a MPC wallet.
- [ ] NotAWalletV3: burner / MPC Wallet to onboard people (register ENS / make swaps / buy an NFT)
- [ ] Make a community compiled list on Web3 And React Native
- [ ] Explore Solana and Cosmos


