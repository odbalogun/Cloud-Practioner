# LAB 2

## 1. Create a cost budget
    - Select AWS Budget from the service menu
    - On the next page, click the create budget button
    - Set the budget type as Cost Budget and click next
    - Enter a budget name, select a period/ budget renewal type and set an amount
    - Select a budget scope. This allows you to tie the budget to some or all AWS services.
    - On the next page, click the `Add an alert threshold` button. Set the threshold as a % of the budgeted amount or as an actual value. Also, add one or email addresses to notify. You can also configure SNS and Chatbot alerts.
    - On the next page, you can add an extra action to be triggered by the alert. This could be stopping an EC2 instance or any such operation. Click Next when you are done.
    - This page allows you to review your configuration and finalize the budget

## 2. Create a usage budget
    - Before you can create a usage budget, you have to enable Cost Explorer
    - On the AWS Budget page, click the create budget button. Set the budget type as Usage Budget.
    - Choose to budget against Usage type groups or Usage types and configure the service usage measurement as applicable.
    - Under Period, select how often you want the budget to reset the actual and forecasted usage.
    - Select whether the budget should be a Recurring budget or a one-time Expiring Budget
    - Under Budgeting method, select one of Fixed/ Planned/ Auto-adjusting
    - Add a Budget name and choose Next
    - Again, you can set alert thresholds and configure actions to be performed when needed