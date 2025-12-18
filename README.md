# 🛡️ SOC Home Lab - Entorno de Práctica Profesional

![GitHub Last Commit](https://img.shields.io/github/last-commit/tuusuario/soc-home-lab)
![GitHub Stars](https://img.shields.io/github/stars/tuusuario/soc-home-lab)
![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-Linux%20%7C%20Windows-success)

Laboratorio de Security Operations Center construido desde cero para desarrollo de habilidades en detección y respuesta a amenazas.

## 🎯 Objetivo del Proyecto
Simular un entorno SOC empresarial completo con herramientas enterprise de código abierto para:
- Análisis de logs en tiempo real
- Detección de amenazas
- Respuesta a incidentes
- Caza de amenazas (Threat Hunting)

## 🏗️ Arquitectura
![Diagrama del Laboratorio](images/diagrama_lab.png)

**Especificaciones Técnicas:**
- **Host:** Ubuntu 22.04 LTS (8GB RAM, 4 Cores)
- **Virtualización:** Oracle VirtualBox 7.0
- **Red:** Segmentada (192.168.1.0/24)
- **Herramientas Implementadas:**

| Herramienta | Versión | Propósito |
|-------------|---------|-----------|
| Wazuh | 4.5 | SIEM/XDR |
| Splunk | 9.0 | SIEM (Alternative) |
| TheHive | 5.0 | Gestión de Incidentes |
| Elastic Stack | 8.10 | Análisis de Logs |
| Kali Linux | 2023.4 | Máquina de ataque |

## 🚀 Instalación Rápida
```bash
# Clonar repositorio
git clone https://github.com/tuusuario/soc-home-lab.git
cd soc-home-lab

# Ejecutar script de instalación
chmod +x scripts/setup_lab.sh
sudo ./scripts/setup_lab.sh
