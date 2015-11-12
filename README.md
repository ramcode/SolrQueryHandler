# SolrQueryHandler
#This project contains a standalone jar which converts solr query results to TREC format
#Instructions to run jar
1. download SolrQueryHandler.jar to your local machine and place queries.txt in the same folder as SolrQueryHandler.jar
2. start your koding VM (make sure your core is up and running)
3. run the following command at your command prompt java -jar SolrQueryHandler.jar {KodingURL} {IR_model_name} {query_file}

#A sample command should be like this:
java -jar SolrQueryHandler.jar http://xxxxxxxxx.yyyyyyyy.koding.io:8983/solr/mysolrcore BM-25 queries.txt
