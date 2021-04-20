# Grafana Daskboard For Agoric Validator
![alt text](https://github.com/earnx-stake/Agoric-Dashboard/blob/main/Agoric%20Dashboard.png?raw=true)

# How to use it 
- Install Prometheus Server on your monitoring machine (https://prometheus.io/docs/introduction/first_steps/).
- Configure Prometheus Server to scrap your validator metrics, pointing to you Agoric Validator.
- Install Grafana on your machine (https://grafana.com/).
- Configure Grafana using Web Interface and create a new datasource. Go to Configuration -> Data Sources -> Add datasource
- Download the JSON file that describes all dashboard configuration as the template above https://github.com/earnx-stake/Agoric-Dashboard/blob/main/Agoric%20Validator%20Daskboard%20-%20by%20EarnX-1618881703796.json 
- Using Grafana Web Interface, go to Dashboard -> Manage -> Import and upload the previous Dashboard JSON file
- On the Dashboard Interface, fill the variables "InstanceName" and "Interface" poiting to your respective Agoric Validator.


