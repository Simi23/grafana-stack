# Setup

1. Run docker-compose.yml
2. Set up Grafana at :3000
3. Set up influxDB at :8086

# Usage

- Set scrape jobs in config.alloy
- Send syslog to syslogng:514/udp

# Sites to be published

- grafana:3000 - Main Grafana dashboarding instance
- influxdb:8086 - InfluxDB Manager interface
- alloy:12345 - Grafana Alloy interface
