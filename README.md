# PowerToPeople

## Abstract:

> Our idea focuses on making the election process more transparent by monitoring usage of funds during election campaigns by  political parties, and ensuring that the the code of conduct is followed.

> The idea is to use a publicly accessible blockchain to create a system that monitors the inflow of funds from various   sources and the usage of the same by the political parties. The system includes a feedback loop where the various  stakeholders, i.e. the donors, the EC and opposition parties can choose to audit/question any and all expenditure of funds by the participating candidates. 

> Through this we also wish to make the pre-election phase more democratic by increasing the involvement of the voters.


## Participants:
+ `Voters`
+ `Funding organizations/supporters`
+ `Political Parties`
+ `Election Commission`
+ `Media organizations`

## Workflow:
### Here we describe the details of our idea and how it will work:
+ Every party starts with a ZERO amount transaction block from the EC.
+ Any party receiving funds from a voter or a funding organization has to declare the transaction on the blockchain through an official and verifiable document.
+ Any party spending any funds on campaigning activities like rallies, meetings etc. has to declare it through a document consisting of:
> + `Time and Date of declaration`
> + `Time and Date of the event` 
> + `Venue`
> + `Money Spent and payment method`
+ Smart contracts on the blockchain ensure no over-spending by the parties.
#### *Any interested entity can audit this aforementioned data and raise a flag with a proper explanation on any transaction it deems illicit. Any flagged transaction will then be reported to the EC, with the help of smart contracts, which can investigate it and take appropriate action.*

### What if a party doesn’t declare such transactions or activities?
+ The amount declared by the parties will be the official amount they own to spend in the campaigning activities. So if they don’t declare it or declare less amounts then officially they won’t have a (a lot) of money.
+ If they participate in any activities with exorbitant expenditure,like rallies etc.(and also not declare them) then anyone who witnesses such an activity can ask to verify whether it is declared or not. 
+ If not then they can also check if the party officially owns funds for such an activity or not. Also,they can flag the party's ZERO amount bloack and ask for an explanation.
This is the beauty of this system that the requirement of these declarations will give the voters transparency into the money involved in the elections and its effects.


Technologies:

Azure Blockchain Services
Integrate blockchain with Inter-planetary File System(IPFS) to facilitate storing the documents. We plan on using this as the size of the documents might be too large to store on a blockchain.
The information will be accessible on a web portal as well as mobile devices(through sms).
Purpose of giving information access through sms is to provide access to remote areas without internet connections by incorporating an offline blockchain through SMS services using idea in the lines of mCoin.


Why Blockchain?

Immutability: This essential feature of blockchain enables us to keep a permanent record of the transactions executed by the political parties under the code of conduct. Immutability works to our advantage here because we insist on keeping track of the funds every step of the way. This will make it extremely to carry out illegitimate activities using those funds as every penny has to be accounted for.
Transparency: This feature of a public blockchain will help the voters to exercise their right to information more easily and also help them know how their money is being used. This will also assure voters that their hard earned money is not used to buy votes or any other illicit activities.
