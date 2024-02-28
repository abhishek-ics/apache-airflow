## Install Airflow

```bash 
helm repo add apache-airflow https://airflow.apache.org/
```

```bash
helm repo update
```

```bash
kubectl create namespace airflow
```

```bash
helm upgrade --install my-airflow apache-airflow/airflow --version 1.12.0 -n airflow --values values.yaml
```