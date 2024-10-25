# EKS-Monitor
The objective of this repo is to set up a logging solution on AKS and it is going to utilize Promtail as the log shipper, Loki for log aggregation, and Grafana for log visualization.


Managing and analyzing logs is important for maintaining system health, helping with troubleshooting and also having insights ti application perfomance.

To proceed with this solution we will install each tool separately and then access the logs through Grafana dashboards by adding Loki as a data source.

Step 1 - Create a VNET for our AKS cluster.
