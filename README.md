# Soc-home-lab
## 🛡️ SOC Lab

# 🔍 EFK Stack (Elasticsearch, Filebeat, Kibana)

A lightweight logging stack for collecting, storing, and visualizing logs using Filebeat, Elasticsearch, and Kibana.

---

## 📦 Components

### 1. **Elasticsearch**
- Distributed search and analytics engine.
- Stores structured and unstructured data.
- RESTful API for querying and indexing.

### 2. **Filebeat**
- Lightweight log shipper.
- Tail logs from files, containers, services.
- Sends logs to Elasticsearch directly.

### 3. **Kibana**
- Visualization tool for Elasticsearch data.
- Powerful dashboards, charts, and filters.
- Real-time log search and anomaly detection.

---

## ⚙️ How It Works

```plaintext
[ Log File ] → [ Filebeat ] → [ Elasticsearch ] → [ Kibana UI ]


