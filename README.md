# home-server-service

docker-compose for home services


## Usage


```bash

docker-compose up -d

```


##  troubleshooting

- If pihole was active before, ensure nameserver is set in /etc/resolv.conf
 ```bash
 sudo vi /etc/resolv.conf

    nameserver 127.0.0.1
    nameserver 1.1.1.1

 ```
- ensure pi-hole container has internet access to run setup scripts

- ensure /sys is mounted and shareable for Beszel battery monitoring
