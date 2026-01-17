---
title: "contact_protocol"
date: 2025-11-22T13:00:00+01:00
---

## Initiating Handshake

```bash
guest@internet:~$ ping ackvarmland.se
PING ackvarmland.se (127.0.0.1): 56 data bytes
64 bytes from server: icmp_seq=0 ttl=64 time=2.3 ms
64 bytes from server: icmp_seq=1 ttl=64 time=2.4 ms

--- ackvarmland.se ping statistics ---
2 packets transmitted, 2 packets received, 0.0% packet loss

guest@internet:~$ ./contact_me
> Email:    jonas@ackvarmland.se  [SEND_MAIL]
> LinkedIn: in/jonsson-jonas/      [CONNECT]
> Location: Stockholm, Sweden       [LOCATE]
> Origin:   Värmland, Sweden        [ORIGIN]
guest@internet:~$ _
