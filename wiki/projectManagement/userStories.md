
## Administrator 

As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version  |	Acceptance criteria
------	|	------	|	------	|	------	|	------	 |	------	 |	------
Administrator	|	Off chain	|	channel funds	|	channel funds in a trustworthy way	|	get the donation to the appropiate actors	|	all	|	"1. Incoming Banktransfers should be hold or automatically redirected to appropiate actor 2. Admin should see if any errors or unexpected behaviour occured"
Administrator	|	SC	|	Managing EPMs	|	add EPMs	|	add EPMs which were previously proposed by experts 	|	1	|	"1. Display form to add new EPM 2. Inserted EPM will be shown as EPM on platform"
Administrator	|	SC	|	Managing EPMs	|	remove EPMs	|	remove EPMs are not usful or not fair	|	1	|	"1. Display all EPMs of plattform 2. Selected EPMs will be removed from Platform "
Administrator	|	SC	|	Managing experts	|	add experts	|	add reliable and trusthworthy experts to the expert group	|	1	|	"1. Display all experts of platform 2. Display form to add expert 3. Inserted user will be a new expert of platform"
Administrator	|	SC	|	Managing experts	|	remove experts	|	remove unreliable and non-trustworthy experts from the group	|	1	|	"1. Display all experts of platform 2. Selected experts will be removed from platform"
Administrator	|	SC	|	Managing farmers	|	validate farmers	|	only add farmers which can provide the EPM	|	all	|	"1. Display farmers to validate 2. Display validation information of farmer 3. Admin can select to approve or reject validation 4. Farmer will be informed of validation result 5. Approved farmers will be shown on plattform and able to create EPMs "
Administrator	|	SC	|	Managing farmers	|	add farmers	|	add validated farmers to the plattform, so they can offer EPM	|	all	|	
Administrator	|	SC	|	Managing farmers	|	remove farmers	|	remove non-trustworthy farmers from the plattform	|	1	|	"1. Display all farmers of plattform 2. Selected farmers will be removed from Platform"
Administrator	|	SC	|	Managing farmers	|	add validator	|	add trusted validators to the plattform, so they can validate EPM	|	1	|	"1. Display all validators of plattform 2. Display form to add new Expert 3. Added users will be validators"
Administrator	|	SC	|	Managing farmers	|	remove validator	|	remove non-trustworthy validators from the plattform	|	1	|	"1. Display all validators of plattform2. Selected validators will be removed from Platform"
Administrator	|	SC	|	Platform	|	update the plattform	|	add, remove or update processes which are not working as intended or could be working better	|	1	|	1. Admin can change Smart-Contract-Address of Platform
Administrator	|	SC	|	Review Donation Process 	|	review full donation processes	|	check how the system can be improved	|	1	|	"1. Display all donations of platform2. Admin is able to select specific donations2. Admin is able to select multiple donations specified by properties"
Administrator	|	SC	|	Review Proofs	|	review selected proofs	|	check whether selected proof-system works  	|	1	|	"1. Admin is able to specify a specific donation2. Display whole donation process"
Administrator	|	SC	|	Acren token	|	update the bonding curve in a transparent way	|	address security concerns	|	1	|	1. Admin can change Smart-Contract-Address of Bonding Curve
Administrator	|	SC	|	Acren token	|	set minimum funding pool ratio for investors	|	to force investors to donate part of the investment	|	1	|	"1. Display current minimum and maximum funding pool ratio2. Update minimum and maximum funding pool ratio "
Administrator	|	SC	|	Acren token	|	update default reserve and funding pool ratio	|	address security concerns and improve efficency 	|	1	|	"1. Display current default funding pool/investion ratio2. Update default funding pool/investion ratio"
Administrator	|	SC	|	Acren token	|	change action fee (mint, burn token)	|	address security concerns and improve efficency 	|	1	|	"1. Display current actions and their fees 2. Update fees of actions"
Administrator	|	Mobile App	|	Mobile App	|	temporarily suspend service	|	fix bugs and update the system	|	1	|	1. Set app system temporarily down
Administrator	|	Website	|	Website	|	temporarily suspend service	|	fix bugs and update the system	|	1	|	1. Set website system temporarily down



