---
section: issue
title: "[HPC users] Change in the Slurm authentication mechanism"
date: 2026-04-28T13:19:10.691Z
resolved: false
draft: false
informational: false
pin: true
resolvedWhen: 2026-04-27T13:19:10.700Z
affected:
  - Batch System
  - Computing Elements
severity: disrupted
---
In the coming days, maintenance will be carried out on Slurm authentication, and job submission will not be possible during the change. An exact date and time have not yet been scheduled, since the compute nodes first need to be drained to clear running jobs and make the intervention as light as possible.

Update \[30 abr 12.30 pm]

Slurm is updated to support the new native slurm authentication. The change was applied to some group machines, and it works except from wngpus. The rest of the machines needs to apply it in the next hour when puppet runs.