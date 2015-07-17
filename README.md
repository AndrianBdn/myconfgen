# MySQL /etc/my.cnf generator

## Description

A python2 script that outputs MySQL my.cnf config which is based on some known good practices (tools.percona.com Configuration Wizard,
percona.com/blog, some existing MySQL configs) and mostly amount of RAM allocated for MySQL. 

## Usage

Run as

```
./myconfgen.py mysql_ram_gb=1 > /etc/my.cnf
```

mysql_ram_gb parameter is specified in gigabytes.


## Your input

Please feel free to open pull request with your configuration suggestions.

## Tried On

This has been tried on CentOS 7 using Percona Server 5.6. Potentially it could work with other MySQL flavors and probably with other Linux distributions.
