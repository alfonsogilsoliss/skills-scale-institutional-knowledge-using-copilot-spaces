# Descripción General de Gestión de Proyectos OctoAcme

## Propósito
Proveer una introducción concisa y compartible de cómo OctoAcme gestiona proyectos, para que los nuevos integrantes del equipo puedan entender rápidamente el enfoque, los roles y los artefactos clave.

## Alcance
Aplica a todos los proyectos multifuncionales que entregan funcionalidades de producto, servicios o integraciones.

## Principios
- Cliente primero: priorizar el valor y la usabilidad para el cliente.
- Entrega iterativa: entregar incrementos pequeños y verificables.
- Propiedad clara: cada proyecto tiene un Project Manager (PM) y un Product Lead designados.
- Decisiones basadas en datos: medir el impacto e iterar con base en evidencia.
- Seguridad psicológica: fomentar la retroalimentación y el aprendizaje continuo.

## Roles Principales
- **Project Manager (PM):** coordina la entrega, cronogramas, riesgos y comunicaciones.
- **Product Manager (PdM):** define los resultados esperados, prioriza el backlog y mide el éxito.
- **Desarrolladores:** implementan funcionalidades, colaboran en diseño y verificabilidad.
- **Analista de Calidad (QA):** valida la calidad, ejecuta planes de prueba y gestiona defectos.
- **Diseñador UX/UI:** asegura la usabilidad, accesibilidad y calidad de la experiencia de usuario.
- **Líder Técnico (Tech Lead):** establece estándares técnicos, guía al equipo de desarrollo y asegura la viabilidad técnica.
- **Stakeholders Externos:** aportan perspectiva de negocio o usuarios finales, validan entregables y participan en revisiones clave.

Para descripciones detalladas de cada rol, consultar [`docs/octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md).

## Artefactos Clave
- Charter del Proyecto / One-pager
- Roadmap y Plan de Releases
- Backlog del Sprint/Iteración
- Criterios de Aceptación y Definición de Hecho (DoD)
- Registro de Riesgos
- Notas de Retrospectiva y elementos de acción

## Ciclo de Vida (alto nivel)
1. Iniciación: declaración del problema, identificación de stakeholders, cronograma de alto nivel.
2. Planificación: alcance, recursos, hitos, dependencias. Participan PM, PdM, Líder Técnico y Diseñador UX/UI.
3. Ejecución: construir, probar, revisar, iterar. Participan todos los roles del equipo.
4. Liberación: desplegar, verificar, anunciar. QA y Stakeholders Externos validan antes del lanzamiento.
5. Cierre & Retrospectiva: capturar aprendizajes y próximos pasos. Todos los roles participan.

## Cadencia de Comunicación
- Sincronización semanal entre PM + PdM (+ Líder Técnico cuando haya temas técnicos relevantes)
- Standups dos veces por semana para el equipo de entrega (o según se acuerde)
- Actualizaciones mensuales a Stakeholders Externos
- Revisiones de hitos con participación del Stakeholder Externo para validación y feedback
- Escalaciones ad hoc según sea necesario

## Cómo usar esta documentación
- Mantén el Charter del Proyecto actualizado en el repositorio del proyecto.
- Agrega documentos de proceso específicos en `.copilot/` si deseas que Copilot Spaces los use como contexto.
- Consulta [`docs/octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) para incorporar nuevos roles o ajustar la estructura del equipo.
