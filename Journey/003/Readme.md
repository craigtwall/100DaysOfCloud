# Deploy SCCM Via Azure QuickStart Template

## Introduction

This was a short-duration setup day towards future testing. I discovered Azure Quickstart Templates, and wanted to know if the SCCM Current Branch template would work in the A Cloud Guru Azure Cloud Sandbox. 

This would not only allow me a short-duration SCCM test environment, but would also give me insight into what in Azure would be necessary to stand that infrastructure up. 

## Cloud Research

- [Install Configuration Manager Current Branch in Azure](https://azure.microsoft.com/en-us/resources/templates/sccm-currentbranch/) -- This was the Quickstart Template in question. 

## What Does the Quickstart Template Install?

- AD Domain Controller (domain: contoso.com)
- 4 or 5 Virtual Machines, including the Domain Controller, the ConfigMgr primary site server, a remote site server, and one VM to act as an SCCM client
- Each VM has a public IP added to a Network Security Group, which only allows in RDP traffic.
- Each VM has a private IP so that ConfigMgr can communicate.

Unfortunately, in the time I had today -- roughly an hour -- the VMs and such were setup, but ConfigMgr was not installed on them yet. 

The [MS Guide for this template](https://docs.microsoft.com/en-us/mem/configmgr/core/get-started/azure-template) does say it could take 2-4 hours to complete, even after Azure appears to signal that the work is finished. I'll check this later.

## Social Proof

✍️ Show that you shared your process on Twitter or LinkedIn

[Day 3 Tweet](https://twitter.com/craigtwall/status/1393035834719449090)
