# Realtime-Spark-Streaming-Java

Realtime user-friendly e-commerce users analytics dashboard.

_Toolset: Spark, Kafka, Grafana, MySQL,  influxDB, Docker, Avro, Maven_



### Docker operations ###
```shell
# SPARK
docker pull bitname/spark
# Run the image
docker run -d --name spark bitname/spark
# Open container in interactive mode
docker exec -it spark-shell


# INFLUX DB
# Fire up Influx DB
docker-compose up -d influx_grafana

# Enter into influx container
docker-compose exec influx_grafana sh

#Star influx shell
influx

```
