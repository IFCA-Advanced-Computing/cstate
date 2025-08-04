---
section: issue
title: "[HPC and Grid] Slurm upgrade "
date: 2025-07-29T07:00:33.111Z
resolved: false
draft: false
informational: false
pin: true
resolvedWhen: 2025-07-30T12:00:33.146Z
affected:
  - Batch System
  - Computing Elements
severity: disrupted
---
**\[Update 1 Aug 9am]**

\[English version below]

Estimados/as usuarios/as,

La pasada semana se procedió a actualizar Slurm a la última versión estable y no vulnerable.

Esta actualización nos ha conyevado a más cambios de los previstos inicialmente y estamos terminando algún otro:

* Se han eliminado los nodos que teníamos en centos7, que se encuentra fuera de mantenimiento hace tiempo.
* Todos los nuevos nodos están actualizados con Alma Linux 9.
* Reestructuración de particiones de compute y res con los nuevos nodos en AL9
* Eliminación del nodo antiguo de login1 en CentOS 7, estamos trabajando para que el nuevo login1 con AL9 funcione dentro de nada

Les seguimos manteniendo informados de la actuación en nuestra página de status \[1].

Para cualquier duda o información, no dude en contactarnos en \[2].

Disculpen las molestias

Un saludo

IFCA Advanced Computing Service Team

- - -

\[English version]

Dear users,

Last week we proceeded to update Slurm to the latest stable and non-vulnerable version.

This update has led us to more changes than initially planned and we are finishing some others:

* The nodes we had on centos7, which has been out of maintenance for some time, have been removed.
* All new nodes are upgraded to Alma Linux 9.
* Restructuring of compute and res partitions with the new nodes in AL9.
* Removal of the old login1 node in CentOS 7, we are working to get the new login1 with AL9 up and running in no time.

We continue to keep you informed of the performance on our status page \[1].

For any questions or information, please feel free to contact us at \[2].

Sorry for the inconvenience

Best regards

IFCA Advanced Computing Service Team

**\[Update 1 Aug 9am]**

Slurm controllers are failing. Altamira nodes were removed that cause some issues when slurmctld has to get up. 

**\[Update 30 July 4pm]**

Grid and HPC nodes are already upgraded to slurm 25.05 except altamira nodes. In the following days we will include new nodes to Altamira partition to replace old altamira nodes that are not compatible with the new version of slurm.

**\[Update 30 July 9am]**

The last version of slurm (25.05) is already installed in the controllers and HPC nodes. Grid is missing but will be operative throughout the morning. There were a delay in the upgrade due to an issue in the WN. 

\----------------------------------------------------------------------

El **próximo martes 29 de Julio se procederá a la actualización del sistema de colas slurm del clúster de HPC**. Esto es una medida que llevamos semanas posponiendo pero que debemos realizar aprovechando el periodo estival y que hay una menor actividad. Esta actualización es necesaria debido a una vulnerabilidad de seguridad en la versión actual. 

La intervención está planificada para la mañana del martes donde todos los nodos de cómputo estarán apagados. También, para asegurar que los trabajos actuales terminan su ejecución correctamente se procederá a drenar todos los nodos  **hoy, 24 de julio** (mañana y el lunes es fiesta en Santander). En principio, la intervención no debería durar más de la mañana del martes.

\------------------------------------------------------------------

Dear user,

**Next Tuesday, July 29, the Slurm queueing system of the HPC cluster will be updated.** This is a maintenance operation we have postponed for several weeks, but it must now be carried out, taking advantage of the summer period when system activity is lower. This update is necessary due to a security vulnerability present in the current version.

The intervention is scheduled for Tuesday morning, during which all compute nodes will be powered off. In order to ensure that currently running jobs complete properly, all nodes will be drained **today, July 24** (since tomorrow and Monday are public holidays in Santander).  The procedure should not take longer than Tuesday morning.