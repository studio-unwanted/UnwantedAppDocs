# How To Airdrop

To airdrop to externally owned accounts, you will need to upload a CSV file with the addresses of the accounts you want to send tokens or NFTs to as well as the balances or token ids of the token or NFT you want to airdrop. Visit the Airdropper to get started.

{% hint style="danger" %}
MAKE SURE THAT YOU ONLY CONNECT TO THE OFFICIAL UNWANTED APPLICATION TO PREVENT PHISHING SCAMS!
{% endhint %}

### Page View:

Desktop:

![](<../../.gitbook/assets/Screen Shot 2022-03-02 at 1.27.50 AM.png>)

Mobile:

![](<../../.gitbook/assets/Screen Shot 2022-03-02 at 1.33.24 AM.png>)

### Select A Token Or NFT

Begin the airdrop process by first selecting a token or NFT to airdrop.



![](<../../.gitbook/assets/Screen Shot 2022-03-01 at 4.49.54 PM.png>)

Use the tab selector to select either an NFT or Token to airdrop.



Below will be either Tokens or NFTs:

Tokens:

![](<../../.gitbook/assets/Screen Shot 2022-03-01 at 5.30.31 PM (1).png>)

NFTs:

![](<../../.gitbook/assets/Screen Shot 2022-03-01 at 5.31.10 PM.png>)

Click on an asset and it will bring up a modal asking you to add the asset to the queue.

![](<../../.gitbook/assets/Screen Shot 2022-03-01 at 5.20.26 PM (1).png>)

Click on `Add Token` (or NFT) and the asset will be added to the queue.

After adding the asset, the selection container will switch to a container with a button to upload a CSV.

![](<../../.gitbook/assets/Screen Shot 2022-03-01 at 5.38.39 PM.png>)

### CSV Uploader

The CSV uploader will accept CSV files that contain data that fits the upload acceptance criteria.

#### Token Airdrop Criteria:

The CSV to upload may look similar to:

| HolderAddress\* | Balance\*\*\* |
| --------------- | ------------- |
| 0x123           | 12390         |
| 0x456           | 1.213         |
| 0x789           | 0.004         |
| 0x012           | 1E-12         |
| 0x888           | 120.3323      |



#### NFT Airdrop Criteria

| HolderAddress\* | TokenId\*\* |
| --------------- | ----------- |
| 0x892           | 23          |
| 0x991           | 1           |
| 0x321           | 482         |

{% hint style="info" %}
Please include the full Address\*

NFT Token Ids cannot be non-existing\*\*

Token Balances must be positive\*\*\*
{% endhint %}

Upload the CSV file and allow the application to load the data. The app will display the total balance to send as well as the total amount of addresses.\
\
![](<../../.gitbook/assets/Screen Shot 2022-03-01 at 5.41.35 PM.png>)



### Prepare & Initiate

Doing so will enable the `Cast Token Airdrop` button at the bottom allowing you to view the list of batches that are prepared to be sent.

![](../../.gitbook/assets/adex1.gif)

You will have to approve the Airdropper to transfer to the addresses on your behalf. This will allow the Airdropper to be able to transfer the total balance based on the amounts of balances parsed from the CSV.



After approval, you may begin initiating the batch transfers by clicking on `Initiate Airdrop` each batch. This will initiate a transaction that will send the inputted balances of up to 200 addresses in a single transaction.&#x20;

Ex. Tx on the Kovan ETH Network: [https://kovan.etherscan.io/tx/0x278a64443215dd296f4105f819f5e1bb84cb609c4637a18df24a6c4bcddc58f8](https://kovan.etherscan.io/tx/0x278a64443215dd296f4105f819f5e1bb84cb609c4637a18df24a6c4bcddc58f8)
