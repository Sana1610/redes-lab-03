# Laboratorio 3 — Servicios DNS y NTP

Trabajo de **Juan Esteban Ortiz Pastrana** y **Santiago Alberto Naranjo Abril**, presentado en la Escuela Colombiana de Ingeniería Julio Garavito el 23 de septiembre de 2023.

## Descripción

El laboratorio estudia la configuración y administración de DNS y NTP. DNS permite relacionar nombres de dominio con direcciones IP, mientras que NTP mantiene sincronizados los relojes de los sistemas de una red.

## Temas abordados

- DNS, dominios de nivel superior, servidores raíz y DNS dinámico.
- Registros A, AAAA, NS, MX y CNAME.
- NTP, servidores de tiempo, relojes atómicos y estratos de referencia.
- Configuración de BIND en Solaris y Slackware.
- Archivos `named.conf`, `named.ca`, `named.soa`, archivos de hosts y `resolv.conf`.
- Verificación de resolución de nombres mediante `nslookup`.
- Configuración de NTP en sistemas Unix y Windows Server.
- Shells para copias incrementales, administración de procesos y búsqueda de archivos.

## Desarrollo

En Solaris se documenta la creación manual de carpetas y archivos de configuración de BIND. En Slackware se modifican los archivos generados por el servicio para definir dominios, servidores maestro y esclavo, direcciones IPv4 e IPv6 y alias.

## Conclusiones

DNS es fundamental para hacer accesibles los servicios mediante nombres de dominio. NTP permite mantener registros y eventos coherentes al sincronizar con precisión la fecha y la hora de los equipos.

> Este README fue elaborado exclusivamente a partir del informe `Laboratorio No 3.docx`.
