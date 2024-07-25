---
section: issue
title: "[CLOUD] Upgrade Compute and Network OpenStack services"
date: 2024-07-23T06:30:51.777Z
resolved: false
draft: false
informational: false
pin: true
resolvedWhen: 2024-07-17T12:17:51.787Z
affected:
  - OpenStack Compute (nova)
  - OpenStack Cloud Public APIs
severity: notice
---
An upgrade in the OpenStack Cloud Computing services will be scheduled at 23 July until the services will be updated.

\[Update July 23 - 15:00]

Neutron and nova controllers are migrated to Ubuntu 20 and OpenStack Victoria.  Worker nodes are still missing.

\[Update July 24- 18:00] 

Some issues with network and compute controller communication made that new instance launching was failing. Now, nova (compute) and network (neutron) services are working. The storage service is still failing.

\[Update July 25 -11am]

Problems with the cinder setup are solved. The services are stable now but some features are still missing (e.g. instance console access)