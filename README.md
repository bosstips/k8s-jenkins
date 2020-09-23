
# k8s部署jenkins系统按照下面操作即可。



### 按照分别在master和node按照服务在存储节点执行下面操作 nfs
### yum -y install NFS-*

### mkdir -p /data/v1

### chown -R 1000 /data/v1

### echo "/data/v1  192.168.15.0/24(rw,no_root_squash) " >> /etc/exports 

### systemctl   restart   nfs
