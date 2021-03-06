Introducing NoSQL Script
=================================================================

*This lesson defines the term NoSQL and the technology it references. It describes NoSQL history in the
database landscape, explains concepts and characteristics of NoSQL databases, and lists the primary
benefits to adopting a NoSQL database.*

First, let’s talk about the name NoSQL. The name was introduced at an event to discuss all of the new
open-source distributed databases that were coming onto the scene, and the name, NoSQL, has stuck
ever since. NoSQL describes what it is not meaning it refers to a family of databases that vary widely in
style and technology, but all share a common trait in that they are non-relational in nature, meaning they
are not a standard row and column RDBMS. Therefore a better name to describe these databases would
be non-relational.

NoSQL databases provide new ways of storing and querying data that address a number of issues for
modern applications. Most importantly, the majority of NoSQL databases are geared to handle a different
breed of scale problems that have arisen associated with the “big data” movement. By scale, we are
referring to both the size of the data, but also the concurrent users acting on that data. NoSQL databases
also are typically more specialized to various use cases and can be much simpler to develop application
functionality than relational databases. We’ll get into more detail on the benefits of NoSQL in a moment.

Let’s take a quick look at the history of the NoSQL movement. Going back 10 years or so, when application
architects and developers needed a data store for their applications, they pretty much were choosing
amongst of variety of relational databases. Oracle, MySQL, SQL Server, and DB2 being some of the more
popular ones. When internet applications and companies started exploding during the dotcom boom in le
ate 90’s/early 2000’s, applications went from predominately serving thousands of internal employees at
companies to having millions of users on the public internet. 

For these applications, availability and
performance were paramount and these new scale problems led to a drive to create new scalable
technologies to support them. Several large tech companies at this time developed a lot of great
technology, and in turn released white papers and/or open sourced the technology to the community.
Specific examples include Google’s MapReduce white paper describing how to process large data sets on
distributed systems and Amazon’s Dynamo paper which details a way to evenly distribute data and
workload in a cluster in a quorum style architecture.

In the late 2000’s, several new databases emerged on the scene, a large number of them from the open
source communities. Databases like Apache CouchDB, Cassandra, and Hbase, as well as Mongo and Riak
became more prevalently used in applications, particularly in ones that required larger scale than a
relational database could handle. In the last 5 years or so, several NoSQL databases have leveraged a fully
managed service model, otherwise called, database-as-a-service to offload the administration and
maintenance from the end user and allow developers to focus on building applications with these modern
databases.

So you’ve already heard that the most common trait amongst NoSQL databases is that they are nonrelational
in architecture. But what kinds of NoSQL databases exist? And what is common amongst them?
Several efforts have been made to categorize NoSQL databases and in the market there is a general
consensus that they fit into four types: Key-Value, Document, BigTable (also called Column-Oriented) 
and Graph style NoSQL databases. There is some overlap amongst these types so the definition isn’t
always clear, but you’ll hear more details on the different types and use cases in the next lesson.
What ties NoSQL databases together? One commonality is that a lot of them have their roots in the open
source community and have been used and leveraged in an open source manner. This has been
fundamental for spring-boarding their growth in the industry. You’ll often see companies who also
provide a commercial version of the database, and services and support of the technology, at the same
time providing sponsorship of the open source counterpart. Examples of this include Datastax for Apache
Cassandra, IBM Cloudant for CouchDB, and Mongo has their own open source version of the Mongo
database.

Technically speaking they all differ quite a bit, but a few commonalities do emerge. Most NoSQL
databases are built to horizontally scale and share their data more easily than relational counterparts and
to do this often require unique keys across whole databases. They also are more specialized than RDMBS
which previously have been the Swiss army knives of datastores and developers are drawn to them for
the ease of data modeling and use. Finally, many NoSQL databases allow more agile development via
flexible schemas vs. the fixed schemas of relational databases.
So we have covered what NoSQL means, its history in the database technology world, and some basics of
what makes up a NoSQL database. But why would you use a NoSQL database? Why is the popularity of
these databases growing at such a rapid rate? The list is long, so we’ve included some of the more
common ones here. Let’s briefly touch on each topic, keeping in mind that not all NoSQL databases will
exhibit all of these benefits.
First, the most common reason to employ a NoSQL database is for scalability, particularly the ability to
horizontally scale across clusters of servers, racks, and possibly even data centers. The elasticity of scaling
both up and down to meet the varying demands of applications is key. NoSQL databases are well suited to
meet the large data size and huge amount of concurrent users that “Big Data” applications exhibit.
The second point of performance goes hand-in-hand with scalability. The need to deliver fast response
times even with large data sets and high concurrency is a must for modern applications, and the ability of
NoSQL databases to leverage the resources of large clusters of servers makes them ideal for fast
performance in these circumstances.

High Availability is an obvious requirement for a database, and having a database run on a cluster of
servers with multiple copies of the data makes for a more resilient solution than a single server solution.
Modern enterprises are employing cloud architectures to support their applications. Historically, large
databases have run on expensive machines or mainframes. The already covered distributed data nature of
NoSQL databases means that they can be deployed and operated on clusters of servers in cloud
architectures.

Cost is important for any technology venture, and it is common to hear of NoSQL adopters cutting
significant costs vs. their existing databases…..and able to get the same or better performance and
functionality.

Flexible schema and intuitive data structures are key features that developers love when wanting to build
applications efficiently. Most NoSQL databases allow for having flexible schemas, which means that one 
can build new features into applications quickly and without any databases locking or downtime. NoSQL
databases also have varied data structures which often are more eloquent for solving development needs
than the rows and columns of relational datastores. Examples include key-value stores for quick lookup,
document stores for storing de-normalized intuitive information, and graph databases for associative data
sets.

There are also various specialized capabilities that certain NoSQL providers offer that attract end users.
Examples include specific indexing and querying capabilities such as geospatial or search, data replication
robustness, and modern HTTP API’s.

With all this goodness you might wonder why anyone would ever use anything but a NoSQL database,
right? Well, you might say this is true for most cases these days, but there are definitely still many
requirements which are best met with an RDBMS. We’ll cover that in lesson 3 of this course.
That brings us to the end of the first lesson in the Introducing NoSQL & Database-as-a-Service course. This
lesson defined the term NoSQL, the technology it references, its history in the database landscape, and
explained concepts, characteristics, and benefits of NoSQL databases.
The next lesson will dive into the various types of NoSQL databases.
