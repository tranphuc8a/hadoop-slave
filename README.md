# hadoop-master

Cài hadoop và ghi đè 2 folder này vào thư mục hadoop

Cụm hadoop 3 node (1 namenode + 2 datanode).


Cấu hình hostname cho 3 node:
	namenode 	<<IP namenode>>
	datanode1 	<<IP datanode 1>>
	datanode2	<<IP datanode 2>>

Yêu cầu 3 node:
	- Chung network
	- Thống nhất chứng chỉ ssh
	- Cài đặt Java SDK

Cấu hình biến môi trường:
	export HADOOP_HOME=/path/to/hadoop
	export PATH=$PATH:$HADOOP_HOME/bin
	export PATH=$PATH:$HADOOP_HOME/sbin
	export HADOOP_MAPRED_HOME=${HADOOP_HOME}
	export HADOOP_COMMON_HOME=${HADOOP_HOME}
	export HADOOP_HDFS_HOME=${HADOOP_HOME}
	export YARN_HOME=${HADOOP_HOME}
	export JAVA_HOME=/path/to/java (ex: /usr/lib/jvm/java-8-openjdk-amd64)


