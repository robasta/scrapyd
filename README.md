# scrapyd
Based on: https://github.com/vimagick/dockerfiles/tree/master/scrapyd

I added the following packages:
- bsddb3 & sqlitedict - for 'CrawlOnce' functionality
- pika - for writing items to a RabbitMQ (https://github.com/robasta/rabbitmq-pipeline)
- python-dateutil - for parsing string dates
