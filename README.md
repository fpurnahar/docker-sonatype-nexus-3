# Docker Nexus 3
This docker nexus 3 using images sonatype/nexus3

# Installation
  - clone this repository https://github.com/fpurnahar/docker-sonatype-nexus-3.git
  - create docker network local_network 
  - create docker local volume data_nexus
  - docker build . --tag my-iamges
  - docker compose -f docker_compose_nexus.yaml
