# OctoAcme — Ejecución y Seguimiento

## Propósito
Orientación para gestionar la ejecución diaria y hacer seguimiento del avance hacia los hitos del proyecto.

## Ritmo del Equipo
- Standups diarios (15 min) — enfocados en avance, bloqueos y dependencias; participan todos los roles del equipo
- Sincronización semanal de entrega — mostrar avance, actualizaciones y riesgos identificados (PM, PdM, Líder Técnico)
- Demo/Revisión al final de cada sprint o hito — con participación del Stakeholder Externo para validación y feedback

## Flujos de Trabajo
- Usar el tablero del proyecto (p. ej., GitHub Projects) con columnas: Backlog, Listo, En Progreso, En Revisión, QA, Hecho
- Flujo de Pull Requests:
  - PRs pequeños (<= 400 líneas cuando sea posible)
  - Incluir enlace al issue y criterios de aceptación en la descripción del PR
  - Ejecutar pruebas automáticas y linting en CI antes de solicitar revisión
  - El **Líder Técnico** participa en las revisiones de código para asegurar los estándares técnicos
  - Requerir al menos una aprobación antes de hacer merge (o según la política del equipo)

## Calidad y Pruebas
- Pruebas unitarias para nueva lógica
- Pruebas de integración donde corresponda
- Pruebas de humo end-to-end para flujos críticos antes del release
- Escaneo de seguridad en CI
- **QA** ejecuta pruebas de aceptación manual cuando se requiere validación de funcionalidades
- **Diseñador UX/UI** participa en pruebas de usabilidad y accesibilidad antes del cierre de hitos

## Reportes y Métricas
- Rastrear velocidad y burndown
- Monitorear las métricas de éxito identificadas en el One-pager del proyecto
- Usar dashboards para señales clave (errores, latencia, uso)
- **QA** reporta métricas de calidad y estado de defectos en las sincronizaciones semanales

## Escalamiento de Bloqueos
- Nivel 1: Triaje a nivel de equipo en el standup diario
- Nivel 2: El PM escala al Product Lead y a los equipos dependientes; el **Líder Técnico** coordina la resolución técnica
- Nivel 3: Escalamiento al Sponsor para problemas con impacto en el negocio; notificar al **Stakeholder Externo** si el bloqueo afecta hitos acordados

## Checklist de Ejecución
- [ ] Convenciones de branching y PR documentadas en el repositorio
- [ ] CI configurado para pruebas y lint (validado por el Líder Técnico)
- [ ] Demos regulares calendarizadas con participación del Stakeholder Externo
- [ ] Registro de Riesgos actualizado semanalmente
- [ ] QA integrado en el flujo de entrega desde el inicio del sprint
- [ ] Diseñador UX/UI disponible para consultas y revisiones durante la ejecución
