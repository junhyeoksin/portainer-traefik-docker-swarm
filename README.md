# portainer-traefik-docker-swarm
Portainer with Let's Encrypt in a Dokcer Swarm 

The temporary configuration file is stored locally on the volume. It is recommended to move it to the NFS server when changes are made.

Deploy Portainer in a Dokcer Swarm using the command.

docker stack deploy -c portainer.yml portainer

도커 스웜에서 Let's Encrypt와 함께 Portainer를 배포방법입니다. 
임시 구성 파일은 볼륨에 로컬로 저장됩니다. 변경 사항이 있을 때마다 이를 NFS 서버에서 사용하는 것을 지향하고 있습니다.
다음 명령을 사용하여 도커 스웜에서 Portainer를 배포합니다.
docker stack deploy -c portainer.yml portainer
