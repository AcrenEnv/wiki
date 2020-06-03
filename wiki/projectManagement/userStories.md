
## Administrator 

As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version  |	Acceptance criteria
------	|	------	|	------	|	------	|	------	 |	------	 |	------
Administrator	|	Off chain	|	channel funds	|	channel funds in a trustworthy way	|	get the donation to the appropiate actors	|	all	|	<ul><li>Incoming Banktransfers should be hold or automatically redirected to appropiate actor </li><li>Admin should see if any errors or unexpected behaviour occured</li></ul>
Administrator	|	SC	|	Managing EPMs	|	add EPMs	|	add EPMs which were previously proposed by experts 	|	1	|	<ul><li>Display form to add new EPM </li><li>Inserted EPM will be shown as EPM on platform</li></ul>
Administrator	|	SC	|	Managing EPMs	|	remove EPMs	|	remove EPMs are not usful or not fair	|	1	|	<ul><li>Display all EPMs of plattform </li><li>Selected EPMs will be removed from Platform </li></ul>
Administrator	|	SC	|	Managing experts	|	add experts	|	add reliable and trusthworthy experts to the expert group	|	1	|	<ul><li>Display all experts of platform </li><li>Display form to add expert </li><li>Inserted user will be a new expert of platform</li></ul>
Administrator	|	SC	|	Managing experts	|	remove experts	|	remove unreliable and non-trustworthy experts from the group	|	1	|	<ul><li>Display all experts of platform </li><li>Selected experts will be removed from platform</li></ul>
Administrator	|	SC	|	Managing farmers	|	validate farmers	|	only add farmers which can provide the EPM	|	all	|	<ul><li>Display farmers to validate </li><li>Display validation information of farmer </li><li>Admin can select to approve or reject validation</li><li>Farmer will be informed of validation result</li><li>Approved farmers will be shown on plattform and able to create EPMs </li></ul>
Administrator	|	SC	|	Managing farmers	|	add farmers	|	add validated farmers to the plattform, so they can offer EPM	|	all	|	
Administrator	|	SC	|	Managing farmers	|	remove farmers	|	remove non-trustworthy farmers from the plattform	|	1	|	<ul><li>Display all farmers of plattform </li><li>Selected farmers will be removed from Platform</li></ul>
Administrator	|	SC	|	Managing farmers	|	add validator	|	add trusted validators to the plattform, so they can validate EPM	|	1	|	<ul><li>Display all validators of plattform </li><li>Display form to add new Expert </li><li>Added users will be validators</li></ul>
Administrator	|	SC	|	Managing farmers	|	remove validator	|	remove non-trustworthy validators from the plattform	|	1	|	<ul><li>Display all validators of plattform</li><li>Selected validators will be removed from Platform</li></ul>
Administrator	|	SC	|	Platform	|	update the plattform	|	add, remove or update processes which are not working as intended or could be working better	|	1	|	Admin can change Smart-Contract-Address of Platform
Administrator	|	SC	|	Review Donation Process 	|	review full donation processes	|	check how the system can be improved	|	1	|	<ul><li>Display all donations of platform</li><li>Admin is able to select specific donations</li><li>Admin is able to select multiple donations specified by properties</li></ul>
Administrator	|	SC	|	Review Proofs	|	review selected proofs	|	check whether selected proof-system works  	|	1	|	<ul><li>Admin is able to specify a specific donation</li><li>Display whole donation process</li></ul>
Administrator	|	SC	|	Acren token	|	update the bonding curve in a transparent way	|	address security concerns	|	1	|	 Admin can change Smart-Contract-Address of Bonding Curve
Administrator	|	SC	|	Acren token	|	set minimum funding pool ratio for investors	|	to force investors to donate part of the investment	|	1	|	<ul><li>Display current minimum and maximum funding pool ratio</li><li>Update minimum and maximum funding pool ratio </li></ul>
Administrator	|	SC	|	Acren token	|	update default reserve and funding pool ratio	|	address security concerns and improve efficency 	|	1	|	<ul><li>Display current default funding pool/investion ratio</li><li>Update default funding pool/investion ratio</li></ul>
Administrator	|	SC	|	Acren token	|	change action fee (mint, burn token)	|	address security concerns and improve efficency 	|	1	|	<ul><li>Display current actions and their fees </li><li>Update fees of actions</li></ul>
Administrator	|	Mobile App	|	Mobile App	|	temporarily suspend service	|	fix bugs and update the system	|	1	|	 Set app system temporarily down
Administrator	|	Website	|	Website	|	temporarily suspend service	|	fix bugs and update the system	|	1	|	 Set website system temporarily down



