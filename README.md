# Hadoop
1 Hadoop includes HDFS and Mapreduce. HDFS is called Hadoop Distributed File System,which is used to store big data such as
metabyte,petabyte.
2 In HDFS, data is stored in Cluster, which includes many datanodes and namenodes. In different datanodes, data will be
separated in there. In order to avoid the loss of data, every part of data will be replicated three times. Meanwhile, there are
two namenodes, one active, one standby. Besides, we also use remote method to restore the data in namenode
MetaData will be stored in Namenode.
