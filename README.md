# common_vars의 변수 별 deployment

PaaS-TA >= v5.0.3

### BOSH INFO
|변수이름|deployment|
|------|---|
|bosh_ip|monitoring-deployment/paasta-monitoring|
|bosh_url|service-deployment/lifecycle-service<br>service-deployment/container-service<br>service-deployment/redis<br>service-deployment/gateway-service|
|bosh_client_admin_id|service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service|
|bosh_client_admin_secret|monitoring-deployment/paasta-monitoring<br>service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service<br>|
|bosh_director_port|service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service|
|bosh_oauth_port|service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service|

### PAAS-TA INFO
|변수이름|deployment|
|------|---|
|system_domain|monitoring-deployment/paasta<br>monitoring-deployment/paasta-monitoring<br>monitoring-deployment/logsearch<br>service-deployment/glusterfs<br>service-deployment/rabbitmq<br>service-deployment/mongodb<br>service-deployment/container-service<br>service-deployment/source-control-service<br>service-deployment/redis<br>service-deployment/pipeline-service<br>service-deployment/logging-service<br>paasta-deployment/paasta<br>portal-deployment/portal-api<br>portal-deployment/portal-ui|
|paasta_admin_username|monitoring-deployment/paasta<br>monitoring-deployment/paasta-monitoring<br>service-deployment/glusterfs<br>service-deployment/rabbitmq<br>service-deployment/mongodb<br>service-deployment/redis<br>paasta-deployment/paasta<br>portal-deployment/portal-api<br>|
|paasta_admin_password|monitoring-deployment/paasta<br>monitoring-deployment/paasta-monitoring<br>service-deployment/glusterfs<br>service-deployment/rabbitmq<br>service-deployment/mongodb<br>service-deployment/redis<br>paasta-deployment/paasta<br>portal-deployment/portal-api|
|paasta_nats_ip|service-deployment/mongodb|
|paasta_nats_port|service-deployment/mongodb|
|paasta_nats_user|service-deployment/mongodb|
|paasta_nats_password|service-deployment/mongodb|
|paasta_nats_private_networks_name|service-deployment/container-service|
|paasta_database_ips|portal-deployment/portal-api|
|paasta_database_port|portal-deployment/portal-api|
|paasta_database_type|portal-deployment/portal-api|
|paasta_database_driver_class|portal-deployment/portal-api|
|paasta_cc_db_id|portal-deployment/portal-api|
|paasta_cc_db_password|monitoring-deployment/paasta<br>paasta-deployment/paasta<br>portal-deployment/portal-api|
|paasta_uaa_db_id|portal-deployment/portal-api|
|paasta_uaa_db_password|monitoring-deployment/paasta<br>paasta-deployment/paasta<br>portal-deployment/portal-api|
|paasta_api_version|portal-deployment/portal-ui|


### UAAC INFO
|변수이름|deployment|
|------|---|
|uaa_client_admin_id|service-deployment/logging-service<br>portal-deployment/portal-api|
|uaa_client_admin_secret|monitoring-deployment/paasta<br>service-deployment/logging-service<br>paasta-deployment/paasta<br>portal-deployment/portal-api|
|uaa_client_portal_secret|monitoring-deployment/paasta<br>paasta-deployment/paasta<br>portal-deployment/portal-ui|


#### Monitoring INFO
|변수이름|deployment|
|------|---|
|metric_url|monitoring-deployment/paasta<br>monitoring-deployment/paasta-monitoring<br>|
|syslog_address|monitoring-deployment/paasta<br>monitoring-deployment/logsearch|
|syslog_port|monitoring-deployment/paasta<br>|
|syslog_transport||
|saas_monitoring_url|monitoring-deployment/pinpoint-monitoring<br>monitoring-deployment/paasta-monitoring|
|monitoring_api_url|monitoring-deployment/paasta-monitoring<br>portal-deployment/portal-api|

### Portal INFO
|변수이름|deployment|
|------|---|
|portal_web_user_ip||
|portal_web_user_url|portal-deployment/portal-api|


### ETC INFO
|변수이름|deployment|
|------|---|
|abacus_url|portal-deployment/portal-api|
