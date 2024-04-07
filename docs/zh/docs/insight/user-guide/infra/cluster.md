# 集群监控

集群监控可查看集群的基本信息，该集群中的资源消耗以及一段时间的资源消耗变化趋势。

## 前提条件

集群中已安装 insight-agent 且应用处于 __运行中__ 状态。

## 操作步骤

1. 进入 __可观测性__ 产品模块。
  
2. 在左边导航栏选择 __基础设施 > 集群__ 。在该页面可查看以下信息：

    1. **集群列表** ：已安装 insight-agent 的集群列表，可点击目标集查看对应详细信息；
    2. **资源概览** ：多选集群中的节点、工作负载的正常和全部的数量统计；
    3. **故障** ：统计当前集群产生的告警数量；
    4. **资源消耗** ：所选集群的 CPU、内存、磁盘的实际使用量和总量；
    5. **指标说明** ：所选集群的 CPU、内存、磁盘读写、网络接收发送的变化趋势。

    ![容器监控](https://docs.daocloud.io/daocloud-docs-images/docs/zh/docs/insight/images/cluster00.png)

### 指标说明

| 指标名 | 说明 |
| -- | -- |
| CPU 使用率 | 该指标是指集群中所有 Pod 资源的实际 CPU 用量与所有节点的 CPU 总量的比率。|
| CPU 分配率 | 该指标是指集群中所有 Pod 的 CPU 请求量的总和与所有节点的 CPU 总量的比率。|
| 内存使用率 | 该指标是指集群中所有 Pod 资源的实际内存用量与所有节点的内存总量的比率。|
| 内存分配率 | 该指标是指集群中所有 Pod 的内存请求量的总和与所有节点的内存总量的比率。|