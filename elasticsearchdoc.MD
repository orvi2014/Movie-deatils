*** Elasticsearch can be started and stopped using the service command: ***
```
// start the Elasticsearch service
`sudo -i service elasticsearch start`
// stop the Elasticsearch service
`sudo -i service elasticsearch stop`
```

*** To configure Elasticsearch to start automatically when the system boots up, run: ***
```
//reload the systemctl daemon
sudo /bin/systemctl daemon-reload`
// enable elastic search so it can be called as a service
sudo /bin/systemctl enable elasticsearch.service
```

*** After running the command above, you can start and stop Elasticsearch by running: ***

```
// start the Elasticsearch service
sudo systemctl start elasticsearch.service
// stop the Elasticsearch service
sudo systemctl stop elasticsearch.service
```

*** To check the status of Elasticsearch: ***
```
// check status of Elasticsearch
sudo service elasticsearch status
```