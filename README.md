# redis-redis-deploy

redis 部署

## 库使用情况

### 测试环境

1 auxo 项目使用

### 生产环境

0 hubble 项目使用
1 auxo 项目使用

## 部署 redis

helm upgrade --install --namespace redis -f values-dev.yaml redis ./redis
