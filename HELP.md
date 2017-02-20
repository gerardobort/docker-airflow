docker-compose -f docker-compose-CeleryExecutor.yml up
docker-compose -f docker-compose-CeleryExecutor.yml ps
docker-compose -f docker-compose-CeleryExecutor.yml down
docker exec -it dockerairflow_webserver_1 bash
