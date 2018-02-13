
*Draft Whitepaper proceeed with caution*

# What is this useful for ?

Borrowing Cryptocurrencies to gain quick access to additional liquid when you don't have any extra money. It's helpful in following cases

 - During Market Crash or dips you can buy additional tokens 
 - Borrowing Tokens to participate in ICO
 - Gain a steady interest by lending out tokens**

It also supports external assets.
** If borrower doesnt defaults

# How it works

 Requesters create Borrow Requests . They send Tokens to the smart contracts and Lock them.
 ![](https://i.imgur.com/WJhlzME.png)
 After successfully locking tokens the requests are shown in market.
 
 Lenders Can Accept any request then send tokens to the smart contracts and lock them.
 
Once funds are locked the timer is started and borrower has to withdraw and return tokens within the given timeframe. On failing to do so Lender has choice to either hopefully wait for his funds to arrive or withdraw the collateral tokens.
On successfully returning lended tokens with interest all tokens are automatically returned to borrowers and lenders.

Images showing a Loan being Completed and Defaulted 
![](https://i.imgur.com/4kk1cxr.png)

Borrower Defaulted
![](https://i.imgur.com/kkAXqIp.png)

# Reputations
On sucessfull completion of loans you gain reputation and lose on unsucessfull loans.
The reputation points depends on variety of factors like volume, time, quantity, consistency, interests paid, completion before due date etc.

# External Assets**

It can support any cryptocurrency or asset that does not belongs to ethereum.

**Currently we have added support for [NANO](https://github.com/clemahieu/raiblocks). Looking to support more.

# Governance

External assets are outside of etheruem therefore its doesnt follows the consensus of ethereum. Therefore you have to go with trusted people or group of people to determine the outcome of event.

Governors needs to stake NanoLend coins to govern. A malicious governor will lose all his coins and reputation. Therefore its in its best interest to not do so.


*SIMPLE EXPLAINATION*
*This scenario only for external assets. ethereum tokens will require no governance as they are inside the ecosystem*
Person **A** sends Asset **A** to SafeBox **A** and clone of **A** to smart contract.

Person **B** **C** **D**  can see inside SafeBox but cannot take things from SafeBox. They can vote the smart contract if Asset **A** is inside SafeBox **A**. Once enough confirmation smart contract can be locked with clone of **A**. 

![](https://i.imgur.com/T4nsr2a.png)

**Note**: *The voting will happen automatically and thus the data of SafeBox will be same for every person. Only way anyone will vote wrong will be a malicious actor. 
And there will be no intent of any malicious actor since funds can only be withdrawn to borrowers and lenders . And malicious actors will risk staked coins, reputations and waste gas with no gains. They can  only create disturbance in network by not letting funds getting locked if succesful.* 





