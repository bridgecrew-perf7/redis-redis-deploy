# redis-redis-deploy

redis 部署

## 库使用情况

1 auxo-statistics 项目使用

## 部署 redis

helm upgrade --install --namespace redis -f values-dev.yaml redis ./redis
