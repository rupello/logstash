Start logstash using named config file, with refresh
```
logstash -r -f ./plain.conf
```

Send some data to it...
```
echo test >> ./plaintext.log
```

JSON Example:
```
echo '{"foo":123, "bar":"baz"}' >> ./json.log
```
