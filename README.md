# 

Given a (typically) long url, design a service that generates a shorter, unique alias for it? (e.g. tinyurl, bit.ly, google url shortener etc.). 

a) How you would generate a unique ID for each URL
b) How you would generate unique IDs at scale (8K+ requests per second)
c) How your service would handle redirects
d) How you would support custom short URLs
e) How you would delete expired URLs
f) How you would track click stats
g) Draw flowcharts diagrams, sequence diagrams, architecture diagram and deployment diagram for this service. *

Tech stack details:

* Node.js 
* Postgres as database
* Sequelize as ORM
* Redis for caching


