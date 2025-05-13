---
section: issue
title: Cloud upgrade
date: 2025-04-14T07:31:17.705Z
resolved: false
draft: false
informational: false
pin: false
resolvedWhen: 2025-04-14T07:31:17.713Z
affected:
  - OpenStack Cloud Public APIs
  - OpenStack Compute (nova)
  - OpenStack Networking (Neutron)
severity: disrupted
---
Se va a proceder a actualizar cloud a una nueva versión, esto podrá tener algún corte de servicio momentaneo.

Disculpen las molestias

\-﻿-- --- ---

We will proceed to update cloud to a new version, this may have some momentary service outage.

Sorry for the inconvenience

\[Update 05-13]

One of the upcoming tasks involves upgrading the operating systems of all machines in the cloud ecosystem — including the core compute, network, and storage services (most of which have already been updated), as well as the nodes hosting the instances. This step is necessary because the operating system currently in use will reach its end of standard support this month \[1].

\[1] <https://ubuntu.com/blog/ubuntu-20-04-lts-end-of-life-standard-support-is-coming-to-an-end-heres-how-to-prepare>

This upgrade process will begin **tomorrow, Wednesday, May 14**, and will involve a downtime of approximately 1 to 1.5 hours per instance-hosting machine.

If any of you have a justified need to postpone the upgrade for a few days, please let us know at **[computing.support@ifca.unican.es](<>)**, and we will schedule the upgrade of those specific machines for the end of the process. We apologize for the short notice.

\[Update 05-09 15pm] 

After the investigatin, we got to make the network metadata service working. You can launch an instance and access it without any problem. 

\[Update 05-08 10:00 am]

Second upgrade of the main controllers is done. The Operating system update of the nodes is missing, it is scheduled for the following weeks grou by group. 

**A problem in the metadata service of the network or the compute components makes that the launching or rebooting of the instances is not working well. We are investigating the reason of the issue.** 

\[Update 04-25 13:30 pm]

After the first upgrade of all the Openstack services and some problems with cinder and nova, everything should be stabilized. If you see some issue, do not hesitate to send us a ticket to take a look if something is misconfigured. 

We wil continue with the next update that hopefully, would be lasted until next week.