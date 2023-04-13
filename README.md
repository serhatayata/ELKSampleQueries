# ElasticSearch_UdemyLesson
Complete Guide to Elasticsearch Udemy Course queries

All notes and queries (udemy.com/course/elasticsearch-complete-guide/)

- BULK Insert : 

   - curl -H "Content-Type: application/json" -XPOST "http://localhost:9200/recipes/_bulk?pretty" --data-binary "@recipes-bulk.json" -u elastic
