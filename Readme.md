Start logstash using named config file, with refresh
```
logstash -r -f ./plain.conf
```

Send some data to it...
```
echo test >> ./plaintext.log
```
