Hadoop is a scalable, open source, fault-tolerant Virtual Grid operating system architecture for data storage and processing. 
It runs on commodity hardware, it uses HDFS (Hadoop Distributed File System) which is fault-tolerant high bandwidth clustered storage architecture. 
It runs MapReduce for distributed data processing and it works with structured and unstructured data. HDFS is a distributed file system that stores 
and manages the data in a Hadoop cluster. A central node called NameNode to store the meta-data of the file system. The NameNode is running on the Master node. 
The other nodes are called DataNodes that store the data. These can run on both, Slave and Master nodes. Files in HDFS are split into smaller blocks and each 
block is stored separately at a DataNode and replicated as specified in the configuration of Hadoop to provide data durability. All blocks in a file except the 
last block are the same size. This size can be specified in the configuration files of Hadoop. A HDFS client contacts the NameNode to get the location of each block, 
and then interacts with DataNodes, that are responsible for the requested data. Hadoop MapReduce Framework consists of two types of components that control the 
job execution process: a central component called the ResourceManager and a number of distributed components called NodeManagers. Based on the location of a job’s 
input data, the ResourceManager schedules tasks to run on some NodeManagers and coordinates their execution of the job. NodeManagers run tasks assigned to them and 
send progress reports to the ResourceManager.
 
Modern smartphones provide a high-performance hardware, which is not fully capitalized, during everyday usage. Based on this, it would be interesting moving data 
processing tasks, commonly used in big data environments, on the private smartphone of its user. In previous works it could be discovered, that Apache Hadoop is 
executable on primitive hardware ressources such as Intel Galileo development boards. The basic idea of this project, is to investigate the possibility  of running 
an Apache Hadoop cluster on a smartphone based infrastructure.
 
> Task/Aufgabe
> Investigate whether it is possible to transfer a common Apache Hadoop cluster to an Android smartphone-based infrastructure
> Alternatively, development of a primitive Map-Reduce framework for Android smartphones