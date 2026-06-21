<div align="center">

# Direccionamiento Red LAN — VLSM

![Networking](https://img.shields.io/badge/Networking-LAN-0078D4?style=for-the-badge)
![VLSM](https://img.shields.io/badge/VLSM-Subnetting-2E86AB?style=for-the-badge)
![Cisco](https://img.shields.io/badge/Cisco-Packet%20Tracer-1BA0D7?style=for-the-badge&logo=cisco)

> Diseño y segmentación de red LAN con VLSM simulada en Cisco Packet Tracer.

## Descripción

</div>

---

Proyecto de diseño de infraestructura de red de área local aplicando **Variable Length Subnet Masking (VLSM)** para una segmentación eficiente del espacio de direccionamiento IPv4. Incluye tablas de subredes, plan de direccionamiento completo y simulación del esquema en **Cisco Packet Tracer**.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `*.pkt` | Topología de red en Cisco Packet Tracer |
| `Tablas.xlsx` | Plan de direccionamiento VLSM |
| `*.pdf` | Informe técnico con análisis de la segmentación |
| `*.docx` | Desarrollo detallado del laboratorio |

## Conceptos aplicados

- Subnetting con VLSM para optimización del espacio de direcciones
- Cálculo de rangos de host, broadcast y máscara por subred
- Topología lógica de red LAN con switches y routers
- Verificación de conectividad entre subredes

## Contexto académico

**Asignatura:** Redes de Computadores · **Institución:** Ingeniería Informática
**Autor:** Alejandro De Mendoza — Ingeniero Informático · Máster Arquitectura de Software

---

## Arquitectura

```mermaid
flowchart TD
    A[Requerimiento de red LAN] --> B[Calculo VLSM - Tablas.xlsx]
    B --> C{Subred}
    C --> D[Subred 1 - Rango hosts + Broadcast]
    C --> E[Subred 2 - Rango hosts + Broadcast]
    C --> F[Subred N - Rango hosts + Broadcast]
    D & E & F --> G[Diseno topologia logica - Switches y Routers]
    G --> H[Simulacion en Cisco Packet Tracer *.pkt]
    H --> I{Verificacion conectividad}
    I -- Fallo --> B
    I -- Exitosa --> J[Informe tecnico PDF + DOCX]
    J --> K[Red LAN operativa]
```

## Autor

**Alejandro De Mendoza**  
Ingeniero Informático · Especialista en IA · Especialista en Ingeniería de Software · Máster en Arquitectura de Software

[![GitHub](https://img.shields.io/badge/GitHub-AlejoTechEngineer-181717?style=for-the-badge&logo=github)](https://github.com/AlejoTechEngineer)
