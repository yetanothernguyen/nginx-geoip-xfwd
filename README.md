# nginx-geoip-xfwd
Add an option to force the usage of an address from the “X-Forwarded-For” request header field as the client IP

```
Syntax: geoip_force_x_forwarded_for on | off;
Default: geoip_force_x_forwarded_for off;
Context:  http
```

If multiple IP addresses are in x-forwarded-for, the last one is used.
