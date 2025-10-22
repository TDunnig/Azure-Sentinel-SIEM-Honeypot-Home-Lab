![Banner](screenshots/banner.png)
# Azure-Sentinel-SIEM-Honeypot-Home-Lab

This lab simulates failed login attacks using a honeypot VM in Azure...

## Table of Contents
- [Architecture](docs/architecture.md)
- [Detection Query](queries/failed-logons.kql)
- [Screenshots](#screenshots)
- [Lessons Learned](#lessons-learned)

## Screenshots

![Failed login events](screenshots/event-id-4625.png)

## Lessons Learned

- How to configure a honeypot VM and NSG to simulate attacks
- How to ingest logs using AMA and DCR
- How to enrich data with GeoIP using `externaldata()`
- How to visualize threats in Sentinel Workbooks
