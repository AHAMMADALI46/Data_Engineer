# Data_Engineer
Difference between Data Engineer & Data Scientist?
Data engineer: Develops, constructs, tests and maintain architectures, such as databases and large-scale processing systems.
Data scientist: Performs descriptive statistics and analysis to develop insights, build models and solve a business need.

Data engineering: 1. Focuses on practical applications of data collection and analysis.
2. Extraction /collection
3. Transformation/Enrichment
4. Analysis
5. Cleaning & Quality.

Day to Day tasks of a Data Engineer:
1. Participate in scrum meetings-task updates, backlog refinement etc.
2. meeting with stake holders, end user, managers
3. learn, unlearn and relearn
4. discuss about the tasks 
5. code & demo scalable frameworks/data pipelines
6. monitor existing pipelines.
7. Support testing activities, fix bugs etc.

The 5 Vs of Big Data
1. Volume: The size of the data
2. Velocity: The speed at which the data is generated
3. Variety: The different types of data
4. Veracity: The trustworthiness of the data in terms of accuracy
5. Value: Just having Big data is of no use unless, we can turn it into value.
 
Common Problems-Traditional systems:
1. Unimaginable size of data
2. Heterogenous systems
3. Traditional systems do not scale up
4. RDBMS is costly
5. Building single system is complex and not cost effective
6. Data analysis, Machine learning and predictive analysis do not have a common infrastructure.


Possible solutions:
Scale up:
1. increase the configuration of a single system, like disk capacity, RAM, data transfer speed, etc.
2. Complex, costly and a time consuming process.

Scale out:
1. Use multiple commodity (economical) machines and distribute the load of storage/processing among them
2. Economical and quick to implement as it focuses on distribution of load.
3. Instead of having a single system with 10 TB of storage and 80 GB of RAM, use 40 machines with 256GB of storage and 2GB of RAM.


Challenges of Scaling out:
Need a new system:
1. with new database management other than relational databases capable of handling unstructured as well as structured data.
2. To process huge datasets on large clusters of computers than on a single system.

To manage clusters in which:
1. Nodes fail frequently
2. Number of nodes keep changing
3. Take care of communication between the nodes
4. During analysis, take results from different machines and merge/aggregate them.

How to solve the problems we need common infrastructure which is:
1. Efficient
2. Easy to use
3. Reliable.

What is Hadoop?
1. open source distributed data processing cluster
2. Data processed in Hadoop Distributed file system (HDFS)
3. Hadoop is that new framework which helps to solve the problem of data explosion.
4. Hadoop is an open source, Java-based programming framework that supports the processing of large datasets in a distributed computing environment.
5. Hadoop provides: A reliable, scalable platform for storage and analysis.
6. it is based on Google file system or GFS.
7. Hadoop runs a number of applications on distributed systems with thousands of nodes involving petabytes of data.
8. It has a distributed file system, called the Hadoop Distributed file system or HDFS, which enables fast data transfer among the nodes.
9. It leverages a distributed computation framework called Map reduce.
10. Resource Management is performed by YARN.
