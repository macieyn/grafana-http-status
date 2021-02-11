# Readme

1. Setup your sources in telegraf.conf under `urls` (find `[[inputs.http_response]]`)
2. Run `docker-compose up --build`
3. Login to Grafana with default admin:admin
4. Add InfluxDB data source. Database name is `telegraf`.
5. Go to `Create > Dashboard > Import` and import this dashboard: https://grafana.com/grafana/dashboards/11777
6. Select data source.
7. You're good to go.