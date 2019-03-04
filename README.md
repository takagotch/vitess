### vitess
---
https://github.com/vitessio/vitess

```
set workload='olap'
```

```
-mysql_server_port $mysql_server_port \
-mysql_server_socket_path $mysql_server_socket_path \
-mysql_auth_server_static_file "./mysql_auth_server_static_creds.json" \

mysql -h 127.0.0.1 -P 15306 -u mysql_user --password=mysql_password

sudo service apparmor stop
sudo server apparmor teardown
sudo update-rc.d -f apparmor remove
```

```
```


