# options-for-cloud-SQL-hosting
Exploring the cost and quality of different methods of hosting a SQL server on GCP and AWS.

Last update: 2024 Apr 04

Here is a high level summary of the options which I will explore:
(click on the method name for more detail)

| Method | Cost | Latency | Concurrency | Security | Setup/maintenance Difficulty | Backup/rollback/consistency/data loss|Limitations|
|--------|------|---------|-------------|----------|------------------------------|-----------------------------|-------------|
| Google BigQuery | | | |<code style="color : Green">High (managed)</code>|<code style="color : Green">Easy (managed)</code> | | Maximum 1,500 modifications to a table per day (this includes adding new rows) |
| self-hosted SQL server on a GCP Compute Engine VM| | | | | | | |
| self-hosted SQL server on an AWS EC2 instance| | | | | | | |
| CloudNativePG on Google Kubernetes Engine (GKE)| | | | | | | |
| CloudNativePG on Amazon Elastic Kubernetes Services (EKS)| | | | | | | |
| Serverless (e.g. SQLite) with database files stored on cloud storage| | | | | | | |
| template row | | | | | | | |
