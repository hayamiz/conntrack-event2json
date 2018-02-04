# natlogger-fluent

Tracks TCP/UDP NAT connections with conntrack(1) and saves log to fluentd.

## Execute as a daemon

Copy `natlogger-fluent.service.example` to `/etc/systemd/system/natlogger-fluent.service`
and update its content to match your environment.

