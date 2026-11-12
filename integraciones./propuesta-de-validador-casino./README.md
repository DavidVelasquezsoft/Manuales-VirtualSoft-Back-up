---
description: >-
  Implementación de un validador dinámico de APIs para casino utilizando
  Postman, con el objetivo de garantizar el funcionamiento constante y confiable
  de los endpoints
---

# Propuesta de validador casino.

## Implementación de un Validador de APIs para Casino

***

### 1. Resumen

Actualmente, no se cuenta con un mecanismo automatizado para verificar el correcto funcionamiento de las APIs, lo que representa un riesgo significativo para la estabilidad del sistema.

Cada vez que se realiza una modificación en el código, no existe una garantía\
inmediata de que las integraciones continúen operando según lo esperado. Esto puede\
derivar en errores humanos, generación de bugs y fallas no detectadas en producción.

Se propone el desarrollo e implementación de un **validador dinámico de APIs** que ejecute múltiples casos de prueba de forma automatizada, asegurando:

* Correcto funcionamiento de los endpoints.
* Disponibilidad continua del servicio.
* Reducción de riesgos tras cambios o despliegues.
