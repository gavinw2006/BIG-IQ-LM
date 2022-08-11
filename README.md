# BIG-IQ-LM

This is a repo for APIs on BIG-IQ LM and DO Declarations on BIG-IP to assign/revoke/re-assign the license on BIG-IP via BIG-IQ License Manager (LM)

Contents including, 

The API examples on BIG-IQ License Manager (LM) automatic assign/revoke (push) a license from an ELA/Utility license pool to a BIG-IP instance;

The DO Declarations on BIG-IP to automatic assign (pull), revoke and relicense a license from an ELA/Utility license pool on a BIG-IQ LM;

Adding the BIG-IQ LM intro Deck v1.1 pdf;

Prerequisites:

Provision BIG-IQ LM in Azure/AWS etc Cloud and install/activate the F5 ELA/Utility license pool(s);

Use Terraform to spin up New F5 BIG-IP VEs in the VNet/VPC, make sure the connectivity between BIG-IQ LM and F5 BIG-IP VEs, these new BIG-IP VEs are reachable from BIG-IQ LM (might need vnet peering, routing etc.)
