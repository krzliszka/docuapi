---
weight: 10
title: API Reference
---

# Admin applications

## certificate_issuer

Container responsible for issuing certificates. Required in cloud systems

### image

<aside class="success">
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</aside>

### infrastructure_image

<aside class="warning">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur</aside>

### timestamp

> Example:

```json
{
  "image": "image"
}
```


# Services

## logs

> Example:

```json
{
    "logs": {
        "timestamp": 123.45,
        "password": "cGFzc3dvcmQK",
        "collect_containers_logs_regex": ".*",
        "remove_rotated_logs": {
            "host": false,
            "containers": false
        },
        "collect_host_logs": true,
        "execution": {
            "type": "oneshot",
            "exit_timeout": 1200
        }
    }
}
```

Logs collection configuration

Field | Type   | Default | Description
--------- |---------|---------| -----------
password | string  | -       | Base64 encoded password
collect_host_logs | boolean | -       | Should logs from host be collected

## ntp

> Example:

```json
{
  "ntp": {
    "servers": [
      "1.2.3.9",
      "6.5.3.33"
    ]
  }
}
```

NTP configuration. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum
