# paper-readings
a reading lists about paper

# books

- [x] 《DDIA》
- [ ] 《Streaming System》
- [ ] 《Fault-Tolerant Message-Passing Distributed Systems》

# Database system

## Survey
- [x] OLTP Through the Looking Glass, and What We Found There, SIGMOD, 2008 [[pdf](https://15721.courses.cs.cmu.edu/spring2020/papers/02-inmemory/hstore-lookingglass.pdf)]

## Optimizer
- [x] Access Path Selection in a Relational Database Management System, SIGMOD 1979 [[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.71.3735&rep=rep1&type=pdf)]
- [x] Query Processing in Main Memory Database Management Systems, VLDB 1979 [[pdf](http://15721.courses.cs.cmu.edu/spring2016/papers/p239-lehman.pdf)]
- [ ] The Volcano Optimizer Generator- Extensibility and Efficient Search, ICDE 1993 [[pdf](https://pdfs.semanticscholar.org/a817/a3e74d1663d9eb35b4baf3161ab16f57df85.pdf)]
- [ ] The Cascades Framework for Query Optimization, IEEE Data engineering Bulltin, 1995 [[pdf](https://pdfs.semanticscholar.org/360e/cdfc79850873162ee4185bed8f334da30031.pdf)]
- [ ] An Overview of Query Optimization in Relational Systems, PODS, 1998 [[pdf](https://web.stanford.edu/class/cs345d-01/rl/chaudhuri98.pdf)]
- [ ] Orca: A Modular Query Optimizer Architecture for Big Data, 2014, SIGMOD [[pdf](http://15721.courses.cs.cmu.edu/spring2016/papers/p337-soliman.pdf)]
- [ ] The MemSQL Query Optimizer: A modern optimizer for real-time analytics in a distributed database, VLDB, 2016 [[pdf](http://www.vldb.org/pvldb/vol9/p1401-chen.pdf)]

## Transaction


## Storage

## data warehouse and datalake


## TP

## AP

# Distributed system

## Theoretical results
- [x] Time, Clocks, and the Ordering of Events in a Distributed System, CACM 1978  [[acmdl](https://dl.acm.org/citation.cfm?id=359563),[pdf](https://lamport.azurewebsites.net/pubs/time-clocks.pdf)]
- [ ] The implementation of reliable distributed multiprocess systems, Computer Networks 1978 [[pdf](https://www.microsoft.com/en-us/research/publication/implementation-reliable-distributed-multiprocess-systems/)]
- [x] Impossibility of Distributed Consensus with One Faulty Process, JACM 1985 [[acmdl](https://dl.acm.org/citation.cfm?id=214121),[pdf](https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf)]
- [ ] Unreliable Failure Detectors for Reliable Distributed Systems, JACM 1996 [[acmdl](https://dl.acm.org/citation.cfm?id=226647),[pdf](https://www.cs.utexas.edu/~lorenzo/corsi/cs380d/papers/p225-chandra.pdf)]

## Consensus Algorithms
- [x] The Part-Time Parliament, TOCS 1998 [[acmdl](https://dl.acm.org/citation.cfm?id=279229),[pdf](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf)]


## Consensus in production
This section lists papers describing experiences of deploying distributed consensus in production.
- [x] The Chubby lock service for loosely-coupled distributed systems, OSDI 2006 [[acmdl](https://dl.acm.org/citation.cfm?id=1298487),[pdf](https://static.googleusercontent.com/media/research.google.com/en//archive/chubby-osdi06.pdf)]
- [x] Paxos Made Live - An Engineering Perspective, PODC 2007 [[acmdl](https://dl.acm.org/citation.cfm?id=1281103),[pdf](https://www.cs.utexas.edu/users/lorenzo/corsi/cs380d/papers/paper2-1.pdf)]
- [x] ZooKeeper: Wait-free coordination for Internet-scale systems, ATC 2010 [[acmdl](https://dl.acm.org/citation.cfm?id=1855840.1855851),[pdf](https://www.usenix.org/legacy/event/atc10/tech/full_papers/Hunt.pdf)]
- [ ] Zab: High-performance broadcast for primary-backup systems, DSN 2011 [[acmdl](https://dl.acm.org/citation.cfm?id=2056409),[pdf](https://knowably-attachments.s3.amazonaws.com/u/55b69a1ce4b00ab397d67250/7c8734d3cf02154499a9b3161ef9f575/Zab_2011.pdf)]
- [ ] Megastore: Providing Scalable, Highly Available Storage for Interactive Services, CIDR 2011 [[pdf](http://cidrdb.org/cidr2011/Papers/CIDR11_Paper32.pdf)]