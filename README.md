# What can I find here?

As you can see, this is a fork of <a href="https://github.com/PacktPublishing/Data-Engineering-with-Python">this repository</a>, the code repository for [Data Engineering with Python](https://www.packtpub.com/product/data-engineering-with-python/9781839214189?utm_source=github&utm_medium=repository&utm_campaign=9781839214189), published by Packt.

One of the first chapters in the book covers how to set up your work environment to follow the rest of the book, code along as you do so and to perhaps try some things for yourself. 

Here you can find a docker-compose.yaml to set up the entire environment as described in the book but in Docker containers. This saves you the hassle of doing everything yourself.

I generally liked reading the book and it has certainly helped me, but without mentioning it anywhere it implicitly assumes that you are working on a Debian based Unix system. That's the only setting in which the instructions on setting up the environment work.

Even if I personally work with such an environment, it still took me some time to do everything as described in the book. And indeed I ended up with a working environment (after googling around in some cases, since some information in the book is outdated and this caused some errors).

Since I wanted to get a better understanding of Docker as well after reading the book, I found this to be a rewarding excercise.

## This is what you will set up
| Software | Used for | Accessible via | Credentials |
| --- | --- | --- | --- |
| NiFi | Data processing | http://localhost:9090/nifi/ | |
| NiFi Registry | NiFi version control | http://localhost:19090/nifi-registry/ | |
| Airflow (Webserver, Scheduler)| Data processing | http://localhost:8080/login/ (Web UI) | airflow/airflow |
| Postgres database| Database (relational) |  | airflow/airflow |
| pgAdmin 4 | http://localhost:8081/browser/ | Database UI | admin@admin.com/admin |
| Elasticsearch cluster (3 instances) | Database (noSQL) | http://localhost:9200/_cat/nodes?v=true&pretty (check if they are running) | |
| Kibana | Data Visualization | http://localhost:5601/ | |

## Don't miss these critical steps

*
*
*
tbd

---

For more content on data engineering and related projects, visit <a href=http://www.dominikschauer.com>http://www.dominikschauer.com</a>.
