# Bridging Stablecoins with Meso

[Meson](http://meson.fi) is a stablecoin cross-chain swap protocol that supports multiple networks. With Meson, you can bridge either USDC or USDT tokens from different networks into Conflux eSpace, or from Conflux eSpace to other networks.

In this guide, we'll bridge USDC on BNB Chain to USDT on Conflux eSpace through Meson.

## Prerequisites

* A USDC or USDT stablecoin on any of the following networks:
  * Ethereum (USDC/USDT)
  * BNB Chain (USDC/USDT)
  * Tron (USDT)
  * Avalanche (USDC)
  * Fantom (USDC)
  * Polygon (USDC)
  * Conflux (USDC/USDT)
* Your MetaMask wallet connected to Conflux eSpace.

## Bridging Stablecoins to Conflux eSpace with Meson

1. Go to [Meson](https://meson.fi/).​
2. Click **Connect Wallet** to connect MetaMask to Meson.\
   ![](<../../.gitbook/assets/image (36).png>)
3. Select the account(s) that you wish to use on Meson and click **Next**.\
   ![](<../../.gitbook/assets/image (67).png>)
4. Confirm the connection to the site by clicking **Connect**.\
   ![](<../../.gitbook/assets/image (2).png>)\
   Your MetaMask wallet is now connected to Meson. Let's now bridge our tokens.
5. In the **FROM** drop-down list, select the network that you'll transfer your assets from (for example: BNB Chain).\
   ![](<../../.gitbook/assets/image (59).png>)
6. In the token type drop-down list, select **USDC**.\
   ![](<../../.gitbook/assets/image (11).png>)
7. Enter the amount of USDC that you want to transfer.\
   ![](<../../.gitbook/assets/image (37).png>)
8. In the **TO** drop-down list, select **Conflux eSpace**.\
   ![](<../../.gitbook/assets/image (24).png>)
9. Confirm the transaction details and click **Swap**.\
   ![](<../../.gitbook/assets/image (5).png>)
10. In the Approve dialog, click **Approve** to invoke MetaMask and grant Meson permission to access your funds. \
    ![](<../../.gitbook/assets/image (10).png>)\
    **Note**: The approval operation requires a gas fee, however, this is the only time you'll need to pay for gas, the gas fee for other steps are on Meson.
11. In MetaMask, click **Confirm** to give permission to Meson to access your funds.\
    ![](<../../.gitbook/assets/image (49).png>)
12. Once you grant permission to MetaMask, click **Confirm** in the Swap Summary to confirm the swap transaction you're about to do.\
    ![](<../../.gitbook/assets/image (50).png>)
13. Now, in MetaMask, click **Sign** to sign and proceed with the transaction.\
    ![](<../../.gitbook/assets/image (55).png>)
14. In the Swap Summary, wait for the swap request to be processed. \
    **Note**: This may take around 1 minute.\
    ![](<../../.gitbook/assets/image (61).png>)
15. Once the swap request transaction is processed, click **Sign** on MetaMask to release the funds in Conflux.\
    ![](<../../.gitbook/assets/image (68).png>)\
    You have now bridged your funds to Conflux eSpace!



## Verifying Transactions

To verify the transaction:

1. Open the wallet menu.\
   ![](<../../.gitbook/assets/image (47).png>)
2. Click on the Swap ID to open the Meson transaction explorer.\
   ![](<../../.gitbook/assets/image (13).png>)\

3. You can verify the transactions on both networks' transaction explorers.\
   ![](<../../.gitbook/assets/image (15).png>)

## Additional Resources

* To learn more about Meson, check out Meson's blog at [https://medium.com/@mesonfi](https://medium.com/@mesonfi).\
