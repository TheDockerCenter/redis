# Redis Sentinel Cluster Rancher

[InfraTeam] Rancher template for Redis Sentinel Cluster

## Install

In Rancher's UI, go to **Admin/Settings** and add a new custom catalog:

| Name          | URL                                                   | Branch |
| ------------- | ----------------------------------------------------- | ------ |
| Redis Cluster | https://github.com/TheDockerCenter/redis.git          | master |

## Templates

* **redis**: Redis Sentinel Cluster for production environment

## Docker Images

* **redis-config**:
Docker image used as sidekick container of all redis containers to provide scripts and data.
