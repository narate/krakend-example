# KrakenD Example

See more https://i.dont.works/basic-krakend-api-gateway/

# TL; DR

```
$ docker-compose up -d

$ curl http://127.0.0.1/

$ curl http://127.0.0.1/ip

$ curl http://127.0.0.1/aggs
```


# Check config file

```
$ docker-compose up check
Starting krakend_check_1 ... done
Attaching to krakend_check_1
check_1     | Parsing configuration file: krakend.yml
check_1     | Syntax OK!
krakend_check_1 exited with code 0
```

# Start Designer

```
docker-compose up -d designer
```

# Start KrakenD

```
docker-compose up -d krakend
```
