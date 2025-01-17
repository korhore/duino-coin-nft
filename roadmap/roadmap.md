# Roadmap for Open Trade with Categosized Smart Contracts
## Inspiration
Inspiration to innovate [smart contracts](https://en.wikipedia.org/wiki/Smart_contract) for real physical products comes of current ongoing Russian war against Ukraina, because innocent people are dying there just now and this can be one way to say to Putin, that he is doing wrong things and we don't accept it and that we want to help Ukraina people. But even if Ukraina-case is very very important for us, if we want keep as human people, one very bad thing can also lead good things.

Nothing like Open Trade with Categosized Smart Contracts has not even been possible before. If we can make full-version of categorized smart contracts, it is possible to check history of a single product of what components it consists and do they fullfill same category contract, than main product clains to fullfill.

Also, making same products's component same smart contract history data data available of sellers and buyers if, they also fullfill smart contract rules or not, real controll to real data of how products are made can be available as component level. Even if component is dismanted from one old product and sold to someone, who installs that component to his/her product, new one or old one, also that components history can be found, when component is sold with it's smart contract. So business possibities for this kind smart contract -usage seems to be very promising if you are going to save the world or even if your are not going to do it.
 
## Steps
### Categosized Smart Contracts
Basic idea is based on Categirized Contracts
#### Category
Category for a component can be based on conditions with a component has build, traded or owned. One example is Russia ban [Russia sanctions list: What the west imposed over the Ukraine invasion](https://www.ft.com/content/6f3ce193-ab7d-4449-ac1b-751d49b1aaf8) . This category may be defined for instance so, that component has not been made is Russia, not a company that is owned by any people that are citizens of Russia directly or indirectly, preventing use of bullvans.

Example of conditions contract may be, that conditions of the workers fullfill some category difined for instance [ILO C029 - Forced Labour Convention, 1930 (No. 29)](https://www.ilo.org/dyn/normlex/en/f?p=NORMLEXPUB:12100:0::NO::P12100_ILO_CODE:C029).

Very popular category is nowdays climate carbon neutral, for instance for [Design Buildings](https://www.designingbuildings.co.uk/wiki/Carbon_neutral_contract). This contract is easy to be extended to any area of the business products.

One category will be of how deep level information of smart contracts of products producing phases and components customer can get, is it only producers announcement or does it go higher to the deepest level, where same contracts information can be got also for all services and subcomponents that are used in the product. If implementaion is made so, that customers can confirm or deny relationship of product and category we can implement reliability.

#### Categorized Contract
Categorized Contract is concrete contract under it's category. Examples of Categorized Contract can be above examples, they are examples of both 'Category' and  'Categorized Contracts'.

### Contract Makers
Basically contract is one-sided. Those are promises to follow those category contracts rules. Producer companies make those promiseses of their products, components or services. Product consists on many components and services of many companies. Chain goes from component makers to product maker to shops, where customer can buy those products.

In this transfer chain component is always holded by one actor. We can identify two type component holder change dependent of that, is component buyed to not, is ownership changed or not. Those actors have made categorized contracts how they behave with that component. We can identify assignment between component, actor and contract.

If we look situation in the shop, customer can find out a product that consists of components and services. Even the shop selling assings a service to a product what it is selling and have made promises how it works. Customer can find out products all components and services and get information of all categorized contract made or not made.

On selling phase customer can choose a produuct by a categorized contract and if product does not fullfil this contracts by some component or service, customer can see what is wrong with that product or simply get a list of other products that fullfill the contract wanted. We can find out that with this logic we have made a system, where customer can choose his/her values and put his/her money to talk how this world should act.

### What this projects will sell?

This project's product will be product sticker that includes a QR-code, which has http-link to this single products Smart contrats infiormation. From that customer can check if a product fullfilss smart contracts he/she wants. Look car componts, cellular phone boxes etc. All products have stickers, where are many kind of id-information. This Categorized Contracts sticker is one more. With that sticker product makers can get get goodwill for their products, because they act responsible.

### Open Trade
Because anyone can check the product or product batch that contains the QR code, trading will become open. We cannot assume that this idea will ever be used in all commerce, but it is possible that it will eventually become mainstream.

### Distributed Architecture
Plan is make this app to work also if users in the internet don't get connection to each other any moe freely, but it is restricted. We use distributed architecture, meaning that data is divaded in all devices and all devices can connect each other to get data from others. To get started we use one named server, that will hold data of known categies, smart contracts, products, etc. and also devices that real users use with this application. Device information is simple, so it is not needed to get this information from basic named server, but can be shatred other ways too, so this systerm can run also in the closed island of the internet.
### Book Keeping
#### Items identified
We can find out, that all items can have same structure and only it's role differs. Role can be actor or component and with those roles we can build company, department of a company, product shat consists of components, component, customer, group of customers, group of customer groups etc. Categorys are are Items descripted below with a role 'Smart Contract' as highest level without owner. 'Smart Contract's are lowest level of this chain, concrete contracts.
##### Smart Contract
This is an Item descripted below with a role 'Smart Contract'
##### Device
This is an Item descripted below with a role 'Device'. No other device in collected or saved, than neede fo cennections. We need only IP-addresses. There can be volunteer servers and customer devices, so we ,ust study, if we ass parameters 'pewrmanent' as opposite of smart phone, which IP changes very often.

##### Assignment/Association
Link between 2 Items whith features. For instance is link is between a component and smart contract, this will include True or False indicator and also link to crteator. This neans that this creator has identifies if this compunents fullfills smart contract rules or not.
* id
* date
* item id
* otherItem id
* creator id
* isTrue
##### Item
Item is iterative with roles, so item can be basic component that is a part of a product; component, that is not a part of a product yet; a product that contais components; company or department of company, customer or group of customers; category or smart contract under a category.
* id
* date
* name
* description
* url
* role (company, department, component, product, customer, customer group, smart contract, device)
* set of assigned items that are assembled to this item, this can be also ownership, if role role is company, customer
* set of assigned items which this item is part of
* set of assigned items this item holds. Valid for company that sells services like transport. Transport can also be a component. Because ownership is not changed ith these kind operatoins, we need onother set than obove one. 
* set of assigned items which this item is holded of
* set of assigned smart contract this item fullfills or does not fullfill (roles company, department) or what smart contract role customer wan't to be fullfilled (roles customer, group of customers).


#### Transactions identified
##### Create, modify delete Item
* id
* date
* transaction type (create, modify, delete )
* item

##### assign or deassign Item
Some deassings are reasonable, but some are not, depending on Itrm roles. This need a study.

* id
* date
* actor, who makes thos assignemt, item with roles company (department), customer(customer group)
* assign or deassign
* assignement type(part to, part of, holded to, holded of, smart contract)
* item to be assigned/deassigned
* otherItem to be assigned/deassigned
* item id,
* otherItem id
* True/False is this assignment True. 

### Implementation
#### Demo
Maybe demo with python3 is the easiest way.
#### Final Implementaion
This should work with smart phones. Maybe java-implementation for clients is needed. Probable we need server side.


### Book keeping
There are many possibilities. We can even use pure files almost for a demo, datata base aor block chain. Maybe this is list a roadmap. Below is some study points for Duino, because it is chep coin, but maybe study for it should be with a very low priority.

#### Block-Chain
##### Study Block_Chains
##### Study Duino as Block_Chain
Read-only logging is basic feature of a block-chain, but is Duino a block-chain? If yes, how we con log with Duino? If not, is it possible to wrap Duino-Coin to some block-chain?

Suggstion by bobyblobfish#1566: "... make a duino nft on polygon blockchain, and make an official section on the duinocoin website that lets you buy the nfts with duco, but actually it buys it with polygon by exchanging the duino to polygon through the website. Now we have duino nfts that  are decentralized, and also doesn’t force anyone to directly use anything besides duino to buy it." In this use case we should put "smart contract" on a polygon blockchain to keep consepts clear, because it seems that nft is always asociated to some digital thing, but here we have smart contract, which is digital itself, but it is associated to a flysical thing like a component of a product.

Technical link to [Setting up Metamask for Polygon (Matic Network)](https://medium.com/stakingbits/setting-up-metamask-for-polygon-matic-network-838058f6d844)

Your need wallet and Secret Recovery Phrase. Don't yet know if Duino-Coin Web wallet can be used. In this study I created a new wallet and Secret Recovery Phrase. After creating wallet with a phase, it if I try to add network
- Network Name
- New RPC URL
- Chain ID
- Currency Symbol(Optional)
- Block Explorer URL(Optional)

For Etherium these are
- Network Name 			Ethereum Mainnet
- New RPC URL  			***
- Chain ID				1
- Currency Symbol(Optional)		ETH
- Block Explorer URL(Optional)	https://etherscan.io

For tests can be used for instance
- Localhost 8545
- Ropsten Test Network

To continue study, maybe Ropsten Test Network is best.

- Network Name				Ropsten Test Network
- New RPC URL				***
- Chain ID				3	
- Currency Symbol(Optional) 		ETH
- Block Explorer URL(Optional)	https://ropsten.etherscan.io

Hmm.. this is already included, because I can't add it

Currency can be for istance bitcoin, dollar, but no DUCO.


### Smart Contract
#### Study Smart Contracts
How to deploy smart contract? You can use ethereum as example, but ethereum is not cheap main think to study is we can lof with Duino, how we deploy smart contyracts with Duino?

### GPL
#### Study GPL
Study GPL as a purpose to define Smart Contract same kind as GPL so, that contract maker promises publish all components  he/her has used as a list with Smart Contract -information needed for each. Note that product itself will not be under GPL, but we only study GPL what way like in programs business if we use GPL at code level, which means that we can freely use GPL licenced code in our own code, but after doing so, we must also publish all code we have written to make application under GPL. Logic with items fullfilling smarft agreement will be that kind, that if one subitem will not fullfill a smart contract, then main product will not fullfill also, even if some other subitems will fullfill the smart contract.
