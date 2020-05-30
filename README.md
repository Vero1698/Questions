# Big Data Principles and Best Practices of Scalable Realtime Data Systems
# Chapter 1
### Question 1:
#### What can be a big problem when using a traditional database?
One of the problems may be the saturation of request to save data in the database directly because the database can't keep up withthe load, so write requests to increment pageviews are timing out.

### Question 2:
#### What is horizontal partitioning  or  sharding?
The sharing technique uses multiple database servers, which are seen as small subsets on different machines or servers that choose the shard for each key by taking thehash  of  the  key  modded  by  the  number  of  shards.

### Question 3:
#### What are the main problems that big data solves ? and why ?
The main problems it addresses are scalability and com-plexity issues in a dramatic fashion because Big Data are aware of their distributed nature. And  sharding andreplication are handled for you, so you will never find acciden-tally query the wrong shard, because that logic is internalized in the database.

### Question 4:
#### How does data systems work?
Data systems are those that are in charge of storing and information. They also combine bits and pieces to produce their responses, which follows the following definition:

***query=function (all data)***

that means anything you could ever imagine doing with data can be expressed as a function thattakes in all the data you have as input

### Question5:
#### what are the 5 categories of open source project?

***1.-Batch computation systems***

***2.-Serialization frameworks***

***3.-Random-access NoSQL databases***

***4.-Messaging/queuing systems***

***5.-Realtime computation system***



# Chapter 2
### Question 6:
#### what is the relationship between data, views, and queries?
queries are those that access a list of views to find the answers to these, which in turn need as a next step access to a database where they can obtain the information they request or want.



