Herding ELK - Scaling ELK Towards A Trillion Documents On Disk
----

A practical walkthrough of scaling ELK (Elasticsearch/Logstash/Kibana) at Fitbit Inc, from 7 days of retention at 45,000 documents a second to 30 days of retention at 200,000 documents a second and growing. The current cluster peaks at 335,000 logs per second, which at a 30 day retention is over 800 billion documents on disk. During the scaling process, various bottlenecks were encountered and had to be overcome.

These are the slides and notes from the Surge 2016 conference talk.
