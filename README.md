# cis-docker-image

## Usage

```shell
[root@localhost cis2]# for i in cis-*; do echo -e "\033[31;1;4;5;7m$i\033[0m"; ./$i nginx; done
cis-4.1
Super user found ''
cis-4.4
  ➜ Analysis [48bdcb07d560] found 72 vulnerabilities.
  ➜ Analysis [5114afac2aa4] found 72 vulnerabilities.
  ➜ Analysis [5349a8fb01bf] found 38 vulnerabilities.
cis-4.6
HEALTHCHECK not found
cis-4.7
cis-4.8
cis-4.9
cis-5.12
Writes detected into directories:
/run /var/cache/nginx
```
