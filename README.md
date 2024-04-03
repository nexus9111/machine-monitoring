# Monitoring - Grafana - Prometheus - Node Exporter - Docker

## Description

This project is a simple monitoring system using Grafana, Prometheus, Node Exporter and Docker. It is a simple way to monitor your system resources.

## Requirements

- Docker
- Docker Compose

## How to use

1. Clone this repository
2. Run the following command:

```bash
docker-compose up -d
```

3. Access the Grafana dashboard at http://localhost:3000

## Grafana Dashboard

- User: admin
- Password: admin

_Note_: Grafana will ask you to change the password after the first login.

## Setup Grafana Dashboard

- Add Prometheus as a data source

  - URL: http://prometheus:9090
  - click on "Save & Test"

- Import the dashboard
  - Go to 'http://localhost:3000/dashboard/new" and click on "Import"
  - Enter the dashboard ID: 1860
  - Select the Prometheus data source
  - Click on "Import"

## Credits

- Author: Joss C.
