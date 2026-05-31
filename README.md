# 🌐 Mi Primer Proyecto en Cisco Packet Tracer

¡Bienvenido/a a mi primer proyecto de simulación de redes! Este diseño representa mis primeros pasos en el mundo del networking, modelando una infraestructura de red funcional desde cero utilizando **Cisco Packet Tracer**.

## 🚀 Descripción del Proyecto

El objetivo de este proyecto fue diseñar e implementar una topología de red básica pero funcional para [mencionar el propósito, ej: una pequeña oficina / una red del hogar / un laboratorio de estudio]. 

A través de esta simulación, logré interconectar diferentes dispositivos finales, aplicar direccionamiento IP y asegurar la comunicación interna mediante el uso de routers y switches.

---

## 🛠️ Tecnologías y Herramientas Utilizadas

* **Software de Simulación:** Cisco Packet Tracer (Versión [ej: 8.2])
* **Dispositivos de Red:** Routers Cisco [ej: 2911], Switches Cisco [ej: 2960].
* **Dispositivos Finales:** PCs, Laptops [ej: y Servidores].
* **Medios de Transmisión:** Cable directo de cobre (Copper Straight-Through) [ej: y cable cruzado].

---

## 📐 Topología de la Red

La red está estructurada bajo una topología en [ej: Estrella / Árbol / Mixta] y cuenta con las siguientes características:

* **Subredes:** Se configuraron [número, ej: 2] subredes distintas para segmentar el tráfico.
* **Direccionamiento:** Se utilizó direccionamiento IPv4 [ej: Estático / mediante DHCP].

### Tabla de Direccionamiento (Ejemplo)

| Dispositivo | Interfaz | Dirección IP | Máscara de Subred | Gateway por Defecto |
| :--- | :--- | :--- | :--- | :--- |
| **Router0** | Gig0/0 | 192.168.1.1 | 255.255.255.0 | N/A |
| **PC-01** | FastEth0 | 192.168.1.2 | 255.255.255.0 | 192.168.1.1 |
| **PC-02** | FastEth0 | 192.168.1.3 | 255.255.255.0 | 192.168.1.1 |

---



## 🧠 Aprendizajes Clave

Con este proyecto logré comprender de forma práctica:
* La diferencia y el propósito de los Routers (Capa 3) y Switches (Capa 2).
* Cómo estructurar y asignar un esquema de direccionamiento IP básico.
* El flujo de encapsulamiento de datos al enviar un paquete de una PC a otra.

---

Este proyecto marca el inicio de mi camino en la ingeniería de redes. ¡Cualquier feedback es más que bienvenido! 🚀
