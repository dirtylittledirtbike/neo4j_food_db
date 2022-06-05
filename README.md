# using neo4j to create graphical databases of recipes from multiple online sources.
## setup (locally with neo4j desktop)
* download repository
* create new project in Neo4j Desktop app
* add a DBMS
* once you create a Graph DBMS go to the three dots to the right of the start button and then navigate the dropdown to "Open folder" -> "import". Then add the downloaded files from neo4j_food_db/food_data_neo/ to the import folder that neo4j opened in finder/file explorer.
* start graph DBMS and then select "Open" once finished. 
* run queries from neo4j_food_db/cypher_queries/cypher_setup.txt to create nodes and connections from each data source
* play around! checkout neo4j_food_db/cypher_queries/fun_cypher_queries.txt for some example queries. 


### original inspiration and data source: http://blog.bruggen.com/2013/12/fascinating-food-networks-in-neo4j.html?m=1 
