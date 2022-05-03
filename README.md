# Weather Dashboard using Nodered, Influxdb and Grafana via Terraform

The original project is from Derek Morgan's course <strong>More Than Certified</strong>. Here's the link to the github repo:https://github.com/morethancertified/mtc-terraform.
Here I used Terraform to build infrastructure on AWS Cloud9 using Docker images of these services (nodered, influxdb and grafana). 
This is a Data Pipeline (ETL) project that collects (E-extract) weather data from OpenWeatherMap using their RestAPI and then makes necessary Data Transformations (T) and Loads (L) it into InfluxDB. I used Grafana to then create the dashboard.
