## Actors

The system has 7 Actors<br>

Actor | Function
------ | ------
Farmers   |  Farmers can offer environmental protection measures and implement funded measures in accordance with the specified requirements. They are limited in the scope of their offer (e.g. price, execution period, offer quantity/frequency). The limitation is determined by the administration and the expert group.
Donors | Donors can donate to environmental protection measures offered by farmers and monitor all steps (money allocation, implementation, validation and impact of the implemented measures) of the donation process.
Investors |Investors can buy [Acren token](../token) to participate in the growth of Acren. A part of any investment flows as a fully transparent donation to environmental protection measures. The other part of the investment flows into a bonding curve contract which is issuing the [Acren token](../token).
Validators | Validates whether farmers have successfully implemented the environmental protection measures according to the guidelines set by the expert group.
Administrator | Channeling euro funds from donors to farmers. Identify, release and block farmers if necessary. Select the expert group. Update the existing system.
Experts | Define environmental protection measures that must be followed by farmers in order to successfully place offers (maximum/minimum price, duration of implementation, measures to be offered) and receive donations. Are represented in the first version by administrators. In the future, active donors and community members will take this position.
Bank Account (Oracle) | Handles all types of euro transactions within the system.


<!-- 
## Trust table

An incentive model and the design of the system should ensure that despite the DNT dependencies, the individual actors can use the system with confidence.<br>

Actor | Trusts* | Does not trust (DNT) | No reveleant connection to
------ | ------ | ------ | ------
Farmers | Administrator | Donor, Verifiers | Experts, Investors
Donors | - | Farmer, Verifiers, Administrator | Experts, Investors
Investors | - | Administrator | Farmers, Donors, Verifiers, Experts
Verifiers | Experts | Farmers, Administrator | Donors, Investors
Administrator | Bank Account (Oracle) | Donors, Verifiers, Farmers, Investors |	-
Experts	| Administrator | Verifiers	| Farmers, Donors, Investors
Bank Account (Oracle) | Administrator |	- | Farmers, Donors, Verifiers, Experts, Investors

*All Actors trust the open-source Smart-Contract and open-source Frontends 
--> 

## Usage of blockchain

The blockchain is used for all communication between the actors, the display of the flow of funds (euro-donations/investments) and the transfer of funds (crypto-donations/investments). Each contact and process step of each actor is recorded in the blockchain. Zero-Knowledge-Proofs guarantee the privacy of the actors.