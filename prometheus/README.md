# 这个是在k8s上部署监控的yaml
# 还没定义数据持久化  后期再改
- 部署操作如下：
  - $ kubectl apply -f prometheus/setup
  - $ kubectl apply -f prometheus/
