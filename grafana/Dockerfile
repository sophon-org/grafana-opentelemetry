FROM grafana/grafana-oss:12.3.1

# copy the datasources and dashboards
COPY grafana-datasources.yml /etc/grafana/provisioning/datasources/datasources.yml

ENV GF_INSTALL_PLUGINS=grafana-piechart-panel,grafana-worldmap-panel,grafana-clock-panel,grafana-simple-json-datasource,grafana-lokiexplore-app

EXPOSE 3000