## Farmer  
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version  |	Acceptance criteria
------	|	------	|	------	|	------	|	------	 |	------	 |	------
Farmers	|	SC	|	Creates Proof	|	create a proof 	|	receive funds for implementing	|	all	|	<ul><li>Display proof options</li><li>Add proof</li><li>Display status of validation</li></ul>
Farmers	|	SC	|	Implements EPM	|	provide an implementation status of the EPMs	|	have an overview for myself and to provide it to donators	|	all	|	<ul><li>Display active EPMs of farmer</li><li>Update status of implementation</li></ul>
Farmers	|	SC	|	Offers EPM	|	offer configured(set price, timerange, ..) EPM	|	be able to receive funding for doing work	|	all	|	<ul><li>Display active EPMs of farmer</li><li>Display possible EPMs with costs and other properties</li><li>Insert properties of selected EPM</li><li>Show implementation and proof steps of EPMs</li></ul>
Farmers	|	SC	|	Offers EPM	|	have an overview of EPMs to implement	|	know what to implement	|	all	|	<ul><li>Display active EPMs</li><li> Display implementation and proof steps of EPMs</li></ul>
Farmers	|	SC	|	Offers EPM	|	have an overview how much money got allocated for the different EPMS	|	have an financial overview of how much money I expect to get	|	all	|	Display active EPMs with already funded amount
Farmers	|	Off Chain	|	Offers EPM	|	Receive Donation in DAI, EURO or AcrenToken	|	to cover expenses for the implementation of EPM	|	all	|	<ul><li>Select how to receive payment</li><li>Insert payment information for payment</li></ul>

## Contributor 
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version  |	Acceptance criteria
------	|	------	|	------	|	------	|	------	 |	------	 |	------
Contributor	|	SC	|	Selecting and Configuring Donation	|	select "smart donation"	|	easily donate without needing to select an EPM	|	all	|	<ul><li>Display donation/investment ratio</li><li>Editable donation/investment ratio within given bounds</li><li>Select donation topic</li><li>Exchange donation to DAI</li><li>Forward donated DAI to a joint funding pool</li></ul>	
Contributor	|	SC	|	Selecting and Configuring Donation	|	want to donate anonymously	|	keep my privacy	|	2	|		
Contributor	|	SC	|	Selecting and Configuring Invest	|	select "smart invest"	|	easily invest in AcrenToken without needing to select an EPM	|	2	|		
Contributor	|	SC	|	Selecting and Configuring Donation	|	select a specific EPM from a specific farmer for the donation	|	be sure that I only support EPMs and Farmers that I want to receive support	|	all	|	<ul><li>Display all open EPMs provided by farmers</li><li>Order EPMs by different properties</li><li>View information about selected EPM</li><li>Select EPM for donation</li></ul>	
Contributor	|	SC	|	Selecting and Configuring Donation	|	select an donation amount	|	chose how much i want to spend	|	all	|	<ul><li>Input donation amount</li><li>Display donation-investemt ration</li><li>Change donation amount</li></ul>	
Contributor	|	SC	|	Selecting and Configuring Donation	|	select distribution to donation / token buy	|	chose how much i want to donate and invest	|	all	|	<ul><li>Display donation amount</li><li>Change donation amount</li><li>Display donation-investment ratio</li><li>Change donation/investment ratio within given bounds</li></ul>	
Contributor	|	Off Chain	|	Send Donation	|	send transaction through Bank-Transfer	|	be able to support withought haven to adopt a new System	|	alle	|	<ul><li>Display bank information and amount</li><li>Approve completed banktransfer</li><li>Display next steps</li><li>Display approx. Transfer time</li></ul>	
Contributor	|	Off Chain	|	Send Donation	|	send transaction through CreditCard and Paypal	|	be able to support withought haven to adopt a new System	|	2	|		
Contributor	|	SC	|	Send Donation	|	send transaction through Ethereum/Dai token	|	be able to support with crypto tokens	|	all	|	<ul><li>Display Ethereum address, amount and time to complete</li><li>Display transaction status</li><li>Display success or failure</li><li>Display invoice</li></ul>	
Contributor	|	SC	|	Send Donation	|	send transaction through crypto token	|	be able to support with crypto tokens	|	2	|	
Contributor	|	SC	|	Send Donation	|	send transactions which are pure donations withought having to register on any app or website	|	send a donation with less time consumption	|	all	|		
Contributor	|	SC	|	Send Donation	|	Receive an invoice	|	to use it in my annual tax declaration 	|	1	|	<ul><li>Display all donations with donation status</li><li>Download selected donation</li></ul>	
Contributor	|	SC	|	Acren token	|	Receive the bought acren token	|	to get the acren token	|	all	|	<ul><li>Display amount of AcrenToken</li><li>Display AcrenToken actions (burn)</li><li>Display all specifics of order</li></ul>	
Contributor	|	SC	|	Acren token	|	burn the owned acren token and receive DAI	|	to monetize the acren token	|	all	|	<ul><li>Display amount of AcrenToken</li><li>Specify amount of AcrenToken to burn</li><li>Burn selected amount of token</li><li>Add receive Address for DAI</li><li>Display status of burn</li></ul>	
Contributor	|	SC	|	Acren token	|	get information about the acren token	|	get informed and support the decisions about buying/burn acren token	|	all	|	Display detailed information about AcrenToken	
Contributor	|	SC	|	Review Donation Process	|	Review how the farmer used the donation	|	be sure that my donation is used only for eniromental protection	|	all	|	<ul><li>Display all donations of contributor</li><li>Order donations of contributor by properties</li><li>Diplay all properties of selected donation</li><li>Display status of donations</li></ul>	
Contributor	|	SC	|	Review Donation Process	|	Review the whole cash flow of my donation	|	be sure that most of my donation is used for the selected EPM	|	2	|		
Contributor	|	SC	|	Review Donation Process	|	receive a certificate 	|	be able to show others that I am activly engaging in envirmental Protection	|	2	|		
Contributor	|	SC	|	Review Donation Process	|	write messages to the farmer	|	be in contact with the person who implements the EPM	|	2	|		
Contributor	|	SC	|	Review Donation Process	|	receive a acknowledgement by the farmer after completion of EPM	|	stay in contact with a beneficary of the donation	|	2	|		
Contributor	|	SC	|	Review Proofs	|	see a proof created by farmers	|	validate on my own if the farmer really implemented the EPM	|	2	|		
Contributor	|	SC	|	Review Proofs	|	see validators and validation log	|	be able to be sure that the farmer really implemented the EPM	|	2	|		
Contributor	|	SC	|	Review Proofs	|	see if the validators approved the proof	|	know if the donation process has been a success	|	all	|	<ul><li>Display validation status of all donations</li><li>Display validation proof and properties of selected validation process</li></ul>	