## Farmer  
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version  |	Acceptance criteria
------	|	------	|	------	|	------	|	------	 |	------	 |	------
Farmers	|	SC	|	Creates Proof	|	create a proof 	|	receive funds for implementing	|	all	|	"1. Display proof options2. Add proof3. Display status of validation"
Farmers	|	SC	|	Implements EPM	|	provide an implementation status of the EPMs	|	have an overview for myself and to provide it to donators	|	all	|	"1. Show active EPMs of farmer2. Update status of implementation"
Farmers	|	SC	|	Offers EPM	|	offer configured(set price, timerange, ..) EPM	|	be able to receive funding for doing work	|	all	|	"1. Show active EPMs of farmer2. Show possible EPMs with costs and other properties3. Insert properties of selected EPM4. Show implementation and proof steps of EPMs"
Farmers	|	SC	|	Offers EPM	|	have an overview of EPMs to implement	|	know what to implement	|	all	|	"1. Show active EPMs2 . Show implementation and proof steps of EPMs"
Farmers	|	SC	|	Offers EPM	|	have an overview how much money got allocated for the different EPMS	|	have an financial overview of how much money I expect to get	|	all	|	1. Show active EPMs with already funded amount
Farmers	|	Off Chain	|	Offers EPM	|	Receive Donation in DAI, EURO or AcrenToken	|	to cover expenses for the implementation of EPM	|	all	|	"1. Select how to receive payment2. Insert payment information for payment"

## Contributor 
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version  |	Acceptance criteria
------	|	------	|	------	|	------	|	------	 |	------	 |	------
Contributor	|	SC	|	Selecting and Configuring Donation	|	select "smart donation"	|	easily donate without needing to select an EPM	|	all	|	"1. Display donation/investment ratio2. Editable donation/investment ratio within given bounds3. Select donation topic4. Exchange donation to DAI5. Forward donated DAI to a joint funding pool"	
Contributor	|	SC	|	Selecting and Configuring Donation	|	want to donate anonymously	|	keep my privacy	|	2	|		
Contributor	|	SC	|	Selecting and Configuring Invest	|	select "smart invest"	|	easily invest in AcrenToken without needing to select an EPM	|	2	|		
Contributor	|	SC	|	Selecting and Configuring Donation	|	select a specific EPM from a specific farmer for the donation	|	be sure that I only support EPMs and Farmers that I want to receive support	|	all	|	"1. Display all open EPMs provided by farmers2. Order EPMs by different properties3. View information about selected EPM4. Select EPM for donation"	
Contributor	|	SC	|	Selecting and Configuring Donation	|	select an donation amount	|	chose how much i want to spend	|	all	|	"1. Input donation amount2. Display donation-investemt ration3. Change donation amount"	
Contributor	|	SC	|	Selecting and Configuring Donation	|	select distribution to donation / token buy	|	chose how much i want to donate and invest	|	all	|	"1. Display donation amount2. Change donation amount3. Display donation-investment ratio4. Change donation/investment ratio within given bounds"	
Contributor	|	Off Chain	|	Send Donation	|	send transaction through Bank-Transfer	|	be able to support withought haven to adopt a new System	|	alle	|	"1. Display bank information and amount2. Approve completed banktransfer3. Display next steps4. Display approx. Transfer time"	
Contributor	|	Off Chain	|	Send Donation	|	send transaction through CreditCard and Paypal	|	be able to support withought haven to adopt a new System	|	2	|		
Contributor	|	SC	|	Send Donation	|	send transaction through Ethereum/Dai token	|	be able to support with crypto tokens	|	all	|	"1. Display Ethereum address, amount and time to complete2. Display transaction status3. Display success or failure4. Display invoice"	
Contributor	|	SC	|	Send Donation	|	send transaction through crypto token	|	be able to support with crypto tokens	|	2	|	""	
Contributor	|	SC	|	Send Donation	|	send transactions which are pure donations withought having to register on any app or website	|	send a donation with less time consumption	|	all	|		
Contributor	|	SC	|	Send Donation	|	Receive an invoice	|	to use it in my annual tax declaration 	|	1	|	"1. Display all donations with donation status2. Download selected donation"	
Contributor	|	SC	|	Acren token	|	Receive the bought acren token	|	to get the acren token	|	all	|	"1. Display amount of AcrenToken2. Display AcrenToken actions (burn)3. Display all specifics of order"	
Contributor	|	SC	|	Acren token	|	burn the owned acren token and receive DAI	|	to monetize the acren token	|	all	|	"1. Display amount of AcrenToken2. Specify amount of AcrenToken to burn3. Burn selected amount of token4. Add receive Address for DAI5. Display status of burn"	
Contributor	|	SC	|	Acren token	|	get information about the acren token	|	get informed and support the decisions about buying/burn acren token	|	all	|	1. Display detailed information about AcrenToken	
Contributor	|	SC	|	Review Donation Process	|	Review how the farmer used the donation	|	be sure that my donation is used only for eniromental protection	|	all	|	"1. Display all donations of contributor2. Order donations of contributor by properties3. Diplay all properties of selected donation4. Display status of donations"	
Contributor	|	SC	|	Review Donation Process	|	Review the whole cash flow of my donation	|	be sure that most of my donation is used for the selected EPM	|	2	|		
Contributor	|	SC	|	Review Donation Process	|	receive a certificate 	|	be able to show others that I am activly engaging in envirmental Protection	|	2	|		
Contributor	|	SC	|	Review Donation Process	|	write messages to the farmer	|	be in contact with the person who implements the EPM	|	2	|		
Contributor	|	SC	|	Review Donation Process	|	receive a acknowledgement by the farmer after completion of EPM	|	stay in contact with a beneficary of the donation	|	2	|		
Contributor	|	SC	|	Review Proofs	|	see a proof created by farmers	|	validate on my own if the farmer really implemented the EPM	|	2	|		
Contributor	|	SC	|	Review Proofs	|	see validators and validation log	|	be able to be sure that the farmer really implemented the EPM	|	2	|		
Contributor	|	SC	|	Review Proofs	|	see if the validators approved the proof	|	know if the donation process has been a success	|	all	|	"1. Display validation status of all donations2. Display validation proof and properties of selected validation process"	



