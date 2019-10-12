ColorLaunch.net Config/Setup
===========================

Status:
-------

Working but probably not in its final form. 

Usage:
------

```
# initial setup of a lightsail ubuntu 18.04 instance
$ ansible-playbook -i your-host-file dev.colorlaunch.net.yml 

# install and configure mosquitto (MQTT broker)
$ ansible-playbook -i your-host-file mosquitto.yml

# update static files and application code from the repo
$ ansible-playbook -i your-host-file application.yml --tags=app
```

