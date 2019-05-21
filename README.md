# Crawler

Create script that, for a given website, generates a graph in Neo4j of
all (or a reasonable amount of) subpages and their connections. Each
node should contain the URI, title, summary of content (extracted from
h\* tags, title, etc.).

# Before

1. Download and run Neo4J (version 3.5.5 is recommended).
2. Add client and password named "ads"
3. Remember to store localhost port in case it is different than 7687

For development, the best way is to install jupyter notebook and use it to run project.
Then the results should be visible after opening http://localhost:7474 
