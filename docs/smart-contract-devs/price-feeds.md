---
sidebar_position: 4
sidebar_label: "💹 Price Feeds"
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

# 💹 Price feeds

## Available on chain (Classic Model)

The following feeds are available on-chain and are compatible with the [Chainlink interface](https://github.com/smartcontractkit/chainlink/blob/develop/contracts/src/v0.6/interfaces/AggregatorV3Interface.sol).

<Tabs>
  <TabItem value="Ethereum">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| weETH | USD | 1% | 6h | [0xdDb6F90fFb4d3257dd666b69178e5B3c5Bf41136](https://etherscan.io/address/0xdDb6F90fFb4d3257dd666b69178e5B3c5Bf41136#readProxyContract) |
| weETH | ETH | 0.5% | 24h | [0x8751F736E94F6CD167e8C5B97E245680FbD9CC36](https://etherscan.io/address/0x8751F736E94F6CD167e8C5B97E245680FbD9CC36#readProxyContract) | 
| ETHx | USD | 1% | 24h | [0xFaBEb1474C2Ab34838081BFdDcE4132f640E7D2d](https://etherscan.io/address/0xFaBEb1474C2Ab34838081BFdDcE4132f640E7D2d#readProxyContract) | 
| ETHx | ETH | 0.5% | 24h | [0xc799194cAa24E2874Efa89b4Bf5c92a530B047FF](https://etherscan.io/address/0xc799194cAa24E2874Efa89b4Bf5c92a530B047FF#readProxyContract) |
| osETH | ETH | 0.5% | 24h | [0x66ac817f997Efd114EDFcccdce99F3268557B32C](https://etherscan.io/address/0x66ac817f997Efd114EDFcccdce99F3268557B32C#readProxyContract) | 
| swETH | USD | 0.5% | 6h | [0x0704eEc81ea7CF98Aa4A400c65DC4ED5933bddf7](https://etherscan.io/address/0x0704eEc81ea7CF98Aa4A400c65DC4ED5933bddf7#readProxyContract) | 
| swETH | ETH | 0.5% | 6h | [0x061bB36F8b67bB922937C102092498dcF4619F86](https://etherscan.io/address/0x061bB36F8b67bB922937C102092498dcF4619F86#readProxyContract) | 
| XVS | USD | 1% | 24h | [0xa2a8507DEb233ceE4F5594044C259DD0582339CC](https://etherscan.io/address/0xa2a8507DEb233ceE4F5594044C259DD0582339CC#readProxyContract) | 
| C3M | USD | - | 12:00 | [0x6E27A25999B3C665E44D903B2139F5a4Be2B6C26](https://etherscan.io/address/0x6E27A25999B3C665E44D903B2139F5a4Be2B6C26#readProxyContract) | 
| eUSD | USD | 1% | 24h | [0xb347d2e3524D0F9e2321D84A2E9b2e60CbC4A836](https://etherscan.io/address/0xb347d2e3524D0F9e2321D84A2E9b2e60CbC4A836#readProxyContract) | 
| apxETH | ETH | 1% | 24h | [0x19219BC90F48DeE4d5cF202E09c438FAacFd8Bea](https://etherscan.io/address/0x19219BC90F48DeE4d5cF202E09c438FAacFd8Bea#readProxyContract) | 
| rsETH | ETH | 1% | 24h | [0xA736eAe8805dDeFFba40cAB8c99bCB309dEaBd9B](https://etherscan.io/address/0xA736eAe8805dDeFFba40cAB8c99bCB309dEaBd9B#readProxyContract) | 
| ezETH | ETH | 1% | 12h | [0xF4a3e183F59D2599ee3DF213ff78b1B3b1923696](https://etherscan.io/address/0xF4a3e183F59D2599ee3DF213ff78b1B3b1923696#readProxyContract) | 
| rswETH | ETH | 1% | 24h | [0x3A236F67Fce401D87D7215695235e201966576E4](https://etherscan.io/address/0x3A236F67Fce401D87D7215695235e201966576E4#readProxyContract) | 
| USDe | USD | 0.2% | 24h | [0xbC5FBcf58CeAEa19D523aBc76515b9AEFb5cfd58](https://etherscan.io/address/0xbC5FBcf58CeAEa19D523aBc76515b9AEFb5cfd58#readProxyContract) | 
| sUSDe | USD | 0.2% | 24h | [0xb99D174ED06c83588Af997c8859F93E83dD4733f](https://etherscan.io/address/0xb99D174ED06c83588Af997c8859F93E83dD4733f#readProxyContract) | 
| pufETH | ETH | 1% | 24h | [0x76A495b0bFfb53ef3F0E94ef0763e03cE410835C](https://etherscan.io/address/0x76A495b0bFfb53ef3F0E94ef0763e03cE410835C#readProxyContract) | 
| ETH+ | ETH | 0.5% | 24h | [0x3B9c09bde7776C32C518e2E787412A9bBaA7685F](https://etherscan.io/address/0x3B9c09bde7776C32C518e2E787412A9bBaA7685F#readProxyContract) | 
| sfrxETH | ETH | 0.5% | 6h | [0xdd60c54115C19e0c6360AD4762B88BB8076D50a8](https://etherscan.io/address/0xdd60c54115C19e0c6360AD4762B88BB8076D50a8#readProxyContract) | 

  </TabItem>
  <TabItem value="Arbitrum">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| agEUR | USD | 1% | 24h | [0x37963F10245e7c3a10c0E9d43a6E617B4Bc8440A](https://arbiscan.io/address/0x37963F10245e7c3a10c0E9d43a6E617B4Bc8440A#readProxyContract) |
| PREMIA | USD | 0.5% | 24h | [0x50db815D3c4B869F89925690E936ED85b0b76075](https://arbiscan.io/address/0x50db815D3c4B869F89925690E936ED85b0b76075#readProxyContract) | 
| weETH | eETH (contract rate) | 0.5% | 12h | [0x119A190b510c9c0D5Ec301b60B2fE70A50356aE9](https://arbiscan.io/address/0x119A190b510c9c0D5Ec301b60B2fE70A50356aE9#readProxyContract) | 
| weETH | ETH | 0.5% | 24h | [0xA736eAe8805dDeFFba40cAB8c99bCB309dEaBd9B](https://arbiscan.io/address/0xA736eAe8805dDeFFba40cAB8c99bCB309dEaBd9B#readProxyContract) | 
| sUSDe_RATE_PROVIDER | - | - | 24h | [0x3A236F67Fce401D87D7215695235e201966576E4](https://arbiscan.io/address/0x3A236F67Fce401D87D7215695235e201966576E4#readProxyContract) | 
| XVS | USD | 1 | 24h | [0xd9a66Ff1D660aD943F48e9c606D09eA672f312E8](https://arbiscan.io/address/0xd9a66Ff1D660aD943F48e9c606D09eA672f312E8#readProxyContract) | 

  </TabItem>
  <TabItem value="Manta">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| MANTA | USD | 0.5% | 6h | [0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99](https://pacific-explorer.manta.network/address/0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99?tab=read_proxy) |
| STONE | USD | 0.5% | 6h | [0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99](https://pacific-explorer.manta.network/address/0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99?tab=read_proxy) |
| ETH | USD | 0.5% | 6h | [0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99](https://pacific-explorer.manta.network/address/0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99?tab=read_proxy) |
| USDC | USD | 0.5% | 6h | [0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99](https://pacific-explorer.manta.network/address/0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99?tab=read_proxy) |
| wUSDM | USD | 0.5% | 6h | [0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99](https://pacific-explorer.manta.network/address/0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99?tab=read_proxy) |
| wstETH | USD | 0.5% | 6h | [0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99](https://pacific-explorer.manta.network/address/0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99?tab=read_proxy) |
| TIA | USD | 0.5% | 6h | [0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99](https://pacific-explorer.manta.network/address/0x6e3661519025D6cBcAFD3013D5BDB7aB71741B99?tab=read_proxy) |
  *) The feeds on Manta follow the multi-feed interface proposed by LayerBank. Please use the `priceOf(address)` method passing the address of an asset. 
  </TabItem>
  <TabItem value="Blast">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| BTC | USD | 0.5% | 1h | [0x7262c8C5872A4Aa0096A8817cF61f5fa3c537330](https://blastscan.io/address/0x7262c8C5872A4Aa0096A8817cF61f5fa3c537330#readProxyContract) |
| ETH | USD | 0.5% | 1h | [0x0af23B08bcd8AD35D1e8e8f2D2B779024Bd8D24A](https://blastscan.io/address/0x0af23B08bcd8AD35D1e8e8f2D2B779024Bd8D24A#readProxyContract) |
| USDB | USD | 0.5% | 6h | [0x3A236F67Fce401D87D7215695235e201966576E4](https://blastscan.io/address/0x3A236F67Fce401D87D7215695235e201966576E4#readProxyContract) |
| weETH | ETH | 0.5% | 24h | [0xcD96262Df56127f298b452FA40759632868A472a](https://blastscan.io/address/0xcD96262Df56127f298b452FA40759632868A472a#readProxyContract) |
| ezETH | ETH | 0.5% | 24h | [0x6bc42F8Ee8cD9BEA7d5CfF0934Ce73eCD2c11e99](https://blastscan.io/address/0x6bc42F8Ee8cD9BEA7d5CfF0934Ce73eCD2c11e99#readProxyContract) |
| apxETH | ETH | 0.5% | 24h | [0x0c86AAbBEEF451f28C0CE4e9Cfeecc98a7881087](https://blastscan.io/address/0x0c86AAbBEEF451f28C0CE4e9Cfeecc98a7881087#readProxyContract) |

  </TabItem>
  <TabItem value="Blast Testnet">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| ETH | USD | 0.5% | 1h | [0xc447B8cAd2db7a8B0fDde540B038C9e06179c0f7](https://testnet.blastscan.io/address/0xc447B8cAd2db7a8B0fDde540B038C9e06179c0f7) | 
| BTC | USD | 0.5% | 1h | [0x24b44096A381344A43559882c9A23A9DAd420781](https://testnet.blastscan.io/address/0x24b44096A381344A43559882c9A23A9DAd420781) |
| USDB | USD | 0.5% | 1h | [0x2Bc667aDbf3ed021834114599C15388c49C9c773](https://testnet.blastscan.io/address/0x2Bc667aDbf3ed021834114599C15388c49C9c773) | 

  </TabItem>
  <TabItem value="BSC">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| TRX | USD | 0.2% | 10m | [0xa17362dd9ad6d0af646d7c8f8578fddbfc90b916](https://bscscan.com/address/0xa17362dd9ad6d0af646d7c8f8578fddbfc90b916#readProxyContract) | 
| ezETH | ETH | 1% | 12h | [0x3A236F67Fce401D87D7215695235e201966576E4](https://bscscan.com/address/0x3A236F67Fce401D87D7215695235e201966576E4#readProxyContract) | 
| BNB | USD | 0.1% | 1m | [0x8dd2D85C7c28F43F965AE4d9545189C7D022ED0e](https://bscscan.com/address/0x8dd2D85C7c28F43F965AE4d9545189C7D022ED0e#readProxyContract) | 
| BTC | USD | 0.1% | 1m | [0xa51738d1937FFc553d5070f43300B385AA2D9F55](https://bscscan.com/address/0xa51738d1937FFc553d5070f43300B385AA2D9F55#readProxyContract) | 
| weETH | eETH | 0.5% | 6h | [0x9b2C948dbA5952A1f5Ab6fA16101c1392b8da1ab](https://bscscan.com/address/0x9b2C948dbA5952A1f5Ab6fA16101c1392b8da1ab#readProxyContract) | 

  </TabItem>
  <TabItem value="Kava">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| ETH | USD | 0.5% | 1h | [0x5C552051bcD340cC57fa5Fb1ecdF0d896B1379Ec](https://kavascan.com/address/0x5C552051bcD340cC57fa5Fb1ecdF0d896B1379Ec/read-proxy#address-tabs) |
| BTC | USD | 0.5% | 1h | [0x099E81C3A9aA6185c083ac579ef60541418dE8d7](https://kavascan.com/address/0x099E81C3A9aA6185c083ac579ef60541418dE8d7/read-proxy#address-tabs) |
| USDT | USD | 0.2% | 1h | [0xc0c3B20Af1A431b9Ab4bfe1f396b12D97392e50f](https://kavascan.com/address/0xc0c3B20Af1A431b9Ab4bfe1f396b12D97392e50f/read-proxy#address-tabs) |

  </TabItem>
  <TabItem value="Mantle">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| ETH | USD | 0.5% | 1h | [0xFc34806fbD673c21c1AEC26d69AA247F1e69a2C6](https://explorer.mantle.xyz/address/0xFc34806fbD673c21c1AEC26d69AA247F1e69a2C6/contracts?contract-tab=read-proxy#address-tabs) |
| MNT | USD | 0.5% | 1h | [0xed1f0df0b88889e5eA19c768613cDf3DbBF3d2a7](https://explorer.mantle.xyz/address/0xed1f0df0b88889e5eA19c768613cDf3DbBF3d2a7/contracts?contract-tab=read-proxy#address-tabs) |
| wstETH | ETH | 0.5% | 1h | [0xE8d850331faAbb277a24C09d91aabb68fb808748](https://explorer.mantle.xyz/address/0xE8d850331faAbb277a24C09d91aabb68fb808748/contracts?contract-tab=read-proxy#address-tabs) |
| USDe | USD | 0.2% | 24h | [0x3DFA26B9A15D37190bB8e50aE093730DcA88973E](https://explorer.mantle.xyz/address/0x3DFA26B9A15D37190bB8e50aE093730DcA88973E/contracts?contract-tab=read-proxy#address-tabs) |
| sUSDe | USD | 0.2% | 24h | [0xd6a987Ff6323F658D04da16c36CE00960137a115](https://explorer.mantle.xyz/address/0xd6a987Ff6323F658D04da16c36CE00960137a115/contracts?contract-tab=read-proxy#address-tabs) |
| USDT | USD | 0.25% | 24h | [0x3A236F67Fce401D87D7215695235e201966576E4](https://explorer.mantle.xyz/address/0x3A236F67Fce401D87D7215695235e201966576E4/contracts?contract-tab=read-proxy#address-tabs) |

  </TabItem>
  <TabItem value="Canto">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| ATOM | USD | 1% | 1h | 0xCe8937eF7f3874e71C65C55470253B6b86f7C1AB |
| CANTO | USD | 1% | 1h | 0x93063D743Fc0082121aec5d183e40554468E1568 |
| ETH | USD | 1% | 1h | 0x6D882e6d7A04691FCBc5c3697E970597C68ADF39 |
| USDC | USD | 1% | 1h | 0x1b23243882DC7F419Ba01B5a841554f7bb0b9Da1 |
| USDT | USD | 1% | 1h | 0x5BA83F63c558cedba271a1892188b58360976acc |

  </TabItem>
  <TabItem value="Mode">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| ETH* | USD | 0.5% | 6h | [0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256](https://explorer.mode.network/address/0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256?tab=read_proxy) |
| BTC* | USD | 0.5% | 6h | [0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256](https://explorer.mode.network/address/0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256?tab=read_proxy) |
| USDC* | USD | 0.5% | 6h | [0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256](https://explorer.mode.network/address/0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256?tab=read_proxy) |
| USDT* | USD | 0.5% | 6h | [0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256](https://explorer.mode.network/address/0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256?tab=read_proxy) |
| weETH* | USD | 0.5% | 6h | [0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256](https://explorer.mode.network/address/0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256?tab=read_proxy) |
| ezETH* | USD | 0.5% | 6h | [0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256](https://explorer.mode.network/address/0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256?tab=read_proxy) |
| STONE* | USD | 0.5% | 6h | [0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256](https://explorer.mode.network/address/0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256?tab=read_proxy) |
| rsETH* | USD | 0.5% | 6h | [0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256](https://explorer.mode.network/address/0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256?tab=read_proxy) |
| weETH** | eETH | 0.5% | 6h | [0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256](https://explorer.mode.network/address/0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256?tab=read_proxy) |
| MODE | USD | 0.5% | 24h | [0x8dd2D85C7c28F43F965AE4d9545189C7D022ED0e](https://explorer.mode.network/address/0x8dd2D85C7c28F43F965AE4d9545189C7D022ED0e?tab=read_proxy) |
  *) The feeds on Mode follow the multi-feed interface proposed by LayerBank. Please use the `priceOf(address)` method passing the address of an asset.<br />
  **) weETH/eETH rate value is available through `priceOfWeETHRate()` function 


  </TabItem>
  <TabItem value="Fraxtal">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| BTC | USD | 0.5% | 6h | [0x8dd2D85C7c28F43F965AE4d9545189C7D022ED0e](https://fraxscan.com/address/0x8dd2D85C7c28F43F965AE4d9545189C7D022ED0e#readProxyContract) |
| CRV | USD | 0.5% | 6h | [0x6C5090e85a65038ca6AB207CDb9e7a897cb33e4d](https://fraxscan.com/address/0x6C5090e85a65038ca6AB207CDb9e7a897cb33e4d#readProxyContract) |
| ETH | USD | 0.5% | 6h | [0x89e60b56efD70a1D4FBBaE947bC33cae41e37A72](https://fraxscan.com/address/0x89e60b56efD70a1D4FBBaE947bC33cae41e37A72#readProxyContract) |
| FRAX | USD | 0.5% | 6h | [0xa41107f9259bB835275eaCaAd8048307B80D7c00](https://fraxscan.com/address/0xa41107f9259bB835275eaCaAd8048307B80D7c00#readProxyContract) |
| FXS | USD | 0.5% | 6h | [0xbf228a9131AB3BB8ca8C7a4Ad574932253D99Cd1](https://fraxscan.com/address/0xbf228a9131AB3BB8ca8C7a4Ad574932253D99Cd1#readProxyContract) |

  </TabItem>
  <TabItem value="Linea">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| weETH | eETH | 0.5% | 6h | [0x100c8e61aB3BeA812A42976199Fc3daFbcDD7272](https://lineascan.build/address/0x100c8e61aB3BeA812A42976199Fc3daFbcDD7272#readProxyContract) |
| ezETH | eETH | 0.5% | 24h | [0x97c19d3Ae8e4d74e25EF3AFf3a277fB614ed76D4](https://lineascan.build/address/0x97c19d3Ae8e4d74e25EF3AFf3a277fB614ed76D4#readProxyContract) |

  </TabItem>
  <TabItem value="B²">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| BTC | USD | 0.5% | 24h | [0xfcd454d19f9B8806F8908e99d85b8eA17b3c7346](https://explorer.bsquared.network/address/0xfcd454d19f9B8806F8908e99d85b8eA17b3c7346) |
| USDT | USD | 0.2% | 24h | [0xfcd454d19f9B8806F8908e99d85b8eA17b3c7346](https://explorer.bsquared.network/address/0xfcd454d19f9B8806F8908e99d85b8eA17b3c7346) |
| STONE | USD | 0.5% | 24h | [0xfcd454d19f9B8806F8908e99d85b8eA17b3c7346](https://explorer.bsquared.network/address/0xfcd454d19f9B8806F8908e99d85b8eA17b3c7346) |
  *) The feeds on B² follow the multi-feed interface proposed by LayerBank. Please use the `priceOf(address)` method passing the address of an asset. 
  **) BTC rate value is available through `priceOfBTC()` function 

  </TabItem>
  <TabItem value="BOB">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| BTC | USD | 0.5% | 1h | [0x2d484E029b8Ae5cA6335DAe11fC726B232bE87D1](https://explorer.gobob.xyz/address/0x2d484E029b8Ae5cA6335DAe11fC726B232bE87D1?tab=read_proxy) |
| ETH | USD | 0.5% | 1h | [0x2d484E029b8Ae5cA6335DAe11fC726B232bE87D1](https://explorer.gobob.xyz/address/0x2d484E029b8Ae5cA6335DAe11fC726B232bE87D1?tab=read_proxy) |
| USDC | USD | 0.2% | 1h | [0x2d484E029b8Ae5cA6335DAe11fC726B232bE87D1](https://explorer.gobob.xyz/address/0x2d484E029b8Ae5cA6335DAe11fC726B232bE87D1?tab=read_proxy) |
| USDT | USD | 0.2% | 1h | [0x2d484E029b8Ae5cA6335DAe11fC726B232bE87D1](https://explorer.gobob.xyz/address/0x2d484E029b8Ae5cA6335DAe11fC726B232bE87D1?tab=read_proxy) |
| STONE | USD | 0.5% | 1h | [0x2d484E029b8Ae5cA6335DAe11fC726B232bE87D1](https://explorer.gobob.xyz/address/0x2d484E029b8Ae5cA6335DAe11fC726B232bE87D1?tab=read_proxy) 
| wstETH | USD | 0.5% | 1h | [0x2d484E029b8Ae5cA6335DAe11fC726B232bE87D1](https://explorer.gobob.xyz/address/0x2d484E029b8Ae5cA6335DAe11fC726B232bE87D1?tab=read_proxy) |
  *) The feeds on BOB follow the multi-feed interface proposed by LayerBank. Please use the `priceOf(address)` method passing the address of an asset. 
  **) ETH rate value is available through `priceOfETH()` function 

  </TabItem>
  <TabItem value="Merlin">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| BTC | USD | 0.5% | 24h | [0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256](https://scan.merlinchain.io/address/0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256) |
| MERL | USD | 1.0% | 24h | [0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256](https://scan.merlinchain.io/address/0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256)|
| SolvBTC | BTC | 0.5% | 24h | [0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256](https://scan.merlinchain.io/address/0x7C1DAAE7BB0688C9bfE3A918A4224041c7177256) |
  *) The feeds on Merlin follow the multi-feed interface proposed by LayerBank. Please use the `priceOf(address)` method passing the address of an asset for feeds denominated in USD and `priceOfInBTC(address)` for these denominated in BTC. 
  **) BTC rate value is available through `priceOfBTC()` function 

  </TabItem>
  <TabItem value="Base">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| pufETH | ETH | 0.5% | 24h | [0x4aaf2844c5420bf979d5bc2cf883ef02db07e590](https://basescan.org/address/0x4aaf2844c5420bf979d5bc2cf883ef02db07e590#readProxyContract) |

  </TabItem>
  <TabItem value="Etherlink Testnet">

| Symbol | Denomination | Deviation threshold | Heartbeat | Contract Address |
| -------------------------- | -------------------------- | -------------------------- | -------------------------- | -------------------------- |
| ETH | USD | --- | 10s | [0xb31D94df41ccc22b46fd2Ae4eA2a6D6eB9c23bfb](https://testnet-explorer.etherlink.com/address/0xb31D94df41ccc22b46fd2Ae4eA2a6D6eB9c23bfb?tab=read_proxy)|
| BTC | USD | --- | 10s | [0xfe66A25096128f57D3876D42cD2B4347a77784c2](https://testnet-explorer.etherlink.com/address/0xfe66A25096128f57D3876D42cD2B4347a77784c2?tab=read_proxy)|
| XTZ | USD | --- | 10s | [0xE06FE39f066562DBfE390167AE49D8Cb66e1F887](https://testnet-explorer.etherlink.com/address/0xE06FE39f066562DBfE390167AE49D8Cb66e1F887?tab=read_proxy)|

  </TabItem>
</Tabs>


## Available to pull (Core Model)

Thanks to its unique design, RedStone can provide 1000+ price feeds for various types of data, including:

- Crypto
- Stocks
- Currencies
- Commodities
- ETFs
- And many more...

You can check all the available data provided by RedStone in [our web app.](https://app.redstone.finance/#/app/tokens)
