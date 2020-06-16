# docker-grafana-prometheus

Contient du spécifique boulot

Export de l'image Docker de StreamsMetricsExporter construite à partir du tuto IBM sur mon MacBook:
docker save -o ./docker_streamsexporter.tar docker_streamsexporter:latest

Import sur la machine cible:
docker load -i docker-streamsexporter.tar
