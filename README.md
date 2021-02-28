# MARLOWE

This simple contract is to capture an ADA100 loan given by the Bank to its Customer secured by USD1,000 security. 

Steps
1. Customer to deposit USD1000 into the contract.

2. Bank to deposit ADA100 into the contract.

3. The contract release ADA100 to the Customer. 

4. On the repayment date:

a. Customer confirms that ADA100 has been returned to the Bank;

b. Agent (Bank's agent) to check if the money has been received and to either confirm or deny the Customer's confirmation

c. If the Agent confirms that the Customer's confirmation is correct, the Contract will release the USD1,000 to the Customer.

c1. If the Agent does not confirm or deny within a stipulated time, the Contract will release the USD1,000 to the Customer.

d. If the Agent denies the Customer's confirmation, the confirmation is escalated to the Bank directly for the Bank to confirm.  

e. If the Bank confirms that the Customer's confirmation is correct, the Contract will release the USD1,000 to the Customer.

f. If the Bank denies the Customer's confirmation, the Contract will release the USD1,000 to the Bank.
