# bug-free-engine
## Caso 2 — Filtración en la app de citas *Tea*

**Hipótesis:**

La brecha de seguridad en *Tea* fue consecuencia de una mala gestión de sistemas heredados durante la migración de datos.

**Preguntas:**

1. ¿Qué vulnerabilidades específicas del sistema de almacenamiento “legacy” permitieron la exposición?
2. ¿Qué medidas implementó *Tea* después del incidente?

**Fuentes seleccionadas (8 fuentes):**

| Tipo | Fuente | Descripción / Características | URL / Medio |
| --- | --- | --- | --- |
| Primaria | Tea Dating Advice (declaración oficial) | Reconoce la brecha y causa raíz: bucket legacy público durante migración. | [Declaración oficial](https://www.teaforwomen.com/cyberincident) |
| Secundaria | National Law Review | Análisis legal y cumplimiento. Contexto de demandas y privacidad. | [Análisis legal](https://natlawreview.com/article/safest-space-spill-tea-dating-safety-app-targeted-massive-data-breach) |
| Secundaria | Malwarebytes | Segunda brecha: 1.1M mensajes y CVE-2025-54957. Detalles técnicos. | [Reporte técnico](https://www.malwarebytes.com/blog/news/2025/07/tea-dating-advice-app-has-users-private-messages-disclosed) |
| Secundaria | Appknox | Auditoría móvil: hardcoded secrets, sin jailbreak detection, sin SSL pinning, sin RASP. | [Informe de seguridad](https://www.appknox.com/blog/tea-app-data-breach-security-flaws-analysis-appknox) |
| Secundaria | USA Today / Chicago Sun-Times | Impacto social y recomendaciones para usuarias. | [Cobertura de impacto](https://chicago.suntimes.com/technology/2025/07/28/womens-dating-safety-app-tea-data-breach-impacting-thousands-photos) |
| Secundaria | Security Boulevard | Análisis de ambas brechas y patrones de seguridad deficientes. | [Análisis de seguridad](https://securityboulevard.com/2025/07/tea-app-data-breach-deepens-with-1-1-million-user-chats-exposed/) |
| Secundaria | [ClassAction.org](http://ClassAction.org) | Demandas colectivas y derechos de víctimas. | [Demandas colectivas](https://www.classaction.org/data-breach-lawsuits/tea-july-2025) |
| Secundaria | LiveNOW from FOX | Consecuencias reales del leak: uso indebido de datos en web y mapas. | [Cobertura en video](https://www.livenowfox.com/news/tea-app-breach-fallout) |
| Fuente rechazada | Reddit y 4chan | las fuentes se rechazaron por practicamente ser un foro de usuarios lo cual no deja pie para ser una fuente veridica |  |
| fuente rechazada | 404media | por tener un muro de pago para revisar el contenido |  |
