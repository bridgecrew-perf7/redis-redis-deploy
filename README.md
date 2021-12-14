# redis-redis-deploy

redis 部署

## 库使用情况

- 0 hubble 项目使用
- 1 auxo 项目使用
- 2 carpo 项目使用
- 3 thallo 项目使用
- 4 ceres 项目使用
- 5 plutus 项目使用
- 6 odin   项目使用

## 部署 redis

helm upgrade --install --namespace redis -f values-dev.yaml redis ./redis
