# Scam Filter

On the blockchain, there are some tokens that act as malicious trojan horses that when provided approval, can remove any amount of one's assets out of their wallet. The way these tokens work is that a malicious actor on the chain deploys an ERC20 or ERC721 token with the`approve` and `transfer` function overridden. Thus enabling **only them to transact with the token**. The deployer can then send this token to hundreds to thousands of people in hopes that they will want to either trade it in on their website or try to transfer it away. Doing so will approve the **malicious token to perform a hidden transaction that siphons assets out of the transactor's wallet.**

This is what's known as a `Dust Attack` and there are many different types of dust attacks with different goals but the one that was described above is the version that we see people affected by the most.

Unfortunately, once these tokens are in your wallet, there is no way to get rid of them. The only option is to either remove all assets from that wallet address and throw that wallet away forever, or just leave them in your wallet and try to forget about them. **This also means that Unwanted is unable to perform transactions with these tokens.**

You must understand that **any interaction that you try to make with these tokens can cause serious loss of assets** and you must **NEVER touch these tokens if you see them randomly pop up in your wallet**.

Ultimately this means that Unwanted must be able to remove those tokens from the list of available tokens to perform transfers on. To do this, Unwanted implemented a **Scam Filter** that filters out tokens from the list of a user's available tokens.&#x20;

In addition, to combat the ever-growing list of scam tokens being deployed, Unwanted offers user submissions where users can submit potentially problematic assets for review. This will effectively create a growing user-driven database of problematic assets that should be filtered out automatically for the users of Unwanted.

### How to see what's filtered

Within each tool page, on the token type selector, there is a little :warning: symbol next to `Digital Tokens.` (NFT Filter will be released soon)

``![](<../.gitbook/assets/Screen Shot 2022-03-02 at 6.17.20 AM.png>)``

Clicking on this symbol opens a modal showing the tokens that were filtered out.

![](<../.gitbook/assets/Screen Shot 2022-03-28 at 9.24.33 AM.png>)

If you know of or suspect a NFT or Token to be a scam, un-transferrable, Honeypot or have high gas fees, you can submit the asset for review.&#x20;

Submitting a asset for review helps keep you and others safe by teaching Unwanted to filter out potentially problematic assets.\


![](<../.gitbook/assets/Screen Shot 2022-03-28 at 9.24.45 AM.png>)

