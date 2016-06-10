# RethinkDB Docker Cluster

### Requirements
* Docker Compose
* Docker (>1.9)

# Scaling Up

After startup you should see two servers (the "master" and the "slave" from the compose file).

![base](https://raw.githubusercontent.com/aweiland/rethinkdb-docker-cluster/master/img/base.png)


Try scaling up the "slave" instances

```bash
$ docker-compose scale rethink-slaves=4
```
Now there are more!
![scaled](https://raw.githubusercontent.com/aweiland/rethinkdb-docker-cluster/master/img/scaled.png)
