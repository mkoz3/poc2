# poc2
Docker POC

## addresses

| component | address |
| ---       | --- |
|static     | `http://ADDRESS:9000/` |
|ui         | `http://ADDRESS:9000/ui` |
|stats      | `http://ADDRESS:9000/stats` | 
|portainer  | `http://ADDRESS:9000/portainer` |

## logins

Login for stats and portainer: admin/password

## notes

* *haproxy/haproxy.cfg*  
  haproxy config file
* *proxy/nginx.conf*  
  nginx proxy config file
* *static/pom.xml* / *ui/pom.xml*  
  pom.xml for creating docker images directly in maven
