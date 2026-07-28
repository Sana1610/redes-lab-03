# Laboratorio 3 — Servicios DNS y NTP

**Autores:** Juan Esteban Ortiz Pastrana y Santiago Alberto Naranjo Abril  
**Institución:** Escuela Colombiana de Ingeniería Julio Garavito  
**Grupo:** 2  
**Fecha:** 23 de septiembre de 2023

## Introducción

El laboratorio se enfoca en dos servicios esenciales de infraestructura: **DNS**, encargado de relacionar nombres de dominio con direcciones IP, y **NTP**, utilizado para mantener sincronizadas la fecha y la hora de los equipos.

## Marco teórico

### DNS

Se estudian los dominios de nivel superior, los servidores raíz, el DNS dinámico y los registros:

- **A:** relaciona un dominio con una dirección IPv4.
- **AAAA:** relaciona un dominio con una dirección IPv6.
- **NS:** identifica los servidores responsables de una zona.
- **MX:** define los servidores de correo.
- **CNAME:** permite crear alias para otros nombres.

### NTP

NTP sincroniza relojes mediante clientes y servidores distribuidos. El informe revisa los relojes atómicos, los estratos de referencia y la importancia de mantener una base temporal coherente para procesos, registros y eventos.

## Configuración de DNS

### Solaris

Se verifica la instalación de BIND y se crean manualmente los directorios y archivos requeridos. La configuración incluye `named.conf`, `named.ca`, `named.soa` y `resolv.conf`, con direcciones IPv4, IPv6, dominios y alias.

### Slackware

Los archivos iniciales son generados por el servicio y posteriormente modificados para definir el dominio maestro, un posible servidor esclavo, servidores raíz, hosts y resolución local. El funcionamiento se comprueba mediante `nslookup`.

## Configuración de NTP

Se documenta la configuración de servidores y clientes NTP en sistemas Unix y Windows Server para mantener una referencia horaria común.

## Shells

El informe describe scripts para:

- Realizar copias de seguridad incrementales.
- Listar, buscar, finalizar o reiniciar procesos.
- Buscar archivos por extensión y abrirlos con un visor de texto.

## Conclusiones

El informe concluye que DNS es fundamental para la infraestructura de red porque traduce alias de dominio en direcciones IP y hace más accesibles los servicios. NTP aporta trazabilidad al sincronizar la fecha y la hora, manteniendo la coherencia e integridad de registros, eventos y transacciones.

## Contenido del repositorio

- Informe completo en DOCX y PDF.
- Video de la práctica.
