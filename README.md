# ES_Kibana_Grafana
docker compose file to have containers for Elastic Search(Data Store/Indexing) + Kibana(Vizualization) + Grafana(Vizualization)

* ```git clone https://github.com/abhishekjt/ES_Kibana_Grafana.git```
* ```cd ES_Kibana_Grafana```
* ```docker-compose build```
* ```docker-compose up```
* open grafana: ```http://localhost:3000```
* ES: ```http://localhost:9200```
* Kibana: ```http://localhost:5601```

Note: To add elasticsearch as datasource in grafana, give the IP address of ES container(`docker inspect es_container_id|grep "IPAdress"`)
