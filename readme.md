# SkeletonES

## Short description
A Skeleton project for Django to communicate with Elasticsearch

## Configuration
To configure ElasticSearch you need to drop config file (*config.ini*) to **/SkeletonES** directory with following structure:
```
SECRET_KEY:re@z!$1h^_=e-f(jp@ib*s5+ye3z5_$k6mbbo$0%$-d)gkfgto
ES_HOSTS:http://localhost:9200/
ES_USER:
ES_PASSWORD:
ES_INDEX:my-index
ALLOWED_HOSTS:*
```

Also you are able to place the config file wherever you wish indicating the filepath in settings.py under
**_config_path_** variable

## Requirements
```
Django==2.2.6
elasticsearch==7.0.5
pytz==2019.2
sqlparse==0.3.0
urllib3==1.25.6
```