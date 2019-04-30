# Zabbix-Grafana-Docker

Start container in this order:

- MySql
- Gateway
- Zabbix Server
- Zabbix Web
- Grafana

After start grafana, access the container and install zabbix plugin:

- docker exec -it grafana bash
- grafana-cli plugins install alexanderzobnin-zabbix-app

Access Grafana via browser on port 3000, and Zabbix Web via browser on port 80
