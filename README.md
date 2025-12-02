# TR-2 Vanguard Project 🚀

> **Misión de Certificación L2 / Plataforma de Investigación Experimental**
>
> *Dragons Space Team (DST)*

El **TR-2 Vanguard** es un vehículo de lanzamiento de alta potencia diseñado para validar tecnologías avanzadas de propulsión, aviónica y recuperación. Este repositorio contiene la documentación técnica, simulaciones, código fuente y diseños de hardware del proyecto completo.

## 📋 Resumen Técnico

El proyecto integra múltiples disciplinas de ingeniería para alcanzar un apogeo nominal de **3,166 metros AGL** con recuperación controlada.

### 🔥 Propulsión: Motor "Trinity" (DST-L1780)
*   **Clase:** L (High Power Rocketry).
*   **Química:** KNSB Catalizado (Nitrato de Potasio / Sorbitol / Óxido de Hierro / Aluminio).
*   **Ingeniería:** Grano con geometría BATES optimizada y tobera de grafito de alta densidad para soportar temperaturas de $\approx 3600^\circ C$.
*   **Hardware:** Carcasa 6061-T6 tipo 6268M.

### 💻 Aviónica y Software
*   **Flight Core:** Desarrollado 100% en **Rust** para seguridad de memoria crítica y prevención de *runtime exceptions*.
*   **Estación Terrena:** Interfaz TUI (Terminal User Interface) con análisis de telemetría en tiempo real.
*   **Inteligencia Artificial:** Implementación de **Gemma (SLM)** para análisis semántico de errores y reconstrucción de paquetes de telemetría corruptos (OFA - On-Flight Analysis).
*   **Comunicaciones:** Enlace de datos seguro (SELinux) y transmisión de video 5.8GHz.

### 🪂 Sistemas de Recuperación
*   **Estrategia:** Despliegue Dual (Dual Deploy) con *Jolly Logic Chute Release*.
*   **Paracaídas Principal:** Diseño **Semi-Toroidal** basado en geometría no euclidiana para maximizar el coeficiente de arrastre ($C_d \approx 2.2$) y estabilidad de descenso.
*   **Tren de Recuperación:** Híbrido Kevlar (Térmico) + Nylon Tubular (Elástico) para mitigación de cargas de choque.

---

## 📂 Estructura del Repositorio

Este proyecto está organizado para escalar a medida que se añaden nuevos módulos de ingeniería:

```
TR-2-Vanguard/
├── docs/               # Documentación técnica, Papers y Reportes (LaTeX/PDF)
│   ├── img/            # Activos gráficos y diagramas
│   └── TR-2-Vanguard.tex
├── simulations/        # Modelos físicos y matemáticos
│   ├── openrocket/     # Archivos de simulación de vuelo (.ork)
│   └── motors/         # Curvas de empuje y simulación balística (.eng, .ric)
├── src/                # (Próximamente) Código fuente del Flight Core (Rust)
├── ground_station/     # (Próximamente) Software de control terrestre y modelos IA
└── hardware/           # (Próximamente) Planos CAD, diagramas esquemáticos y PCBs
```

## 🛠️ Requisitos de Desarrollo

Para compilar la documentación y ejecutar futuras simulaciones:

*   **LaTeX:** TeX Live o distribución similar (para generar los PDFs en `/docs`).
*   **OpenRocket:** Java Runtime Environment (JRE).
*   **Rust Toolchain:** `cargo`, `rustc` (para el software de vuelo).

## 📄 Licencia y Referencias

Este proyecto utiliza estándares de la *Tripoli Rocketry Association* y referencias académicas (MIT Rocket Team, Nakka Rocketry) detalladas en la documentación técnica.

---
*Generado automáticamente el 2 de Diciembre, 2025.*
