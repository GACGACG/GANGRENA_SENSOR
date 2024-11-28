# GANGRENA_SENSOR
Repositorio dedicado al proyecto de ataque a redes de sensores por la banda Gangrena. 
-----------------------------------------------------------------------------------
El código rpl-attacks makefile al ejecutar dentro del entorno del Framework RPL-Attack nos ofrece tres carpetas:
- blackhole-attack
- hello-flood-attack
- version-number-attack

Nota: En este proyecto se hizo implementación y uso de los ataques Blackhole y FloodAttack. Aún así se deja en consideración en el repositorio la carpeta version-numer-attack que contiene otro tipo de ataque el cual no se ocupó en el proyecto
------------------------------------------------------------------------------------
Se debe considerar el uso de Redes de Sensores en el ambiente de contiki.ng, por lo que, para realizar estos ataques primero se deberá considerar la instalación previa del simulador.
Los archivos que se deben usar para Blackhole attack en el entorno de contiki-ng son:
- maliciuos.z1 (blackhole-attack/with-malicious/motes/)
- sensor.z1 (blackhole-attack/with-malicious/motes/)

Para realizar FloodingAttack se debe hacer uso de los siguientes archivos en el simulador:
- maliciuos.z1 (hello-flood-attack/with-malicious/motes/)
- sensor.z1 (hello-flood-attack/with-malicious/motes/)

------------------------------------------------------------------------------------
Luego de insertar estas herramientas se puede proceder a realizar la simulación según las variables de entorno deseadas, para luego obtener resultados.


