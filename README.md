# SAP Clean Core Learning Lab

Curso práctico y progresivo para estudiar **SAP Clean Core**, extensibilidad y desarrollo de soluciones en **SAP BTP**, con énfasis en extensiones **side-by-side** y SAP CAP (Node.js). Cada tema mantiene un estado explícito para distinguir lo estudiado de lo realmente practicado y validado.

## Objetivo

Aprender a tomar decisiones de extensibilidad alineadas con Clean Core y aplicarlas a un caso de estudio reproducible, combinando diseño de arquitectura, contratos de integración, desarrollo backend y validación práctica.

Este laboratorio complementa [SAP Integration Suite Learning Lab](https://github.com/victorarellano/sap-integration-suite-learning-lab) y contribuye a construir el perfil de **Ingeniero de Integración y Desarrollo SAP BTP**. La prioridad actual es finalizar el laboratorio de Integration Suite el **13 de noviembre de 2026**; los ejercicios de Clean Core comenzarán después de ese hito, salvo cambio acordado.


## Planificación del curso

| Hito | Fecha |
|---|---|
| Inicio estimado | 16 de noviembre de 2026 |
| Término estimado | 15 de enero de 2027 |
| Duración estimada | 9 semanas calendario |
| Modalidad | Microaprendizajes progresivos y laboratorios prácticos |
| Criterio de finalización | Todos los temas completados y proyecto integrador validado |

### Consideraciones

- El curso comenzará después de finalizar SAP Integration Suite, cuya fecha objetivo es el 13 de noviembre de 2026.
- Las fechas son estimaciones de planificación, no compromisos rígidos.
- El avance dependerá de la complejidad de los laboratorios y de la disponibilidad de los servicios SAP necesarios.
- Se priorizará la comprensión y validación práctica por sobre el cumplimiento estricto de las fechas.
- La fecha de término podrá ajustarse según el avance real del curso.
- Al comenzar se registrará la fecha real de inicio y, al finalizar, la fecha real de término.

## Estados

| Estado | Significado |
|---|---|
| ⬜ `Pendiente` | Aún no iniciado |
| 🟨 `En curso` | Se está estudiando o implementando |
| 🟦 `Revisado` | Conceptos vistos, falta validación práctica |
| ✅ `Completado` | Conceptos revisados y ejercicio validado con evidencia |
| 🔁 `Reforzar` | Visto anteriormente, pero requiere práctica adicional |
| ⛔ `Bloqueado` | Existe una dependencia o problema que impide continuar |

Un ejercicio de análisis o diseño puede completarse sin desplegar software si cuenta con **criterios de aceptación y evidencia verificable**. Una prueba realizada con mocks nunca se registrará como integración real con S/4HANA.

## Ruta del curso

| ID | Tema | Estado | Evidencia |
|---|---|---|---|
| 00 | Fundamentos: SAP Clean Core y propósito | ⬜ `Pendiente` | — |
| 01 | Arquitectura SAP S/4HANA, SAP BTP y límites del core | ⬜ `Pendiente` | — |
| 02 | Estrategias de extensibilidad: key-user, developer y side-by-side | ⬜ `Pendiente` | — |
| 03 | APIs liberadas y SAP Business Accelerator Hub | ⬜ `Pendiente` | — |
| 04 | Eventos, contratos y desacoplamiento | ⬜ `Pendiente` | — |
| 05 | SAP CAP con Node.js: servicio de extensión | ⬜ `Pendiente` | — |
| 06 | Autenticación y autorización entre componentes | ⬜ `Pendiente` | — |
| 07 | SAP Integration Suite en arquitectura Clean Core | ⬜ `Pendiente` | — |
| 08 | Persistencia, consistencia y propiedad de datos | ⬜ `Pendiente` | — |
| 09 | Ciclo de vida, despliegue y observabilidad | ⬜ `Pendiente` | — |
| 10 | Decisiones arquitectónicas y evaluación de alternativas | ⬜ `Pendiente` | — |
| 11 | Laboratorio integrador final: extensión side-by-side | ⬜ `Pendiente` | — |

> **Alcance:** esta es una ruta de aprendizaje propia, no un temario oficial ni una certificación SAP. La evidencia y el estado de cada tema se actualizarán al ejecutarlo. Los enlaces a documentos se incorporarán cuando existan archivos reales.

## Control de cambios

Este registro documenta **cambios en el plan de estudio y la metodología**; el historial completo de modificaciones de archivos se conserva en Git.

| Fecha | Versión | Cambio | Motivo |
|---|---|---|---|
| 2026-10-26 | 0.2.0 | README reorganizado conforme al laboratorio de Integration Suite: estados, ruta, evidencias, control de cambios y criterios de validación | Unificar el seguimiento de ambos proyectos |
| 2026-10-26 | 0.1.0 | Definición inicial del proyecto y syllabus de Clean Core | Preparar el nuevo laboratorio |

Las futuras entradas se añadirán cuando cambien el alcance, el orden de los temas, sus criterios de validación o la metodología. El avance de un tema se refleja en la tabla **Ruta del curso** y su documentación, sin generar necesariamente una nueva versión del syllabus.

## Registro de conocimiento y problemas

Los comportamientos inesperados, dudas resueltas, limitaciones de SAP BTP Trial y referencias oficiales se documentarán en `docs/kba-y-hallazgos.md` cuando comiencen los laboratorios. Se diferenciarán explícitamente hechos comprobados, hipótesis y simulaciones.

## Metodología

Cada tema se aborda como **microaprendizaje**: objetivo breve, conceptos mínimos, ejercicio o laboratorio guiado, validación observable y registro de estado. Si una práctica no se puede ejecutar por falta de acceso a SAP S/4HANA u otro servicio, se describirá la limitación y se podrá usar una simulación debidamente identificada.

El conducto de trabajo y las reglas para actualizar estados y cambios están definidos en [INSTRUCCIONES.md](INSTRUCCIONES.md).

## Entorno inicial del laboratorio

- **Editor:** Visual Studio Code.
- **Control de versiones:** Git.
- **Lenguaje principal previsto para extensiones:** Node.js, con SAP CAP.
- **SAP BTP / S/4HANA:** disponibilidad para este nuevo proyecto aún no validada.
- **Pruebas:** herramientas y servicios por definir según cada laboratorio.

> **Seguridad:** no guardar credenciales, tokens, contraseñas, claves privadas ni otros secretos reales en el repositorio. Revisar capturas antes de versionarlas.
