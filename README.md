# MySQL /etc/my.cnf generator 

## Description

A python2 script that outputs MySQL my.cnf config which is based on some known good practices (tools.percona.com Gonfiguration Wizard, 
percona.com/blog, some existng MySQL configs) and mostly amount of RAM. 

## Usage 

Run as 

```
./myconfgen.py mysql_ram_gb=1 > /etc/my.cnf 
```

mysql_ram_gb parameter is specified in gigabytes. 

## Test Result 

This has been tried on CentOS 7 using Percona Server 5.6. Potentially it could work with other MySQL flawors and probably with other Linux distributions. 

