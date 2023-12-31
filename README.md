# Anonymyzation-of-Healthcare-Data
The system design proposes two types of blockchains: a public main chain and a private 
blockchain. However, the public blockchain contains the patient’s temporary ID only, therefore 
it does not allow tracking history of patient medical treatment. Moreover, in our system design, 
patients are considered owners of their own medical analysis, have full control over them, even 
if those are stored on clinics’ data-centers. Private block chain consists if the original data which 
was given by the customer and was stored in the clinics internal data base. In this system, the 
focus is on preventing the loss of data in both data at rest and in data at motion. Because the 
data is being stored in a blockchain, which is almost tamper-proof, we have the concept which 
will prevent the data at rest, i.e., the data being stored from being modified by any adversary. 
Since it is beyond our scope to increase the security of each hospital’s network, instead, we aim 
to anonymize our data in motion. That is, all the data which is being sent will be hashed to 
ensure that even if it compromised, it cannot 3 be abused by the attacker. In this way we can 
help secure the data in motion within our system from attackers. The data is separated into the 
public chain and the private chain, we have a separation of the actual data and the data being 
sent to the doctors. The real data which has all the patient’s information will not be transferred 
and this will minimize the risk from data in motion to it. The data being transferred to the 
doctors will be affected by all the risks which come from sending data over a network, but their 
security will depend on the network security of the hospitals, rather than the security of our 
system. Beyond this, the proposed system will be tested against different attacks and 
vulnerabilities like SQL injection attacks, Denial of Service attacks, Weak Authentications 
attacks and so on to identify the capability of the system to withstand such attacks and preserve 
its security.
