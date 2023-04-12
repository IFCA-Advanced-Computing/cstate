---
section: issue
title: "[Cloud] Failure launching new instances"
date: 2022-01-31T08:00:47.464Z
resolved: true


severity: down

resolvedWhen: 2022-02-14T11:00:20.523Z
affected:
  - OpenStack Cloud Public APIs
  - OpenStack Networking (Neutron)
  - OpenStack Compute (nova)
  - OpenStack Compute Nodes


---
Since the last upgrade of the version of some components of OpenStack, it fails on launching new instances randomly with error:

Build of instance d47XXXXX aborted: Failed to allocate the network(s), not rescheduling.

We are monitoring the system and trying to resolve it ASAP.