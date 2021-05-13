# Creating Budget Alerts

## Introduction

As an introductory part of the AZ-104 study plan, I made my first budget alert. 

I used the [BIL01-AZ100](https://github.com/100DaysOfCloud/100DaysOfCloudIdeas/blob/master/Projects/BIL/BIL01/BIL01-AZ100.md) project on [100DaysofCloud](https://github.com/100DaysOfCloud/100DaysOfCloudIdeas) as the prompt for this lesson. 

## Use Case

I previously completed the Azure Cloud Resume Challenge, and left the website up on my Azure account. As a result, it's going to slowly accrue charges. 

I set a $5 budget on the account, with an alert once it hits 50% of that amount, or $2.50.

# Question Answers 

1) The difference between a Budget Alert and Credit Alert: Budgets set the limit for spending. Credit alerts tell you when a prepayment on the account has been spent. Credit alerts are also only applicable to accounts with Enterprise agreements. 

2) The cost for creating cost alerts: Cost management features are listed as [Free](https://azure.microsoft.com/en-us/pricing/details/cost-management/) by Microsoft. 

3) The budget alert setup asks for an email, so once the $2.50 threshold is hit, Azure will send me an email to notify me. 

4) Where Cost Alerts are found in the Azure Portal: Cost Management + Billing is a good spot to find info on recurring charges. However, the "Cost Alerts" section on the sidebar in any Azure resource will get you to the cost alerts scoped to that resource. For example, clicking "Cost Alerts" under the Subscription will load the alerts scoped to the subscription.

## Cloud Research

- "Cost Alerts" versus "Budgets" was a little confusing, maybe because since my account doesn't have an Enterprise agreement, the only cost alerts I could really setup WERE the budgets. Still, I expected the budget alert to show up under "Cost alerts", and it didn't. 

## Resources

[Use Cost Alerts to Monitor Usage and Spending](https://docs.microsoft.com/en-us/azure/cost-management-billing/costs/cost-mgt-alerts-monitor-usage-spending)

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[Tweet](https://twitter.com/craigtwall/status/1392656030887301122)
