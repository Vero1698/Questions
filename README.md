# Questions Chapter 1 and 2
### Question 1:
#### What can be a big problem when using a traditional database?
One of the problems may be the saturation of request to save data in the database directly because the database can't keep up withthe load, so write requests to increment pageviews are timing out.

### Question 2:
#### What is horizontal partitioning  or  sharding?
The sharing technique uses multiple database servers, which are seen as small subsets on different machines or servers that choose the shard for each key by taking thehash  of  the  key  modded  by  the  number  of  shards.

### Question 3:
#### What are the main problems that big data solves ? and why ?
The main problems it addresses are scalability and com-plexity issues in a dramatic fashion because Big Data are aware of their distributed nature. And  sharding andreplication are handled for you, so you will never find acciden-tally query the wrong shard, because that logic is internalized in the database.
