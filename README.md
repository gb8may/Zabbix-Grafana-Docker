# Zabbix-Grafana-Docker

Start container in this order:

- 1 - MySql
- 2 - Gateway
- 3 - Zabbix Server
- 4 - Zabbix Web
- 5 - Grafana

After start grafana, access the container and install zabbix plugin:

- docker exec -it grafana bash
- grafana-cli plugins install alexanderzobnin-zabbix-app

Access Grafana via browser on port 3000
Access Zabbix Web via browser on port 80
