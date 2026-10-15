# Arquitectura de Software - Proyecto MIMETIC

Bienvenido a la documentación viva de arquitectura para **MIMETIC** (*Sistema de apoyo a la gestión de recursos médicos mediante Inteligencia Artificial y Gemelos Digitales*).

Este directorio contiene los **Registros de Decisiones de Arquitectura (ADRs)** y los **Diagramas como Código (PlantUML)** que guían el diseño, desarrollo y evolución técnica de la plataforma.

---

## 1. Estructura del Repositorio de Arquitectura

La documentación arquitectónica sigue una estructura clara en `/docs/architecture/` para garantizar el control de versiones en Git y la trazabilidad del diseño:

```text
/docs/architecture/
├── README.md                          # Visión general y matriz de sincronía topológica
├── adr/                               # Registros de Decisiones de Arquitectura (ADRs)
│   ├── 0001-patron-arquitectonico.md  # ADR-001: Servicio de Reconocimiento de Voz
│   ├── 0002-sistema-de-persistencia.md# ADR-002: Arquitectura Monolito Modular
│   └── 0003-estrategia-seguridad.md   # ADR-003: Comunicación en Tiempo Real con WebSockets
└── diagrams/                          # Diagramas en PlantUML (.puml)
    ├── c4-contexto.puml               # Diagrama de flujo e interacción de voz
    └── secuencia-proceso-clave.puml   # Diagrama de componentes y módulos del backend
