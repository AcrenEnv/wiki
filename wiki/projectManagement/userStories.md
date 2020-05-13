## Administrator 

As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version
------	|	------	|	------	|	------	|	------	 |	------
Administrator	|	Off chain	|	channel funds	|	channel funds in a trustworthy way	|	get the donation to the appropiate actors	|	all
Administrator	|	SC	|	Managing EPMs	|	add EPMs	|	add EPMs which were previously proposed by experts 	|	1
Administrator	|	SC	|	Managing EPMs	|	remove EPMs	|	remove EPMs are not usful or not fair	|	1
Administrator	|	SC	|	Managing experts	|	add experts	|	add reliable and trusthworthy experts to the expert group	|	1
Administrator	|	SC	|	Managing experts	|	remove experts	|	remove unreliable and non-trustworthy experts from the group	|	1
Administrator	|	SC	|	Managing farmers	|	validate farmers	|	only add farmers which can provide the EPM	|	all
Administrator	|	SC	|	Managing farmers	|	add farmers	|	add validated farmers to the plattform, so they can offer EPM	|	all
Administrator	|	SC	|	Managing farmers	|	remove farmers	|	remove non-trustworthy farmers from the plattform	|	1
Administrator	|	SC	|	Managing farmers	|	add validator	|	add trusted validators to the plattform, so they can validate EPM	|	1
Administrator	|	SC	|	Managing farmers	|	remove validator	|	remove non-trustworthy validators from the plattform	|	1
Administrator	|	SC	|	Platform	|	update the plattform	|	add, remove or update processes which are not working as intended or could be working better	|	1
Administrator	|	SC	|	Review Donation Process 	|	review full donation processes	|	check how the system can be improved	|	1
Administrator	|	SC	|	Review Proofs	|	review selected proofs	|	check whether selected proof-system works  	|	1
Administrator	|	SC	|	Acren token	|	update the bonding curve in a transparent way	|	address security concerns	|	1
Administrator	|	SC	|	Acren token	|	set minimum funding pool ratio for investors	|	to force investors to donate part of the investment	|	1
Administrator	|	SC	|	Acren token	|	update reserve and funding pool ratio	|	address security concerns and improve efficency 	|	1
Administrator	|	SC	|	Acren token	|	change action fee (mint, burn token)	|	address security concerns and improve efficency 	|	1
Administrator	|	Mobile App	|	Mobile App	|	temporarily suspend service	|	fix bugs and update the system	|	1
Administrator	|	Mobile App	|	Mobile App	|	Update the mobile app in a transparent way without harming trustlessness	|	improve usability of the system	|	1
Administrator	|	Website	|	Website	|	temporarily suspend service	|	fix bugs and update the system	|	1
Administrator	|	Website	|	Website	|	Update the website in a transparent way without harming trustlessnes	|	improve usability of the system	|	1




## Farmer  
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version
------	|	------	|	------	|	------	|	------	 |	------
Farmers	|	SC	|	Creates Proof	|	create a proof 	|	receive funds for implementing	|	all
Farmers	|	SC	|	Implements EPM	|	provide an implementation status of the EPMs	|	have an overview for myself and to provide it to donators	|	all
Farmers	|	SC	|	Offers EPM	|	offer configured(set price, timerange, ..) EPM	|	be able to receive funding for doing work	|	all
Farmers	|	SC	|	Offers EPM	|	have an overview of EPMs to implement	|	know what to implement	|	all
Farmers	|	SC	|	Offers EPM	|	have an overview how much money got allocated for the different EPMS	|	have an financial overview of how much money I expect to get	|	all
Farmers	|	Off Chain	|	Offers EPM	|	Receive Donation	|	to cover expenses for the implementation of EPM	|	all

