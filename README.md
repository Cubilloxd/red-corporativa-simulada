# Red Corporativa Simulada: Infraestructura Enterprise

## 1. Planteamiento del Problema / Caso de Negocio
Una empresa en crecimiento requiere migrar su red plana a una arquitectura segmentada y escalable. La infraestructura previa presentaba problemas de congestión por dominios de difusión extensos, falta de aislamiento entre departamentos y ausencia de redundancia en enlaces críticos.

## 2. Arquitectura y Topología
* **Niveles de red:** Core Layer, Distribution Layer y Access Layer.
* **Segmentación:** VLANs dedicadas para Administración, Contabilidad, TI, Ventas y Usuarios Invitados.
* **Redundancia:** Enlaces EtherChannel y protocolo Spanning Tree (RSTP).

## 3. Tecnologías y Herramientas Utilizadas
* **Simulación:** Cisco Packet Tracer
* **Protocolos:** Inter-VLAN Routing, OSPF, DHCP Snooping, Port Security, NAT/PAT.
* **Documentación:** Git, GitHub, Markdown.

## 4. Resultados e Impacto Medible
* **Seguridad:** Aislamiento total del tráfico sensible entre departamentos mediante listas de control de acceso (ACLs).
* **Rendimiento:** Reducción del tráfico de broadcast innecesario mediante segmentación por VLANs.
* **Disponibilidad:** Conmutación por error (failover) ante caída de enlaces principales.
