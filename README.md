# Single /Vagrantfile to initialize multi VMs 
### Goal: Setup a LB nginx Server and test reverse Proxy with 2 Apache Servers at the backend, mariaDB as a DB Server

## Topology

* Loadbalancer 
  + hostname: lb01
  + Webserver: nginx
  + IP: 192.168.56.100
  
* Web Server1
  + hostname: web01
  + Webserver: apache
  + IP: 192.168.56.101
  
* Web Server2
  + hostname: web02
  + Webserver: apache
  + IP: 192.168.56.102
  
* DB Server
  + hostname: db01
  + Webserver: mariaDB
  + 192.168.56.101
  
* Environment:
 + Host: MacOS Sierra
 + Guest: 5.1.26
  
## Links & References

+ [Scott Keck-Warren](http://www.thisprogrammingthing.com/2015/multiple-vagrant-vms-in-one-vagrantfile/)
  
  
