# Apache Airflow - Arquitetura de Medalhão

### Ambiente

```~/Documents/Medalhas```

**Baixando o projeto**
```bash
# 1. Donwnload
$ wget https://caelum-online-public.s3.amazonaws.com/2689-apache-airflow-transformando-dados/aula-1.zip

# 2. Extrair apenas as pastas: airflow_pipeline, datalake e src
```

**Instalando o Apache Airflow**

```bash
$ CONSTRAINT_URL="https://raw.githubusercontent.com/apache/airflow/constraints-2.3.2/constraints-3.9.txt"
$ pip install "apache-airflow[postgres,celery,redis]==2.3.2" --constraint "${CONSTRAINT_URL}"
$ export AIRFLOW_HOME=/home/alura/Documents/Medalhas/airflow_pipeline
$ airflow standalone
```

### Bibliotecas

$ pip install requests==2.27.1

