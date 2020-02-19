# es-kibana-maraidb
es kibana mariadb and phpmyadmin

###Get IP
```text
ip="$(ifconfig | grep -A 1 'wifi0' | tail -1 | cut -d ' ' -f 10)"
```