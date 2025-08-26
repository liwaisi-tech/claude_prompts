# Nueva Funcionalidad

## Descripción
Prompt para diseñar e implementar nuevas funcionalidades en sistemas existentes, considerando arquitectura, integración y mejores prácticas.

## PROMPT
Actúa como un arquitecto de software senior especializado en [TECNOLOGÍA/FRAMEWORK]. Tu tarea es analizar un repositorio existente y diseñar la implementación de una nueva funcionalidad, considerando la arquitectura actual y las mejores prácticas.

**Información requerida:**
- Repositorio base: [URL_REPOSITORIO]
- Nueva funcionalidad: [DESCRIPCIÓN_FUNCIONALIDAD]
- Flujo propuesto: [PASOS_DEL_FLUJO]
- Tecnologías involucradas: [TECNOLOGÍAS_ADICIONALES]

**Tu análisis debe seguir este orden:**

### 1. Análisis del Repositorio
**Estructura de Archivos:**
- Organización de directorios y archivos principales
- Puntos de entrada y módulos core
- Configuraciones existentes

**Dependencias:**
- Librerías y frameworks utilizados
- Versiones y compatibilidad
- Gestores de paquetes

**Patrones de Código:**
- Arquitectura utilizada (MVC, microservicios, etc.)
- Estándares de codificación
- Patrones de diseño implementados

### 2. Arquitectura Propuesta
**Diseño de Alto Nivel:**
- Diagrama de flujo de la nueva funcionalidad
- Integración con componentes existentes
- Puntos de extensión identificados

**Consideraciones de Integración:**
- Compatibilidad con código existente
- Impacto en rendimiento del sistema
- Nuevas dependencias requeridas

### 3. Plan de Implementación
**Modificaciones Necesarias:**
- Archivos a modificar
- Nuevos módulos/componentes a crear
- Configuraciones adicionales

**Pruebas Unitarias:**
- Casos de prueba principales
- Mocks y stubs necesarios
- Estrategia de testing

**Consideraciones Técnicas:**
- Manejo de errores
- Logging y monitoreo
- Optimizaciones de rendimiento

La respuesta debe estructurarse con:
- Análisis detallado del repositorio en secciones separadas
- Arquitectura visual con diagramas de flujo
- Plan de implementación paso a paso
- Código de ejemplo para componentes clave
- Lista específica de pruebas unitarias
- Consideraciones técnicas y de rendimiento

## Ejemplo
Actúa como un arquitecto de software senior especializado en firmware para esp32, usando el framework esp-idf . Tu tarea es analizar un repositorio existente y diseñar la implementación de una nueva funcionalidad, considerando la arquitectura actual y las mejores prácticas.
**Tu análisis debe seguir este orden:**

### 1. Análisis del Repositorio
**Estructura de Archivos:**
- Organización de directorios y archivos principales
- Puntos de entrada y módulos core
- Configuraciones existentes

**Dependencias:**
- Librerías y frameworks utilizados
- Versiones y compatibilidad
- Gestores de paquetes

**Patrones de Código:**
- Arquitectura utilizada (MVC, microservicios, etc.)
- Estándares de codificación
- Patrones de diseño implementados

### 2. Arquitectura Propuesta
**Diseño de Alto Nivel:**
- Diagrama de flujo de la nueva funcionalidad
- Integración con componentes existentes
- Puntos de extensión identificados

**Consideraciones de Integración:**
- Compatibilidad con código existente
- Impacto en rendimiento del sistema
- Nuevas dependencias requeridas

### 3. Plan de Implementación
**Modificaciones Necesarias:**
- Archivos a modificar
- Nuevos módulos/componentes a crear
- Configuraciones adicionales

**Pruebas Unitarias:**
- Casos de prueba principales
- Mocks y stubs necesarios
- Estrategia de testing

**Consideraciones Técnicas:**
- Manejo de errores
- Logging y monitoreo
- Optimizaciones de rendimiento

**Entrada:**
- Repositorio base: https://github.com/liwaisi-tech/chicken-coop-cam-esp32
- Nueva funcionalidad: Sistema de detección de movimiento con notificación WhatsApp
- Flujo propuesto:
  1. Sensor infrarrojo detecta movimiento
  2. ESP32-CAM toma foto
  3. Imagen se sube a Google Drive
  4. Se envía mensaje con URL vía CallMeBot
  5. Usuario recibe notificación en WhatsApp
- Tecnologías: ESP-IDF, CallMeBot API, Google Drive API

## Formato de Salida
La respuesta debe estructurarse con:
- Análisis detallado del repositorio en secciones separadas
- Arquitectura visual con diagramas de flujo
- Plan de implementación paso a paso
- Código de ejemplo para componentes clave
- Lista específica de pruebas unitarias
- Consideraciones técnicas y de rendimiento