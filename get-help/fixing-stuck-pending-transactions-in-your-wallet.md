---
description: How to ‘unstuck’ any pending transactions that are stuck in your wallet.
---

# Fixing Stuck Pending Transactions in Your Wallet

Every once in a blue moon there can be a hiccup in the transaction in your wallet that the cancel button just can't fix. This walkthrough will essentially wipe the pending transaction by sending a new transaction that replaces the order by resetting the pipeline.

1. **Enable Custome Transaction Nonce**
   1. Open the MetaMask plugin on your browser
   2.  Click the multcolored circle in the upper right of the popup. Usually opposite of the fox head icon

       <figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>
   3.  Select Settings

       <figure><img src="../.gitbook/assets/image (13) (1).png" alt=""><figcaption></figcaption></figure>
   4.  Select Advanced

       <figure><img src="../.gitbook/assets/image (11) (1) (2).png" alt=""><figcaption></figcaption></figure>
   5.  Scroll to Advanced gas controls and make sure the toggle is in the on position

       <figure><img src="../.gitbook/assets/image (1) (1) (2).png" alt=""><figcaption></figcaption></figure>
   6.  Still in the advanced section, go to customize transaction nonce and make sure this is toggled on too

       <figure><img src="../.gitbook/assets/image (3) (2).png" alt=""><figcaption></figcaption></figure>
2. &#x20;**Find the Stuck Transaction**

We need to find the stuck transaction and remember the nonce. The nonce is an identifier that we will be using later

1.  Back at the main Metamask screen select the **Activity** tab and find the token that is stuck in the transaction.&#x20;

    <figure><img src="../.gitbook/assets/image (2) (1) (2).png" alt=""><figcaption></figcaption></figure>
2.  Look for the nonce and note the number

    <figure><img src="../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>
3. **Overwrite the Stuck Transaction**

**Essentially we will be making a new transaction to replace the stuck transaction and we will put in the same nonce as the old transaction**

1.  Create a new transaction with a higher gas fee. In the MetaMask popup select **edit** for the estimated gas fee.

    <figure><img src="../.gitbook/assets/image (2) (2) (1).png" alt=""><figcaption></figcaption></figure>

Remember the gas fee increases the priority of the transaction and will ensure that this nonce is accepted over the old stuck transaction in your wallet.

<figure><img src="../.gitbook/assets/image (6) (2) (1).png" alt=""><figcaption></figcaption></figure>

&#x20; 2\.  On the confirmation screen ensure the gas fee has really been increased.

<figure><img src="../.gitbook/assets/image (14) (1) (1).png" alt=""><figcaption></figcaption></figure>

&#x20; 3\.  Find the custom nonce entry and put in the nonce we noted earlier.

<figure><img src="../.gitbook/assets/image (15) (1).png" alt=""><figcaption></figcaption></figure>

&#x20; 4\.  Click **Confirm.**

&#x20; ****  5.  The transaction should be accepted. Go to the activity section of your MetaMask wallet to make sure it went through.

**Remember that transactions are fast but not instantaneous. Be patient and give the transaction time to process. You can increase the gas fee to increase its priority if you want to. You don't need to worry about a duplicate transaction because no wallet can process the same nonce identifier twice.**&#x20;