## Validator
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version  |	Acceptance criteria
------	|	------	|	------	|	------	|	------	 |	------	 |	------
Validator	|	SC	|	Validate Proof	|	receive instructions for validation proof 	|	be able to know how to validate proofs	|	2	|	
Validator	|	SC	|	Validate Proof	|	receive proofs	|	which I can prove	|	all	|	<ul><li>Display all open validation processes with price</li><li>Display open validation process</li><li>Display notification of incoming proof</li></ul>
Validator	|	Off Chain	|	Validate Proof	|	receive payment in AcrenToken or DAI	|	to cover expenses for validating proof	|	all	|	<ul><li>Display closed validation and payment</li><li>Display amount of received token for validating</li><li>Display action for token </li></ul>
Validator	|	SC	|	Validate Proof	|	stake money	|	be able to validate proof	|	2	|	
Validator	|	SC	|	Validate Proof	|	review validation results	|	be able to determine if my validation was correct	|	2	|	



## Experts
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version  |	Acceptance criteria
------	|	------	|	------	|	------	|	------	 |	------	 |	------
Experts	|	SC	|	Creates EPM Proposal	|	set the basic configuration (e.g.  description, process, price range, proof-system)	|	accept only fair EPMs	|	2	|	
Experts	|	SC	|	Creates EPM Proposal	|	create a EPM Proposual with a set configuration set	|	propose good EPMs to implement	|	2	|	
Experts		SC	|	ExpertPayment 	|	receive a resonable payment in Token	|	to cover the expenses of the tasks	|	all	|	<ul><li>Display all validations of validators</li><li>Display all open validations</li><li>Display status of validations</li><li>Display amount of validations</li><li>Display validation actions</li></ul>
Experts	|	Off Chain	|	ExpertPayment 	|	receive a resonable payment in EUR	|	to cover the expenses of the tasks	|	2	|	
Experts	|	SC	|	Reviews EPMs	|	discuss with other experts which EPMs should be implemented or removed	|	accept only EPMs which are beneifical for enviromental protection	|	2	|	
Experts	|	SC	|	Reviews EPMs	|	review EPMs 	|	check whether configurations and EPMs are still useful und fair	|	all	|	<ul><li>Display all EPMs</li><li>Display selected donation process</li></ul>
Experts	|	SC	|	Reviews EPMs	|	review selected proofs	|	check whether selected proof-system works  	|	all	|	<ul><li>Display all validations</li><li>show donation and validation process of selected validation</li></ul>
Experts	|	SC	|	Reviews EPMs	|	review full donation processes	|	check whether validators and proof-system are intact	|	all	|	<ul><li>Display all Donations</li><li>Display process of selected donation</li></ul>
