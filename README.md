# options-for-cloud-SQL-hosting
Exploring the cost and quality of different methods of hosting a SQL server on GCP and AWS.

Last update: 2024 Apr 04

Here is a high level summary of the options which I will explore:
(click on the method name for more detail)
<table>
    <tr>
        <th>Method</th>
        <th>Cost</th>
        <th>Latency</th>
        <th>Concurrency</th>
        <th>Security</th>
        <th>Setup/maintenance Difficulty</th>
        <th>Backup/rollback/consistency/data loss</th>
        <th>Limitations</th>
    </tr>
    <tr>
        <td>Google BigQuery</td>
        <td></td>
        <td></td>
        <td></td>
        <td>

```diff
+ High (managed)
```

</td>
        <td>

```diff
+ Easy (managed)
```

</td>
        <td></td>
        <td>Maximum 1,500 modifications to a table per day (this includes adding new rows)</td>
    </tr>
    <tr>
        <td>self-hosted SQL server on a GCP Compute Engine VM</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>self-hosted SQL server on an AWS EC2 instance</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>CloudNativePG (or other operator) on Google Kubernetes Engine (GKE)</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>CloudNativePG (or other operator) on Amazon Elastic Kubernetes Services (EKS)</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Serverless (e.g. SQLite) with database files stored on cloud storage</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>GCP Cloud SQL</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>Amazon Relational Database Service (RDS)</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>template placeholder row</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>template placeholder row</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td>template placeholder row</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table> 