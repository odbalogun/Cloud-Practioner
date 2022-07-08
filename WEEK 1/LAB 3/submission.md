# LAB 3

- Create the `BillingFullAccessGroup` user group and assign the `Billing` policy to it.
- Create the `BillingViewAccessGroup` user group and assign the `AWSBillingReadOnlyAccess` policy to it.
- Create the `FinanceManager` user and be sure to enable passworded AWS Management Console access. Add the user to the `BillingFullAccessGroup`. 
- Create the `FinanceUser` user and be sure to enable passworded AWS Management Console access. Add the user to the `BillingViewAccessGroup`.
- If you allowed AWS autogenerate the account passwords, be sure to note them somewhere.
- Log out of your admin account, and log in as the `FinanceManager`. Go to Cost Explorer and try to create a report. It should be successful.
- Do the same with `FinanceUser`. You should receive an error.
- Delete both users then delete the user groups.