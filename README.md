# Zabbix-stack

I made this when I was working on standing up a Zabbix instance to monitor a few local servers of mine in my home lab.


It's pretty simple to stand up your own stack with this config as well.

- Open up port for 10051 for the Zabbix server.
- Edit the variables in .zabbix.env to your desire.
- Then simply do:

```bash
docker-compose up -d
```

And you should have a Zabbix stack up and running at http://localhost:7000. 

From here you can easily hook it up behind a reverse proxy with SSL.