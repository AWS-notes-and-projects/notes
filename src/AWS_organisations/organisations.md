without aws organisations many organisations have to manage several accounts manually 
standard account you created becomes management account(master) you can invite other accounts and they have to prove their identity by providing their email id and phone number and then you can add them to your organisation
then they change from being standard to member account
organisations have 1 master account and 0 or more member accounts

structure within the organisation is heirarchical
ou(orgranisation unit) is a group of accounts
organisation unit can have 1 or more accounts
organisation has 1 root
root is a container for all the accounts in the organisation

individual billin methods for each account are removed and replaced with a single billing method for the organisation

aws organisation features a feture called service control policies
service control policies are used to control which aws services can be used in which accounts
service control policies are applied to accounts and ou's

with organisations you dont need iam accounts for each account
you can use iam roles
you can use aws single sign in to manage access to aws accounts and applications

roll switch is a feature that allows you to switch between accounts without having to log out and log back in



