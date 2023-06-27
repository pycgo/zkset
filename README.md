# zkset
## 用途

替换zk的节点的文件内容 有些时候某些特殊字符开头的文件原生的cli不支持替换，所以单独写了一个工具



## 使用方法

```shell
zkset  -file=/opt/test.yaml -zkpath=/test -zookeeper=zookeeper:2181
```
