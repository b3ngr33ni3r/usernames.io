[usernames.io](http://usernames.io)
==============

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)

quickly generate usernames

# API

## /new

Requets a new username, and it's availability info.

```
{
    "username": "",
    "availability": {
        "github": true,
        "linkedin": true,
        "dot-com": true,
        "facebook": true,
        "twitter": true
    }
}
```

## /availability/:service?username=<username>

Requests availability for a specific service and a given username.

```
{
    "service": true
}
```

# License

MIT