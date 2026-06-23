# Archivos de Práctica Redes CCNA

Este repositorio contiene una colección de laboratorios y escenarios prácticos diseñados para consolidar los conocimientos requeridos en la certificación **Cisco CCNA**. Las prácticas están desarrolladas principalmente en archivos de Packet Tracer (`.pkt`) y cubren temas esenciales de enrutamiento, seguridad, traducción de direcciones y servicios de red.

## Estructura del Repositorio

Los archivos están organizados por categorías según el protocolo o servicio implementado:

### Listas de Control de Acceso (ACL)
Configuraciones orientadas al filtrado de tráfico y la seguridad perimetral.
* **ACL1 estandar - ANGEL RODRIGO GUTIERREZ PEDROZA**: Implementación básica de ACLs estándar basadas únicamente en la dirección IP de origen.
* **ACL2 estandar - ANGEL RODRIGO GUTIERREZ PEDROZA**: Ejercicio avanzado de control de tráfico mediante ACLs estándar.
* **ACL2 extendida- ANGEL RODRIGO GUTIERREZ PEDROZA**: Configuración de ACLs extendidas para filtrar tráfico específico por IP de origen, destino, protocolo y puerto.
* **ACL3 ICMP - ANGEL RODRIGO GUTIERREZ PEDROZA**: Restricciones de tráfico enfocadas en el protocolo ICMP (bloqueo/permiso de Ping y mensajes de diagnóstico).

### Network Address Translation (NAT)
Laboratorios enfocados en la traducción de direcciones para la conectividad hacia redes públicas.
* **NAT1 - ARGP.pkt**: Configuración inicial y conceptos básicos de NAT (Estático/Dinámico).
* **NAT2 - ARGP.pkt**: Escenario intermedio de traducción de direcciones de red.
* **NAT3_sobrecarga - ARGP.pkt**: Implementación de NAT con sobrecarga (PAT - Port Address Translation) para optimizar el uso de IPs públicas compartidas.

### Acceso Remoto y Seguridad
* **Simulacion_Telnet_SSH.pkt**: Configuración de líneas VTY para acceso remoto seguro empleando SSH, y comparativa frente a la inseguridad del protocolo Telnet.
* **vpn_sitio_a_sitio_ARGP.pkt**: Creación de un túnel VPN de sitio a sitio (Site-to-Site) para la interconexión segura de redes remotas.

### Transición y Conectividad IPv6
* **tunel_ipv6ip_ARGP.pkt**: Configuración de mecanismos de transición, específicamente tunelización IPv6 sobre IPv4 (6in4 o similar), para permitir el tráfico IPv6 a través de una infraestructura IPv4.

### Configuración General
* **Practica1_conf.pkt**: Laboratorio integral de topología base, direccionamiento y enrutamiento esencial.

---

## Requisitos

Para poder abrir y simular los laboratorios contenidos en este repositorio, es necesario contar con:
* **Cisco Packet Tracer** (se recomienda la versión más reciente para evitar problemas de compatibilidad con los archivos `.pkt`).

---

## Autor

* **Angel Rodrigo Gutierrez Pedroza**

Residente de Ingeniería en Sistemas Computacionales
