# grafanalib examples
I have spent several days trying to figure out how to create dashboards and graphs in Grafana using the grafanalib Python-module. The examples shown on the official documentation page is somewhat lacking in my opinion, so I have added some stuff to mine that you can use as an inspiration. One of the things that's not described properly is how you create alerts.

You can find more info about the grafanalib module from their website: https://github.com/weaveworks/grafanalib

# Caveats
I have used grafanalib against AWS Managed Grafana v8. One thing that is somewhat different is the whole definition of alerts, because alerts on AWS is written as a part of the graph/timeseries visualization that you create. The official AWS documentation about AWS Managed Grafana mentions something about classic alerts. I have not used these and cannot comment on it.  

# Where?
In the file grafanalib-example.py I have commented on parts of the code that I think is important. Please also take a look at the official documentation page from the module homepage.

# License
Copyright (c) 2023 Kruger A/S

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
