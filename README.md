# BI & Big Data - Laboratorio 06

## Objetivo

Implementar un flujo ELT utilizando Liquibase, GitHub Actions, Databricks y dbt.

## Arquitectura

- Git y GitHub para versionamiento.
- Liquibase para cambios estructurales.
- GitHub Actions para CI/CD.
- Databricks y Unity Catalog como plataforma de datos.
- Capa Bronze para datos crudos.
- Capa Silver para datos transformados.
- dbt para transformaciones, pruebas y lineage.

## Laboratorio 06

El flujo implementará:

1. Schemas Bronze y Silver mediante Liquibase.
2. Tablas raw en Bronze.
3. CI mediante GitHub Actions.
4. CD hacia Databricks.
5. Data Loading en Bronze.
6. Transformaciones Bronze -> Silver con dbt.
7. Pruebas de calidad.
8. Lineage de modelos.

## Seguridad

Las credenciales, tokens y archivos `liquibase.properties` locales no deben versionarse.