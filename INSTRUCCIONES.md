# Instrucciones del proyecto SAP Clean Core

## Contexto
El proyecto complementa el estudio SAP Integration Suite/CPI, cuya fecha objetivo de cierre es el 13 de noviembre de 2026. Meta profesional: Ingeniero de Integración y Desarrollo SAP BTP, con especialización en desarrollo backend, integración y extensiones side-by-side alineadas con Clean Core. El objetivo es construir competencias demostrables para proyectos independientes, no atribuir experiencia productiva inexistente.

## Conducto de trabajo
1. Avanzar de a un microaprendizaje por vez, sin saltar al siguiente sin validación.
2. Antes de cada sesión, indicar objetivo, prerrequisitos y resultado observable.
3. Explicar conceptos brevemente y relacionarlos con escenarios reales de integración y modernización.
4. Desarrollar laboratorio guiado, con pasos reproducibles y comandos/código cuando corresponda.
5. Verificar resultados con pruebas, logs, capturas o archivos versionables.
6. Documentar errores, causas comprobadas y soluciones aplicadas.
7. Cerrar cada módulo con resumen, preguntas de comprobación y criterios de aprobación.
8. Actualizar el estado en README solo después de evidencias verificadas.
9. No asumir acceso a S/4HANA ni a servicios BTP de pago; usar mocks y distinguir simulación de integración real.
10. No cambiar alcance, prioridades ni decisiones arquitectónicas importantes sin analizarlas primero con el usuario.

## Plantilla de cada sesión
- ID y título
- Objetivo
- Conceptos y referencias oficiales
- Prerrequisitos
- Laboratorio paso a paso
- Resultado esperado
- Validación y evidencias
- Problemas y soluciones
- Aprendizajes y preguntas
- Estado: Pendiente / En curso / Revisado / Completado / Reforzar / Bloqueado

## Priorización
Hasta el 13-11-2026, priorizar terminar Integration Suite. Preparar Clean Core documentalmente; comenzar prácticas después de ese hito, sujeto a confirmación del avance real.

## Veracidad
Separar hecho verificado, hipótesis, recomendación y simulación. No afirmar certificaciones, experiencia profesional o ejecución de laboratorios sin evidencia. Usar documentación oficial SAP para validar características y disponibilidad de servicios.

## Gestión de estados y control de cambios
- Usar en README exactamente los seis estados definidos en la sección **Estados**.
- Al comenzar un tema, actualizarlo a `En curso`; si solo se revisó teoría, usar `Revisado`.
- Cambiar a `Completado` únicamente cuando se haya verificado la evidencia exigida para ese tema, dejando un resumen concreto en la columna **Evidencia**.
- Usar `Bloqueado` cuando una dependencia impida continuar, y `Reforzar` cuando sea necesario repetir una práctica o consolidar conocimientos.
- Mantener en README un **Control de cambios**, con fecha, versión, cambio y motivo. Registrar allí modificaciones del syllabus, objetivos o metodología; Git conserva el historial detallado de archivos.
- Nunca registrar como ejecutada una prueba que solamente se haya diseñado o simulado.
