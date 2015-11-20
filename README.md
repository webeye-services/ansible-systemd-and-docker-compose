ansible role for docker compose as systemd service
==================================================

role for ansible to install docker custom service on systemd OS (actually tested on one CentOS 7). So far feed free
to send pull request for update.

Role Variables
--------------

 * **docker_compose_file**: docker compose template path
 * **docker_app_name**: docker application name, also name of service and name of container
 
 