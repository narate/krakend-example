# KrakenD Example

See more https://i.dont.works/basic-krakend-api-gateway/

# TL; DR

```
$ docker-compose up -d

$ http://127.0.0.1/

$ http://127.0.0.1/ip

$ http://127.0.0.1/aggs
```


# Check confilg

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
