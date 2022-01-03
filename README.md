# common_vars의 변수 별 deployment

PaaS-TA >= v6.0.0

### BOSH INFO
|변수이름|deployment|
|------|---|
|bosh_ip|monitoring-deployment/paasta-monitoring|
|bosh_url|service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service<br>service-deployment/web-ide|
|bosh_client_admin_id|service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service<br>service-deployment/web-ide|
|bosh_client_admin_secret|monitoring-deployment/paasta-monitoring<br>service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service<br>service-deployment/web-ide|
|bosh_director_port|service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service<br>service-deployment/web-ide|
|bosh_oauth_port|service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service<br>service-deployment/web-ide|
|bosh_version|service-deployment/redis<br>service-deployment/web-ide|

### PAAS-TA INFO
|변수이름|deployment|
|------|---|
|system_domain|monitoring-deployment/paasta-monitoring<br>monitoring-deployment/logsearch<br>service-deployment/glusterfs<br>service-deployment/rabbitmq<br>service-deployment/mongodb<br>service-deployment/source-control-service<br>service-deployment/redis<br>service-deployment/pipeline-service<br>service-deployment/logging-service<br>service-deployment/web-ide<br>paasta-deployment/paasta<br>portal-deployment/portal-api<br>portal-deployment/portal-ui<br>portal-deployment/portal-container-infra|
|paasta_admin_username|monitoring-deployment/paasta-monitoring<br>service-deployment/glusterfs<br>service-deployment/mongodb<br>service-deployment/redis<br>service-deployment/web-ide<br>paasta-deployment/paasta<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|
|paasta_admin_password|monitoring-deployment/paasta<br>monitoring-deployment/paasta-monitoring<br>service-deployment/glusterfs<br>service-deployment/rabbitmq<br>service-deployment/mongodb<br>service-deployment/redis<br>service-deployment/web-ide<br>paasta-deployment/paasta<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|
|paasta_nats_ip|service-deployment/mongodb<br>service-deployment/rabbitmq|
|paasta_nats_port|service-deployment/mongodb|
|paasta_nats_user|service-deployment/mongodb|
|paasta_nats_password|service-deployment/mongodb|
|paasta_nats_private_networks_name| |
|paasta_database_ips|portal-deployment/portal-api|
|paasta_database_port|paasta-deployment/paasta<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|
|paasta_database_type|portal-deployment/portal-api|
|paasta_database_driver_class|portal-deployment/portal-api|
|paasta_cc_db_id|portal-deployment/portal-api|
|paasta_cc_db_password|paasta-deployment/paasta<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|
|paasta_uaa_db_id|portal-deployment/portal-api|
|paasta_uaa_db_password|paasta-deployment/paasta<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|
|paasta_api_version|portal-deployment/portal-ui|


### UAAC INFO
|변수이름|deployment|
|------|---|
|uaa_client_admin_id|service-deployment/logging-service<br>portal-deployment/portal-api|
|uaa_client_admin_secret|service-deployment/logging-service<br>paasta-deployment/paasta<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|
|uaa_client_portal_secret|paasta-deployment/paasta<br>portal-deployment/portal-ui<br>portal-deployment/portal-container-infra|


#### Monitoring INFO
|변수이름|deployment|
|------|---|
|metric_url|monitoring-deployment/paasta<br>monitoring-deployment/paasta-monitoring<br>|
|syslog_address|monitoring-deployment/paasta<br>monitoring-deployment/logsearch|
|syslog_port|monitoring-deployment/paasta<br>|
|syslog_transport||
|saas_monitoring_url|monitoring-deployment/pinpoint-monitoring<br>monitoring-deployment/paasta-monitoring|
|monitoring_api_url|monitoring-deployment/paasta-monitoring<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|

### Portal INFO
|변수이름|deployment|
|------|---|
|portal_web_user_ip||
|portal_web_user_url|portal-deployment/portal-api|


### ETC INFO
|변수이름|deployment|
|------|---|
|abacus_url|portal-deployment/portal-api|


### Zabbix Agent for monitoring
|변수이름|deployment|
|------|---|
|server_ip|monitoring-deployment/pinpoint-monitoring<br>monitoring-deployment/paasta-monitoring<br>monitoring-deployment/paasta<br>monitoring-deployment/logsearch|
|listen_port|monitoring-deployment/pinpoint-monitoring<br>monitoring-deployment/paasta-monitoring<br>monitoring-deployment/paasta<br>monitoring-deployment/logsearch|
|server_active|monitoring-deployment/pinpoint-monitoring<br>monitoring-deployment/paasta-monitoring<br>monitoring-deployment/paasta<br>monitoring-deployment/logsearch|
|host_metadata|monitoring-deployment/pinpoint-monitoring<br>monitoring-deployment/paasta-monitoring<br>monitoring-deployment/paasta<br>monitoring-deployment/logsearch|
