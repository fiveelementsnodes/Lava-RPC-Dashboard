# Lava RPC Provider Dashboard for Grafana 🌋

## Overview

This repository contains a Grafana dashboard designed to monitor the metrics of the Lava RPC Provider.

https://docs.lavanet.xyz/provider

## Features

- **Nodes monitoring:** Monitor RPC metrics for different blockchains supported by the Lava RPC Provider.
- **Real-time Metrics:** Keep track of essential real-time data, including response times, call rates, and more.
- **User-Friendly Visualization:** Grafana provides intuitive visualizations for quick insights into the health and performance of the RPC provider.
- **Customizable Dashboards:** Easily customize and extend the dashboard to suit your specific monitoring requirements.

## Configuration

This dashboard comes equipped with two essential variables for flexible configuration:

- Instance IP Address Variable: Set the IP address of your Lava RPC Provider to monitoring your specific deployment.
- Metrics Port Variable: Configure the metrics port to ensure communication between Grafana and your RPC Provider.

## Getting Started

1. **Installation:**
   - Install Prometheus as the data source for your metrics collection.
   - Install Grafana on your server.
   - Import the provided JSON dashboard configuration into Grafana.

2. **Configuration:**
   - Set the IP address and metrics port variables to match your Lava RPC Provider deployment.
   - Configure Prometheus as the data source in Grafana.

3. **Customization:**
   - Tailor the dashboard to your specific needs by adding or modifying panels.
  
## Requirements

- Prometheus
- Grafana (version 10.2.2 or later)

## Contributing

If you have suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request. Contributions are highly welcome!

<img src="https://www.5elementsnodes.com/wp-content/uploads/2023/12/LOGO-1.png" width="20%">