## Donors 
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version
------	|	------	|	------	|	------	|	------	 |	------
Donor	|	SC	|	Selecting and Configuring Donation	|	select "smart donation"	|	easily donate without needing to select an EPM	|	all
Donor	|	SC	|	Review Donation Process	|	Review how the farmer used the donation	|	be sure that my donation is used only for eniromental protection	|	all
Donor	|	SC	|	Review Donation Process	|	Review the whole cash flow of my donation	|	be sure that most of my donation is used for the selected EPM	|	all
Donor	|	SC	|	Review Donation Process	|	receive a certificate 	|	be able to show others that I am activly engaging in envirmental Protection	|	all
Donor	|	SC	|	Review Donation Process	|	write messages to the farmer	|	be in contact with the person who implements the EPM	|	all
Donor	|	SC	|	Review Donation Process	|	receive a acknowledgement by the farmer after completion of EPM	|	stay in contact with a beneficary of the donation	|	all
Donor	|	SC	|	Review Proofs	|	see a proof created by farmers	|	validate on my own if the farmer really implemented the EPM	|	all
Donor	|	SC	|	Review Proofs	|	see validators and validation log	|	be able to be sure that the farmer really implemented the EPM	|	all
Donor	|	SC	|	Review Proofs	|	see if the validators approved the proof	|	know if the donation process has been a success	|	all


## Investors 
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version
------	|	------	|	------	|	------	|	------	 |	------
Investor	|	SC	|	Selecting and Configuring Invest	|	select "smart invest"	|	easily invest in AcrenToken without needing to select an EPM	|	all



## Donors & Investors
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version
------	|	------	|	------	|	------	|	------	 |	------
Donor / Investor	|	SC	|	Selecting and Configuring Donation	|	select a specific EPM from a specific  farmer for the donation	|	be sure that I only support EPMs and Farmers that I want to receive support	|	all
Donor / Investor	|	SC	|	Selecting and Configuring Donation	|	select an donation amount	|	chose how much i want to spend	|	all
Donor / Investor	|	SC	|	Selecting and Configuring Donation	|	select distribution to donation / token buy	|	chose how much i want to donate and invest	|	all
Donor / Investor	|	Off Chain	|	Send Donation	|	send transaction through Bank-Transfer, CreditCard or Paypal	|	be able to support withought haven to adopt a new System	|	1
Donor / Investor	|	SC	|	Send Donation	|	send transaction through crypto token	|	be able to support with crypto tokens	|	all
Donor / Investor	|	SC	|	Send Donation	|	send transactions which are pure donations withought having to register on any app or website	|	send a donation with less time consumption	|	all
Donor / Investor	|	SC	|	Send Donation	|	Receive an invoice	|	to use it in my annual tax declaration 	|	1
Donor / Investor	|	SC	|	Acren token	|	Receive the bought acren token	|	to get the acren token	|	 
Donor / Investor	|	SC	|	Acren token	|	burn the owned acren token and receive DAI	|	to monetize the acren token	|	all
Donor / Investor	|	SC	|	Acren token	|	get information about the acren token	|	get informed and support the decisions about buying/burn acren token	|	all

## Validator
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version
------	|	------	|	------	|	------	|	------	 |	------
Validator	|	SC	|	Validate Proof	|	receive instructions for validation proof 	|	be able to know how to validate proofs	|	all
Validator	|	SC	|	Validate Proof	|	receive proofs	|	which I can prove	|	all
Validator	|	Off Chain	|	Validate Proof	|	receive payment	|	to cover expenses for validating proof	|	all
Validator	|	SC	|	Validate Proof	|	stake money	|	be able to validate proof	|	all
Validator	|	SC	|	Validate Proof	|	review validation results	|	be able to determine if my validation was correct	|	all



## Experts
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version
------	|	------	|	------	|	------	|	------	 |	------
Experts	|	SC	|	Creates EPM Proposal	|	set the basic configuration (e.g.  description, process, price range, proof-system)	|	accept only fair EPMs	|	all
Experts	|	SC	|	Creates EPM Proposal	|	create a EPM Proposual with a set configuration set	|	propose good EPMs to implement	|	all
Experts	|	Off Chain	|	ExpertPayment 	|	receive a resonable payment in EUR	|	to cover the expenses of the tasks	|	all
Experts	|	SC	|	Reviews EPMs	|	discuss with other experts which EPMs should be implemented or removed	|	accept only EPMs which are beneifical for enviromental protection	|	all
Experts	|	SC	|	Reviews EPMs	|	review EPMs 	|	check whether configurations and EPMs are still useful und fair	|	all
Experts	|	SC	|	Reviews EPMs	|	review selected proofs	|	check whether selected proof-system works  	|	all
Experts	|	SC	|	Reviews EPMs	|	review full donation processes	|	check whether validators and proof-system are intact	|	all

