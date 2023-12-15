---
section: issue
title: Mantenimiento de transformador de edificio / Building transformer maintenance
date: 2023-11-22T17:18:14.655Z
resolved: true
draft: false
informational: false
pin: true
resolvedWhen: 2023-11-27T07:30:00.000Z
affected:
  - Batch System
  - User Interfaces
  - Computing Elements
  - Indico Agenda pages
  - Wordpress pages
  - OpenStack Compute Nodes
severity: disrupted
---
\[Update: 29 nov. 12am]

* HPC Altamira is operative again.
* Working in making HTC operative.

\[Update: 28 nov. 11am]

* Some issues with HPC to make new slurm nodes available with the new gpfs storage. 
* HTC is down yet. 
* Cloud is operative and the virtual machines are up. Btw, some machines were in ERROR state or do not boot properly. They will be reviewed during today. 
* New Cloud and HPC physical machines are installed but not up. 

\[English version below]\
\
\
Estimados/as usuarios/as,\
\
Por motivos de mantenimiento del transformador de edificio, el día 27 de noviembre de 2023, se realizará un corte de corriente general en el edificio.\
\
Después de la instalación del grupo electrógeno, el corte afectará a los nodos de computo durante unos minutos, que se reiniciarán automáticamente cuando empiece a funcionar.\
\
Aprovechando el corte, vamos a realizar algún que otro cambio necesario, esto conllevará un apagado de algún servicio durante más tiempo:\
\

* Cloud: Tiempo previsto de corte una hora.\
  \
* HPC y Grid: El tiempo previsto para esta actuación será mayor, ya que tenemos un número mayor de actuaciones:\
  \
      - Poner en funcionamiento el nuevo almacenamiento GPFS.\
      - Realizar cambios en el controlador de gestión de colas "slurm".\
      - Montaje de nuevo equipamiento HPC y Grid.\
      - Las colas de slurm se cerrarán el viernes

\
Todo el proceso lo podrán seguir a través de nuestra página de status \[1]\
\
Si tiene alguna pregunta, no dude en contactarnos en \[2]\
\
Nota: Como usuario de los servicio de computación avanzada del IFCA, si tiene conocimiento de algún problema de seguridad o incidente, tiene la obligación de contáctenos lo antes posible en \[3]\
\
Un saludo\
\
IFCA Advanced Computing Team\
\
\
--- --- ---\
\
\[English version]\
\
\
Dear users,\
\
Due to maintenance of the building transformer, on November 27, 2023, there will be a general power outage in the building.\
\
After the installation of the generator set, the outage will affect the computer nodes for a few minutes, which will be automatically restarted when it starts working.\
\
Taking advantage of the outage, we are going to make some other necessary changes, this will lead to a shutdown of some services for a longer period of time:\
\

* Cloud: Expected outage time one hour.\
  \
* HPC and Grid: The expected time for this action will be longer, since we have a greater number of actions:\
  \
      - Get the new GPFS storage up and running.\
      - Make changes in the queue management controller "slurm".\
      - Installation of new HPC and Grid equipment.\
      - Slurm queues will be closed on Friday.\
  \
  You can follow the whole process through our status page \[1].\
  \
  If you have any questions, please do not hesitate to contact us at \[2].\
  \
  Note: As a user of IFCA's advanced computing services, if you are aware of any security problem or incident, you have the obligation to contact us as soon as possible at \[3].\
  \
  Best regards\
  \
  IFCA Advanced Computing Team\
  \
  \
  --- --- ---\
  \
  \
  \[1] <https://status.ifca.es>

\
\[2] computing.support@ifca.unican.es\
\
\[3] security.support@ifca.unican.es\
\
\[4] <https://computing.ifca.es>