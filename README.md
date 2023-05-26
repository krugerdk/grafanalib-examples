# grafanalib examples
I have spent several days trying to figure out how to create dashboards and graphs in Grafana using the grafanalib Python-module. The examples shown on the official documentation page is somewhat lacking in my opinion, so I have added some stuff to mine that you can use as an inspiration. One of the things that's not described properly is how you create alerts.

You can find more info about the grafanalib module from their website: https://github.com/weaveworks/grafanalib

# Caveats
I have used grafanalib against AWS Managed Grafana v8. One thing that is somewhat different is the whole definition of alerts, because alerts on AWS is written as a part of the graph/timeseries visualization that you create. The official AWS documentation about AWS Managed Grafana mentions something about classic alerts. I have not used these and cannot comment on it.  

# Where?
In the file grafanalib-example.py I have commented on parts of the code that I think is important. Please also take a look at the official documentation page from the module homepage.
