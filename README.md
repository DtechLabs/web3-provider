# Web3Provider
# Based on TrustWeb3Provider

![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/trustwallet/trust-web3-provider)
[![Platform](https://img.shields.io/cocoapods/p/TrustWeb3Provider.svg?style=flat)](http://cocoapods.org/pods/TrustWeb3Provider)
[![Platform](https://img.shields.io/badge/platform-android-lightgrey.svg)](https://jitpack.io/#TrustWallet/trust-web3-provider/0.2.1)

Web3Provider is multi-network web3 provider used by TrustWallet. Currently it supports:

- Ethereum
- Solana
- Cosmos
- Atos

## How to Identify Web3 Provider

If plasma provider injected properly `isPlasma` will be `true`

```javascript
window.ethereum.isPlasma
// or
window.plasmawallet.solana.isPlasms
```

## Installation

### iOS

Web3Provider is available through SPM (locally due to Xcode git lfs issue).

Swift Package Manager

Add this repo as a `git submodule`, then add it this to your `Package.swift`:

```swift
.package(name: "TrustWeb3Provider", path: "<local path>"),
```

Here is an example project located at `ios/PlasmaWeb3Provider.xcodeproj` to demonstrate how to use this provider.

To install it:

Step 1. Add jitpack to `repositories` in your root `build.gradle` file:

## License

Web3Provider is available under the MIT license. See the LICENSE file for more info.
