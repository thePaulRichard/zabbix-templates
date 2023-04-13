# Sefaz Monitoring with Zabbix and Grafana

## Overview

This repository contains templates for monitoring the SEFAZ system using Zabbix and displaying the data using Grafana. The Zabbix templates include web scenarios for each SEFAZ URL that is being monitored, with each web scenario corresponding to a Brazilian state. In the authentication tab within each web scenario, the name of the SSL certificate file and SSL key file must be entered to access the URLs from SEFAZ. By default, the names of these files are:

- sefaz_cert.pem
- sefaz_cert.key

In Grafana, the Grafana-worldmap-panel plugin must be installed. Once installed, the dashboard can be imported and will display the geolocation coordinates of each state in Brazil from a JSON file in this repository.

## How to Use

To use the templates in this repository, follow these steps:

1. Import the Zabbix templates.
2. Enter the name of the SSL certificate file and SSL key file in the authentication tab of each web scenario.
3. Install the Grafana-worldmap-panel plugin.
4. Import the Grafana dashboard.
5. Monitor the SEFAZ system and view the data in Grafana.

## Contact

If you have any questions or issues with using the templates in this repository, please don't hesitate to contact me.
