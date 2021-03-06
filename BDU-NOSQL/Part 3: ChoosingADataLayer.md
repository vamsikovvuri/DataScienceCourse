Choosing a Data Layer for Your Application Script
==================================================
* This third lesson introduces you to the concept of Database-as-a-Service along with several important
considerations for choosing a database technology. *

### Considerations
This lesson differentiates your database hosting options and examines the relevant factors and
considerations to determine an appropriate data layer.

First consider the types of questions you need to ask your database and how long you are willing to wait
for answers. If you have a web or mobile application that requires interactive responses, then you will
want to use a database that aims to be an operational datastore. NoSQL databases may be a good choice.
If your application requires datawarehousing for batch analytics, then often a relational database or
Hadoop-based technology would be a better fit.

Second, it’s important to consider how big your data will get and how many concurrent connections you
expect. If you need a really scalable solution, don’t completely know your capacity requirements up front,
or need something that scales as your application grows, then a NoSQL database might be a good choice.

Also consider whether or not you need the database to scale horizontally. If your applications are running
in the cloud, then you need your database solution to be compatible with the underlying architecture.
Many NoSQL databases offer horizontal scalability that fits well with cloud architectures.

#### Data Durability
Data durability is an important consideration based on your application requirements. Some databases
offer the ability to store your data in memory for faster access. However, with this approach, there is an
increased risk of losing the data when a server crashes. If data durability is paramount, then choose a
database that writes the data immediately to disk.

Next, consider your consistency and transactional requirements. Relational databases provide strong
consistency and transactional rollback capabilities, and would be a good choice if you have a use case that
requires these traits.

----------------------------------------------------------------------------
### Other Considerations
Other considerations relate to your availability, replication, and geo-location requirements. Many NoSQL
databases operate inherently in a cluster, and therefore can meet stringent high availability requirements.

#### Data Replication
Data replication is an important feature to achieve disaster recovery objectives by storing the data in
additional data centers, and allow for syncing to application clients for offline access. A few, but not all,
NoSQL databases are built to handle these complex replication scenarios while avoiding data corruption.

#### Flexible Schemas
Flexible schemas are a common trait amongst many NoSQL databases. If you require a flexible schema for
rapid development where your data model may change over time, then you will often want to go with a
NoSQL database for your application. Many of them require no database downtime while making schema
changes, making development easier and faster.

It is important to assess the skill sets of those developing the application, and administering the database
and servers. Make sure you choose a technology that fits with your existing resources before bringing it
on-premise in your environment. 

Think about whether or not your database layer can integrate easily with your application layer. For web
and mobile applications that use JSON, it makes sense to use a NoSQL database that also uses JSON.
However, if the business intelligence tools (or reporting dashboard) are expecting to consume
rows/columns, then a relational datastore might work better for you.

A few final considerations for choosing the best database for your application are around where to host it
and how it is being managed. It is important to understand all of the components to make sure you end
up with the simplest and most cost effective option.

--------------------------------------------------------------------------

### Databases As A Service

In a traditional do-it-yourself scenario, you will own the setup of the underlying hardware and operating
system, installation and configuration of the chosen database management system, overall administration
including patching and support, and of course how the application data is designed.

In comparison, using a fully managed database-as-a-service is really meant to eliminate the complexity
and risk of DIY, and help development teams get to market faster, scale more smoothly and massively,
and provide better performance and availability for end users.

This contrasts a little bit with hosted database solutions. A hosted database solution means the provider is
choosing what hardware your database runs on, and they’re provisioning it for you. So at the end of the
day, they’re handing the administrative keys over to you and it’s really up to your team of database
administrators to keep things scaling and running smoothly. That can end up being a distraction for
developers and result in overhead costs that most companies don’t want to bear these days.

The only concern for users of database-as-a-service is the design and development of their product!
* Guaranteed uptime, availability, and scalability are all the result of a fully-managed service!
* You can mitigate risk by offloading database administration and data layer management issues
from your development team.
* And you ensure that your developers need only concern themselves with what really matters –
developing better applications for your customers.
