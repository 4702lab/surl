# surl - url shortening service

Base url will be https://www.surlweb.com
url directions wil happen from http://lil.gl/<surl_key>  ex : lil.gl/aXdr4 

This project is developed based on REST using Python Flask framework and cassandra back end. 
The caching layer is powered by Redis Custer. 

Cassandra uses single DC 3 node cluster with LOCAL_QUORUM replication policy. 

Longer URLs will be shortened to 4-24 length keys and can be accessed through domain http://lil.gl 
