# 自定义k8s node api接口

> Node 是 Kubernetes 中的工作节点。 每个节点在缓存中（即在 etcd 中）都有一个唯一的标识符。 也就是现实中的机器资源

## 读取指定节点(标签)

- 节点所有信息
  - 节点名称
  - 节点标签
  - 节点标注
  - 节点创建时间
  - 节点系统信息
  - 节点所在镜像信息
  - 节点pod信息
  - 局域网ip
  - hostname
  - 系统资源占用情况


## 读取指定节点的状态

- 节点运行状态
- 节点资源占用


节点运行到那一步

## 列出或监视节点类型的对象

获取节点列表
 - 节点名
 - 节点标签
 - 创建时间
 - 资源占用（内存 CPU）
 - pod数量
 - node是否准备好

## 创建一个节点

通过yaml文件/json文件更新系节点

## 替换指定节点

通过yaml文件/json文件更新系节点

## 添加标签

## 删除标签

## 批量删除

## 批量添加

## 删除一个节点 

删除单个节点

## 删除节点的集合

删除多个节点