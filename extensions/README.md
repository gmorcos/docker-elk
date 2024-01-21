# Extensions

Third-party extensions that enable extra integrations with the Elastic stack.
docker-compose -f docker-compose.yml -f extensions/curator/curator-compose.yml up -d
docker-compose -f docker-compose.yml -f extensions/enterprise-search/enterprise-search-compose.yml up -d
docker-compose -f docker-compose.yml -f extensions/filebeat/filebeat-compose.yml up -d
docker-compose -f docker-compose.yml -f extensions/heartbeat/heartbeat-compose.yml up -d
docker-compose -f docker-compose.yml -f extensions/logspout/logspout-compose.yml up -d
docker-compose -f docker-compose.yml -f extensions/metricbeat/metricbeat-compose.yml up -d
docker-compose -f docker-compose.yml -f extensions/fleet/fleet-compose.yml -f extensions/fleet/agent-apmserver-compose.yml up -d


docker-compose -f docker-compose.yml -f extensions/filebeat/filebeat-compose.yml -f extensions/heartbeat/heartbeat-compose.yml -f extensions/metricbeat/metricbeat-compose.yml up -d
