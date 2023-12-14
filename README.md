# COMP0235 Coursework
This repository contains all the relevant infrastrucure as code files and instructions of how to deploy them thorough Docker.

## Technology Stack
![My Skills](https://skillicons.dev/icons?i=py,pytorch,ansible,aws,kubernetes,docker,grafana,prometheus,linux&perline=3)

## Run the project
[![Static Badge](https://img.shields.io/badge/docker_pull-blue)](https://github.com/mruiyangyou)


## Specific execuation order of all files
1. [Setup all machines](./setup_machines.yml)
3. [Setup monitor service on workers](./node_exporter_playbook.yml)
2. [Monitoring on localhost](./host_monitoring.yml)
3. [Install packages on workers](./install_packages.yml)
4. [Install database on host](./install_database.yml)
5. [Preparation for localhost](./prepare_localhost.yml)
6. [Prepartion for workers](./prepare_workers.yml)
7. [Run the analysis on workers](./workers_analyze.yml)
8. [Collecting results on localhost](./combine_results.yml)