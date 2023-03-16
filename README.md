# Paper Reading List 📚

a reading lists about paper

The sections are as follows:
- [Paper Reading List 📚](#paper-reading-list-)
  - [Database system](#database-system)
    - [Books](#books)
    - [Survey](#survey)
    - [Query Optimizer](#query-optimizer)
    - [Transaction](#transaction)
    - [Indexes Data Structures](#indexes-data-structures)
      - [LSM-Tree](#lsm-tree)
      - [Learned Indexes Structures](#learned-indexes-structures)
    - [Query Execution \& Processing](#query-execution--processing)
    - [Query Compilation](#query-compilation)
    - [Data warehouse and Datalake](#data-warehouse-and-datalake)
    - [NoSQL Systems](#nosql-systems)
    - [NewSql Systems](#newsql-systems)
    - [HTAP](#htap)
    - [Benchmark \& Testing](#benchmark--testing)
  - [Distributed system](#distributed-system)
    - [Books](#books-1)
    - [Theoretical results](#theoretical-results)
    - [Consensus Algorithms](#consensus-algorithms)
    - [Consensus in production](#consensus-in-production)


## Database system

### Books
- [X] [Database System Concepts, Seventh Edition](https://www.db-book.com/)
- [ ] [Readings in Database Systems, 5th Edition](http://www.redbook.io/)

### Survey
- [x] [OLTP Through the Looking Glass, and What We Found There, SIGMOD, 2008](https://15721.courses.cs.cmu.edu/spring2020/papers/02-inmemory/hstore-lookingglass.pdf)

### Query Optimizer
- [x] [Access Path Selection in a Relational Database Management System, SIGMOD 1979](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.71.3735&rep=rep1&typ)
- [x] [Query Processing in Main Memory Database Management Systems, VLDB 1979](http://15721.courses.cs.cmu.edu/spring2016/papers/p239-lehman.pdf)
- [ ] [The Volcano Optimizer Generator- Extensibility and Efficient Search, ICDE 1993](https://pdfs.semanticscholar.org/a817/a3e74d1663d9eb35b4baf3161ab16f57df85.pdf)
- [ ] [The Cascades Framework for Query Optimization, IEEE Data engineering Bulltin, 1995](https://pdfs.semanticscholar.org/360e/cdfc79850873162ee4185bed8f334da30031.pdf)
- [ ] [An Overview of Query Optimization in Relational Systems, PODS, 1998](https://web.stanford.edu/class/cs345d-01/rl/chaudhuri98.pdf)
- [ ] [Efficiency in the Columbia Database Query Optimizer](https://15721.courses.cs.cmu.edu/spring2018/papers/15-optimizer1/xu-columbia-thesis1998.pdf)
- [ ] [Orca: A Modular Query Optimizer Architecture for Big Data, 2014, SIGMOD](http://15721.courses.cs.cmu.edu/spring2016/papers/p337-soliman.pdf)
- [ ] [The MemSQL Query Optimizer: A modern optimizer for real-time analytics in a distributed database, VLDB, 2016](http://www.vldb.org/pvldb/vol9/p1401-chen.pdf)
- [ ] [How Good Are Query Optimizers, Really?, 2015](https://15721.courses.cs.cmu.edu/spring2020/papers/22-costmodels/p204-leis.pdf)

### Transaction
- [ ]  [On Optimistic Methods for Concurrency Control, ACM Transactions on Database Systems， 1981]()
- [ ]  [Multiversion Concurrency Control - Theory and Algorithms, ACM Transactions on Database Systems, 1983](https://sites.fas.harvard.edu/~cs265/papers/bernstein-1983.pdf)
- [x]  [a uniform definition to isolation levels, ANSI SQL-92 standard](https://renenyffenegger.ch/notes/development/databases/SQL/transaction/isolation-level)
- [x]  [A Critique of ANSI SQL Isolation Levels, SIGMOD, 1992](https://www.cs.umb.edu/cs734/CritiqueANSI_Iso.pdf)
- [ ]  [Weak Consistency: A Generalized Theory and Optimistic Implementations for Distributed Transactions, Atul Adya, with his PhD Thesis, 1999](http://publications.csail.mit.edu/lcs/pubs/pdf/MIT-LCS-TR-786.pdf)
- [ ]  [Generalized-Isolation-Level-Definitions, Atul Adya, 1999](https://pmg.csail.mit.edu/papers/icde00.pdf)
- [ ]  [Making-Snapshot-Isolation-Serializable, Alan Fekete, 2005](https://www.cse.iitb.ac.in/infolab/Data/Courses/CS632/2015/2013/2011/Papers/p492-fekete.pdf)
- [ ]  [Serializable Isolation for Snapshot Databases, Alan Fekete, 2008](https://ses.library.usyd.edu.au/bitstream/handle/2123/5353/michael-cahill-2009-thesis.pdf)
- [ ]  [A critique of snapshot isolation, Maysam Yabandeh, 2012](https://dl.acm.org/doi/pdf/10.1145/2168836.2168853)
- [ ]  [Serializable snapshot isolation in PostgreSQL, 2012](https://arxiv.org/pdf/1208.4179.pdf)
- [ ]  [High-Performance Concurrency Control Mechanisms for Main-Memory Databases, VLDB, 2011](https://15721.courses.cs.cmu.edu/spring2020/papers/04-mvcc2/p298-larson.pdf)
- [ ]  [Fast Serializable Multi-Version Concurrency Control for Main-Memory Database Systems, SIGMOD, 2015](https://15721.courses.cs.cmu.edu/spring2020/papers/04-mvcc2/p677-neumann.pdf)
- [ ]  [Scalable Serializable Snapshot Isolation for MulticoreSystems, ICDE, 2014](https://ieeexplore.ieee.org/abstract/document/6816693/)
- [ ]  [Cicada: Dependably Fast Multi-Core In-Memory Transactions, SIGMOD, 2017](https://15721.courses.cs.cmu.edu/spring2020/papers/04-mvcc2/lim-sigmod2017.pdf)
- [X]  [An Empirical Evaluation of In-Memory Multi-Version Concurrency Control, VLDB, 2017](http://www.vldb.org/pvldb/vol10/p781-Wu.pdf)
- [ ] [An Evaluation of Distributed Concurrency Control, VLDB, 2017](https://www.vldb.org/pvldb/vol10/p553-harding.pdf)

### Indexes Data Structures
#### LSM-Tree
- [ ] [The Log-Structured Merge-Tree (LSM-Tree), 1996](https://www.cs.umb.edu/~poneil/lsmtree.pdf)
- [ ] [A Comparison of Fractal Trees to Log-Structured Merge (LSM) Trees, 2014](http://www.pandademo.com/wp-content/uploads/2017/12/A-Comparison-of-Fractal-Trees-to-Log-Structured-Merge-LSM-Trees.pdf)
- [ ] [WiscKey: Separating Keys from Values in SSD-conscious Storage, TOS, 2017](https://www.usenix.org/system/files/conference/fast16/fast16-papers-lu.pdf)
- [ ] [LSM-based Storage Techniques: A Survey, 2019](https://arxiv.org/pdf/1812.07527.pdf)

#### Learned Indexes Structures
- [ ] [The Case for Learned Index Structures, 2018](https://www.cl.cam.ac.uk/~ey204/teaching/ACS/R244_2018_2019/papers/Kraska_SIGMOD_2018.pdf)
- [ ] [Learning Multi-dimensional Indexes, 2020](https://arxiv.org/pdf/1912.01668.pdf)
- [ ] [adixSpline: A Single-Pass Learned Index, Source Code, SIGMOD, 2020](http://www.pandademo.com/wp-content/uploads/2017/12/A-Comparison-of-Fractal-Trees-to-Log-Structured-Merge-LSM-Trees.pdf)
- [ ] [The PGM-index: a fully-dynamic compressed learned index with provable worst-case bounds, Source Code, VLDB, 2020](https://dl.acm.org/doi/pdf/10.1145/3332466.3374547)
- [ ] [From WiscKey to Bourbon: A Learned Index for Log-Structured Merge Trees, 2020](http://pages.cs.wisc.edu/~yifann/bourbon-osdi20.pdf)

### Query Execution & Processing
- [ ] [Volcano-An Extensible and Parallel Query Evaluation System, IEEE Transactions on Knowledge and Data EngineeringFebruary, 1994](https://paperhub.s3.amazonaws.com/dace52a42c07f7f8348b08dc2b186061.pdf)
- [ ] [MonetDB/X100: Hyper-Pipelining Query Execution, 2005](https://15721.courses.cs.cmu.edu/spring2018/papers/18-execution/boncz-cidr2005.pdf)
- [ ] [Vectorization vs. Compilation in Query Execution, 2011](https://15721.courses.cs.cmu.edu/spring2016/papers/p5-sompolski.pdf)
- [ ] [Rethinking SIMD Vectorization for In-Memory Databases, SIGMOD, 2015](http://www.cs.columbia.edu/~orestis/sigmod15.pdf)
- [ ] [Morsel-Driven Parallelism: A NUMA-Aware Query Evaluation Framework for the Many-Core Age, SIGMOD, 2014](https://15721.courses.cs.cmu.edu/spring2019/papers/14-scheduling/p743-leis.pdf)
- [ ] [Push vs. Pull-Based Loop Fusion in Query Engines, 2016](https://arxiv.org/abs/1610.09166)

### Query Compilation

### Data warehouse and Datalake
- [ ] [The Snowflake Elastic Data Warehouse, SIGMOD, 2016](https://pages.cs.wisc.edu/~remzi/Classes/739/Spring2004/Papers/p215-dageville-snowflake.pdf)
- [ ] [Building An Elastic Query Engine on Disaggregated Storage, NSDI, 2020](https://www.usenix.org/system/files/nsdi20-paper-vuppalapati.pdf)

### NoSQL Systems
- [ ] [Bigtable: A Distributed Storage System for Structured Data, OSDI, 2006](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
- [ ] [Dynamo: Amazon’s Highly Available Key-value Store, SOSP, 2007](https://sites.cs.ucsb.edu/~agrawal/fall2009/dynamo.pdf)
- [ ] [Cassandra - A Decentralized Structured Storage System, SOSP, 2010](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf)

### NewSql Systems
- [ ] [Spanner: Google’s Globally-Distributed Database, OSDI,2012](https://static.googleusercontent.com/media/research.google.com/zh-CN//archive/spanner-osdi2012.pdf)

### HTAP
- [ ] [F1 Lightning: HTAP as a Service, VLDB, 2020](http://www.vldb.org/pvldb/vol13/p3313-yang.pdf)
- [ ] [TiDB: A Raft-based HTAP Database, VLDB, 2020](http://www.vldb.org/pvldb/vol13/p3072-huang.pdf)

### Benchmark & Testing
- [ ] [Benchmarking Cloud Serving Systems with YCSB, SOCC, 2010](https://courses.cs.duke.edu/fall13/compsci590.4/838-CloudPapers/ycsb.pdf)

## Distributed system

### Books
- [x] [Designing Data-Intensive Applications, Martin Kleppmann](https://dataintensive.net/)
- [x] [Distributed Systems for fun and profit, Mikito Takada](http://book.mixu.net/distsys/single-page.html)
- [ ] [Patterns of Distributed Systems](https://martinfowler.com/articles/patterns-of-distributed-systems/)
- [ ] [Streaming Systems: The What, Where, When, and How of Large-Scale Data Processing](https://www.oreilly.com/library/view/streaming-systems/9781491983867/)

### Theoretical results
- [x] [Time, Clocks, and the Ordering of Events in a Distributed System, CACM 1978 ](https://lamport.azurewebsites.net/pubs/time-clocks.pdf)
- [ ] [The implementation of reliable distributed multiprocess systems, Computer Networks 1978](https://www.microsoft.com/en-us/research/publication/implementation-reliable-distributed-multiprocess-systems/)
- [x] [Impossibility of Distributed Consensus with One Faulty Process, JACM 1985](https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf)
- [ ] [Unreliable Failure Detectors for Reliable Distributed Systems, JACM 1996](https://www.cs.utexas.edu/~lorenzo/corsi/cs380d/papers/p225-chandra.pdf)

### Consensus Algorithms
- [x] [The Part-Time Parliament, TOCS 1998](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf)


### Consensus in production
This section lists papers describing experiences of deploying distributed consensus in production.
- [x] [The Chubby lock service for loosely-coupled distributed systems, OSDI 2006](https://static.googleusercontent.com/media/research.google.com/en//archive/chubby-osdi06.pdf)
- [x] [Paxos Made Live - An Engineering Perspective, PODC 2007](https://www.cs.utexas.edu/users/lorenzo/corsi/cs380d/papers/paper2-1.pdf)
- [x] [ZooKeeper: Wait-free coordination for Internet-scale systems, ATC 2010](https://www.usenix.org/legacy/event/atc10/tech/full_papers/Hunt.pdf)
- [ ] [Zab: High-performance broadcast for primary-backup systems, DSN 2011](https://knowably-attachments.s3.amazonaws.com/u/55b69a1ce4b00ab397d67250/7c8734d3cf02154499a9b3161ef9f575/Zab_2011.pdf)
- [ ] [Megastore: Providing Scalable, Highly Available Storage for Interactive Services, CIDR 2011](http://cidrdb.org/cidr2011/Papers/CIDR11_Paper32.pdf)