## Validator
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version  |	Acceptance criteria
------	|	------	|	------	|	------	|	------	 |	------	 |	------
Validator	|	SC	|	Validate Proof	|	receive instructions for validation proof 	|	be able to know how to validate proofs	|	2	|	
Validator	|	SC	|	Validate Proof	|	receive proofs	|	which I can prove	|	all	|	"1. Display all open validation processes with price2. Display open validation process3. Display notification of incoming proof"
Validator	|	Off Chain	|	Validate Proof	|	receive payment in AcrenToken or DAI	|	to cover expenses for validating proof	|	all	|	"1. Display closed validation and payment2. Display amount of received token for validating3. Display action for token "
Validator	|	SC	|	Validate Proof	|	stake money	|	be able to validate proof	|	2	|	
Validator	|	SC	|	Validate Proof	|	review validation results	|	be able to determine if my validation was correct	|	2	|	



## Experts
As &lt;Actor>	|	System	|	Modul	|	I want to &lt;do this>	|	to &lt;reach this aim> |	Version  |	Acceptance criteria
------	|	------	|	------	|	------	|	------	 |	------	 |	------
Experts	|	SC	|	Creates EPM Proposal	|	set the basic configuration (e.g.  description, process, price range, proof-system)	|	accept only fair EPMs	|	2	|	
Experts	|	SC	|	Creates EPM Proposal	|	create a EPM Proposual with a set configuration set	|	propose good EPMs to implement	|	2	|	
Experts		SC	|	ExpertPayment 	|	receive a resonable payment in Token	|	to cover the expenses of the tasks	|	all	|	"1. Display all validations of validators2. Display all open validations3. Display status of validations4. Display amount of validations5. Display validation actions"
Experts	|	Off Chain	|	ExpertPayment 	|	receive a resonable payment in EUR	|	to cover the expenses of the tasks	|	2	|	
Experts	|	SC	|	Reviews EPMs	|	discuss with other experts which EPMs should be implemented or removed	|	accept only EPMs which are beneifical for enviromental protection	|	2	|	
Experts	|	SC	|	Reviews EPMs	|	review EPMs 	|	check whether configurations and EPMs are still useful und fair	|	all	|	"1. Display all EPMs3. Display selected donation process"
Experts	|	SC	|	Reviews EPMs	|	review selected proofs	|	check whether selected proof-system works  	|	all	|	"1. Display all validations2. show donation and validation process of selected validation"
Experts	|	SC	|	Reviews EPMs	|	review full donation processes	|	check whether validators and proof-system are intact	|	all	|	"1. Display all Donations2. Display process of selected donation"
