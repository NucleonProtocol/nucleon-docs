---
description: >-
  KuCoin is one of the largest cryptocurrency exchanges in the world. KuCoin
  supports trading for CFX on Conflux eSpace.
---

# Transferring eSpace CFX from KuCoin to MetaMask

## Overview

{% hint style="danger" %}
**Note to Binance users and bCFX holders**: Conflux on Binance is listed as wrapped ERC-20 token, it is **not** native CFX. Conflux eSpace and BNB Chain use EVM-compatible addresses, but those addresses live in different chains.
{% endhint %}

For clarity's purpose:

* KuCoin lists **eSpace CFX**, the native _currency_ of Conflux eSpace.
* Binance lists **wrapped CFX** (or bCFX), an _ERC-20 token_ deployed on BNB Chain.
* You cannot transfer CFX from KuCoin to a Binance wallet, nor to a wallet that is connected to the BNB Chain network.
  * To learn how to transfer your CFX from KuCoin to Conflux eSpace, follow this guide.
* You **cannot** transfer natively bCFX from a BNB Chain wallet to any Conflux eSpace wallet, nor to a KuCoin wallet.
  * To learn how to bridge your bCFX to Conflux eSpace, see: [Bridging bCFX from BNB Chain to Conflux eSpace Using Multichain.org](../from-other-networks/bridging-from-ethereum-and-bnb-chain-with-multichain.md).
* You **cannot** transfer natively eSpace CFX to a Binance account nor to a wallet connected to the BNB Chain network.

| From                    | To                      | How                                                                                                                                                           |
| ----------------------- | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| KuCoin exchange wallet  | Conflux eSpace wallet   | ✅ Natively, send to your MetaMask wallet.                                                                                                                     |
| Binance exchange wallet | Conflux eSpace wallet   | ✅ Bridge your tokens using Multichain (learn how).                                                                                                            |
| KuCoin exchange wallet  | Binance exchange wallet | ❌ Cannot do it directly. You'll need to send your CFX to MetaMask first, then bridge them to BSC using Multichain, then sending them to your exchange wallet. |

## Prerequisites

{% hint style="info" %}
This tutorial is focused on MetaMask, but you can use any other supported wallet, such as Wallet Connect-based wallets and Ledger devices. \
\
See [Supported Wallets](../../wallets/supported-wallets.md) for more information.
{% endhint %}

* A KuCoin account.
* At least **5 CFX** traded on KuCoin. You can trade using the CFX/USDT market. To learn how to do Spot trading on KuCoin, see: [How to Make a Trade on KuCoin](https://support.kucoin.plus/hc/en-us/sections/4403577442201-Spot-Trading).
* A MetaMask wallet connected to Conflux eSpace. To learn how to connect your MetaMask wallet to Conflux eSpace, see: [Connecting MetaMask to Conflux eSpace](../../getting-started/connecting-metamask-to-nucleon.md).

## Transferring eSpace CFX from KuCoin to MetaMask

To transfer CFX from KuCoin to you MetaMask account on Conflux eSpace:

1. Go to KuCoin.
2. In KuCoin, go to your wallet and click **Withdraw**.\
   ![](<../../.gitbook/assets/image (13) (2).png>)
3. In the Withdraw Crypto search bar, search for "CFX" and click the result.\
   ![](<../../.gitbook/assets/image (21).png>)
4. In the Wallet Address field, copy your Conflux eSpace account address from MetaMask.\
   ![](<../../.gitbook/assets/image (7) (2).png>)
5. In the Network select, select **CFX - Conflux (CFX)**.\
   ![](<../../.gitbook/assets/image (2) (1).png>)
6. In the CFX Amount field, enter the amount of CFX that you want to transfer.
7. _Optional_: In the Remarks field, add any notes about this transaction.
8. Review the transaction details, the transaction fee and click **Confirm**.
9. In the Tamper-Proofing Confirmation dialog, confirm the withdrawal information and click **Confirm Withdrawal**.\
   ![](<../../.gitbook/assets/image (23) (1).png>)
10. Finally, verify your security details and click .\
    **Note**: The transaction might take a few minutes to process.

![](<../../.gitbook/assets/image (22) (1).png>)

You have transferred CFX from KuCoin to your Conflux eSpace account.
