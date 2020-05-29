Query Stackoverflow dataset from StackExchange
  1. Go to https://data.stackexchange.com/
  2. Compose Query
  3. Write query statement:
    select top 10000 id, title, body, creationdate, score, owneruserid
    from posts
    where posttypeid = 1
    order by id;
 Link: https://meta.stackexchange.com/questions/2677/database-schema-documentation-for-the-public-data-dump-and-sede
