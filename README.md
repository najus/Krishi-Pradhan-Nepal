# Krishi-Pradhan-Nepal
Nepal agricultural data analysis using Solr and Banana

Data from: https://github.com/opennepal/odp-agriculture/tree/master/Commodies%20production%20in%20Nepal

Start Solr server: bin/solr start

Create Solr collection: bin/solr create -c krishi // create schemaless solr collection

Post data to the Sor collection: bin/post -c krishi example.csv //post data to the collection
