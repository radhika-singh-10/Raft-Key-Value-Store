# Raft-Key-Value-Store

#### A fundamental problem in distributed computing and multi-agent systems is to achieve overall system reliability in the presence of a number of faulty processes. This often requires coordinating processes to reach a consensus or agree on some data value that is needed during computation. Example applications of consensus include agreeing on what transactions to commit to a database in which order, state machine replication, and atomic broadcasts


## how to run it locally

```shell
git clone https://github.com/radhika-singh-10/Raft-Key-Value-Store.git
cd Raft-Key-Value-Store
```
### install dependencies
```shell
make install
```
### create necessary directories
```shell
make create-dirs
```

### start a 3 member cluster
```shell
make run-cluster
```

### stop a cluster 
```shell
make stop-cluster
```

### cleanup 
```shell
make clean
```
