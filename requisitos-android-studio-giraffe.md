# Requisitos Mínimos para Android Studio Giraffe 2022.3.1

Este documento detalla los requisitos mínimos del sistema para ejecutar Android Studio Giraffe 2022.3.1.

## Windows

- **Sistema Operativo:** Windows 10 de 64 bits (no se admiten CPUs Windows basadas en ARM)
- **RAM:** 8 GB mínimo para Android Studio, 16 GB recomendado si se usa el Emulador de Android
- **Espacio en Disco:** Al menos 8 GB de espacio disponible en disco, se recomienda SSD
- **Resolución de Pantalla:** 1280 x 800 mínimo

## macOS

- **Sistema Operativo:** macOS 12 (Monterey) o superior
- **RAM:** 8 GB mínimo para Android Studio, 16 GB recomendado si se usa el Emulador de Android
- **Espacio en Disco:** Al menos 8 GB de espacio disponible en disco, se recomienda SSD
- **Resolución de Pantalla:** 1280 x 800 mínimo

## Linux

- **Sistema Operativo:** 
  - Distribuciones de 64 bits únicamente
  - Ubuntu 18.04 o superior
  - Debian 10 o superior
  - Escritorio GNOME o KDE
- **Bibliotecas del Sistema:**
  - GNU C Library (glibc) 2.27 o posterior
  - Arquitectura x86_64 (ARM no es oficialmente compatible con el IDE)
- **RAM:** 8 GB mínimo para Android Studio, 16 GB recomendado si se usa el Emulador de Android
- **Espacio en Disco:** Al menos 8 GB de espacio disponible en disco (25 GB recomendado), se recomienda SSD
- **Resolución de Pantalla:** 1280 x 800 mínimo
- **Adicional:** Python 3 para algunas tareas del emulador y dispositivos

## Notas Adicionales

- Para una mejor experiencia con proyectos más grandes, se recomiendan más recursos de RAM y CPU.
- Ejecutar el Emulador de Android o múltiples emuladores simultáneamente requiere memoria adicional (aproximadamente 4 GB de RAM por AVD).
- El Kit de Desarrollo de Java (JDK) está incluido con Android Studio.
- Para capacidades más avanzadas (múltiples emuladores, proyectos grandes), es mejor exceder las especificaciones mínimas.
- **Para usuarios de Linux:** Para verificar la versión de glibc de su sistema, ejecute: `ldd --version`

## Referencias

- [Instalar Android Studio - Android Developers](https://developer.android.com/studio/install)
- [Descargar Android Studio - Android Developers](https://developer.android.com/studio)
