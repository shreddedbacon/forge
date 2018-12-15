# Forge
Forge is a collection of BOSH deployments to quickly spin up an operations environment.

# Goal
The goal of Forge is to allow a team to quickly establish systems used in an operations environment.

Systems to include would be, but not limited to:
* Directory Services and Authentication
* CI/CD
* Source Control System
* Chat
* Secure Credential Storage
* Wiki
* Issue Tracking
* Backup and Restoration Service
* Monitoring, Metrics, and Alerting
* Logging

Where possible, systems will be pluggable. For instance, if you already have Directory Services, you can choose to remove that from the deployment.

The main releases that will be used within a Forge will likely be:
* OpenLDAP
* UAA (User Account and Authentication Service)
* ConcourseCI
* Gogs
* MatterMost
* CredHub
* Graylog
* Prometheus
* SHIELD
* JIRA (or other easy deployed alternative)
* Confluence (or other easy deployed alternative)
