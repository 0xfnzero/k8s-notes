# k8s-notes

Kubernetes 学习笔记和脚本集合，包含 Docker/Kubernetes 集群安装脚本、Flannel 配置，以及 Nginx Deployment/Service/扩缩容/滚动发布示例。

## 这个仓库提供什么

| 方向 | 内容 |
| --- | --- |
| 集群安装 | Docker、kubeadm、kubelet、kubectl、master/node 初始化脚本 |
| 网络插件 | Flannel YAML 配置 |
| 应用部署 | Nginx Deployment 和 NodePort Service 示例 |
| 运维练习 | 副本扩缩容、滚动发布、基础排障命令 |
| 使用场景 | Kubernetes 入门笔记、kubeadm 实验环境、CentOS/YUM 环境脚本参考 |

## 目录

1. [自动化脚本安装 Docker 和 Kubernetes 集群环境](https://github.com/0xfnzero/k8s-notes/tree/master/install-k8s)
2. [使用 Kubernetes 部署应用、弹性伸缩、滚动发布](https://github.com/0xfnzero/k8s-notes/tree/master/deployment-nginx)
