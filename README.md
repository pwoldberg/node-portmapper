# node-portmapper
Library that maps ports on NAT-enabled routers with the protocols UPnP-IGD and NAT-PMP

## TODO
- UPnP-IGD support
- NAT-PMP support
- auto renewal if lease expires
- unmap when process terminates
- listen to external ip changes
- what todo when there are multiple nat devices?
  - should probably only change the configured gateway
  - quit after first successful mapping or map port through all protocols?
