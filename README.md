# cronjob

```
$ docker image build -t example/cronjob:latest .
$ docker container run -d --rm --name cronjob example/cronjob:latest
$ docker container exec -it cronjob tail -f /var/log/cron.log
```
