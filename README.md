# Cloud Computing Task 2 – Cloud Monitoring and Alerts

## Objective
To set up monitoring and alerting for a cloud-based application using tools equivalent to AWS CloudWatch, Google Cloud Monitoring, or Azure Monitor.

---

## Tools & Technologies Used
- Prometheus – Metrics collection
- Grafana – Dashboards and alerts
- Docker & Docker Compose
- Git & GitHub

---

## Monitoring Setup
- Prometheus was configured to scrape metrics at regular intervals.
- Grafana was connected to Prometheus as a data source.
- The `up` metric was used to monitor service availability.

---

## Dashboard Configuration
- A Grafana dashboard named **Cloud Monitoring Dashboard** was created.
- The dashboard visualizes service availability using time-series graphs.
- Metrics update automatically at regular intervals.

---

## Alert Configuration
- An alert rule named **Service Down Alert** was created.
- The alert triggers when the monitored service becomes unavailable (`up < 1`).
- Alert evaluation runs every 1 minute.
- A local contact point was configured for notifications.

---

## Screenshots
Screenshots demonstrating the following are included in the `screenshots` folder:
- Grafana dashboard with metrics
- Alert rule configuration
- Alert status screen

---

## Cloud Platform Mapping
| Implemented Tool | AWS / GCP Equivalent |
|------------------|----------------------|
| Prometheus | AWS CloudWatch Metrics |
| Grafana Dashboard | CloudWatch Dashboard |
| Grafana Alert | CloudWatch Alarm |

---

## Result
Successfully implemented cloud monitoring and alerting, demonstrating real-world observability concepts without requiring paid cloud services.
