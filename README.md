# Projeto Grafana

Projeto visa implementar uma stack de monitoramento utilizando o ``Grafana`` e ``Prometheus``, em um ambiente ``AWS``. Nesse estudo de caso vou utilizar terraform para a construção da infra que vai contar com duas instacias ``EC2 - t2.micro`` que fazem parte do ``free tier da AWS``, onde uma será o servidor do grafana e na segunda maquina instalaremos um agente do prometheus para coleta das metricas que vamos utilizar para montar a dashboard.

## Ferramentas utilizadas

- [AWS](AWS)
- [Terraform](Terraform)
- [Docker](Docker)
- [Grafana](Grafana)
- [Prometheus](Prometheus)
- [Node-Exporter](Node-Exporter)
- [Portainer](Portainer)