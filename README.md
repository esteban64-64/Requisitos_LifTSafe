# Requisitos_LifTSafe


# # ✅ Requisitos Funcionales

- **Registro y consulta offline**: La aplicación debe permitir capturar datos, consultar historial de equipos y generar borradores sin conexión a internet.  
- **Plantillas digitales adaptativas**: Formularios que cambien según el tipo de equipo inspeccionado para estandarizar datos y evitar campos irrelevantes.  
- **Vinculación automática de evidencias**: Las fotos y videos deben asociarse al punto de inspección correspondiente de manera automática.  
- **Generación de borradores en campo**: El sistema debe producir un informe preliminar inmediato al finalizar la inspección.  
- **Firma digital en sitio**: Técnicos y clientes deben poder firmar directamente desde la tableta o móvil.  
- **Panel de control (dashboard)**: Vista en tiempo real del estado de las inspecciones (pendientes, en curso, finalizadas).  
- **Flujos de trabajo digitales**: Revisión y aprobación de informes con firma electrónica, eliminando procesos en papel.  
- **Integración con sistemas corporativos**: Debe conectarse con ERP, CRM, facturación y contabilidad mediante APIs.  
- **Módulo de analítica y reporting**: Generación de reportes agregados (cumplimiento, productividad, tiempos, tendencias).  
- **Gestión de roles y accesos**: Control de permisos según perfil (inspectores, coordinadores, administradores).  
- **Respaldo y recuperación de información**: Sincronización con la nube y recuperación de datos en caso de pérdida.  

---

# ⚙️ Requisitos No Funcionales

- **Disponibilidad offline-online**: Capacidad de sincronizar datos sin conflictos ni duplicados.  
- **Tiempo de respuesta rápido**: El sistema debe responder de forma ágil al guardar y cargar información en campo.  
- **Escalabilidad**: Soportar más inspectores, clientes y volúmenes de evidencias multimedia sin degradación.  
- **Seguridad**:  
  - Autenticación robusta.  
  - Encriptación de datos en tránsito y en reposo.  
  - Control de accesos por roles.  
  - Backups automáticos en la nube diarios.  
- **Disponibilidad del servicio**: Recuperación máxima en 24 horas ante fallos.  
- **Compatibilidad**: Funcionar en dispositivos móviles (tabletas y celulares, incluso BYOD).  
- **Usabilidad**: Interfaz intuitiva, sencilla, sin curva de aprendizaje extensa para técnicos.  
- **Cumplimiento normativo**: Informes alineados con regulaciones como RETIE y RGPD.  
- **Mantenibilidad**: Arquitectura modular, con APIs estandarizadas para facilitar integración y evolución futura.

# Entrevista 1: Técnico / Inspector de Campo

*Pregunta:* ¿Podría presentarse y contarnos cómo es un día típico de inspección?  
*Respuesta:* Soy técnico de mantenimiento e inspector de campo. Reviso la seguridad, hago la inspección visual y luego la técnica: cables, frenos, puertas, cabina y sistema eléctrico. Anoto en libreta y tomo fotos con mi celular. Con una aplicación en tableta podría registrar todo en el momento y ahorrar tiempo.

*Pregunta:* ¿Qué herramientas utiliza actualmente para registrar la información?  
*Respuesta:* Uso papel y bolígrafo. Las fotos las tomo con el celular, pero luego debo pasarlas al computador. Una app me permitiría registrar todo en un solo dispositivo.

*Pregunta:* ¿Qué tipo de datos registra normalmente?  
*Respuesta:* Medidas de holgura, estado de frenos, cables, iluminación, pruebas de seguridad… unas 25 a 30 observaciones. Todo lo hago manual, pero con una app móvil podría organizar esos datos en plantillas.

*Pregunta:* ¿Cómo maneja las fotos y videos?  
*Respuesta:* Hoy las paso manualmente al computador. Es muy demorado. Si la app las vinculara de inmediato al informe, sería ideal.

*Pregunta:* ¿Necesita consultar información histórica de los equipos?  
*Respuesta:* Sí. Actualmente debo llamar a oficina o buscar carpetas impresas. Con una tableta podría abrir de una vez el historial del ascensor.

*Pregunta:* ¿Qué problemas tiene con la conectividad en campo?  
*Respuesta:* Muchos. En sótanos no hay señal. La aplicación debería funcionar sin internet y sincronizar después.

*Pregunta:* ¿Cómo transforma sus notas en el informe final?  
*Respuesta:* En la oficina paso todo a Word o Excel. Eso puede tardar hasta 3 horas. Con una app, el informe quedaría prácticamente listo en el sitio.

*Pregunta:* ¿Qué partes del informe son críticas?  
*Respuesta:* Datos técnicos, observaciones, fotos y firmas. Si pudiera firmar directamente en la tableta con el cliente, sería perfecto.

*Pregunta:* En conclusión, ¿qué espera de un sistema ideal?  
*Respuesta:* Una app móvil o para tableta que funcione offline, con plantillas inteligentes, fotos automáticas y firmas digitales.


# Entrevista 2: Jefe de Mantenimiento / Coordinador de Operaciones

*Pregunta:* ¿Podría presentarse y contarnos cómo gestiona actualmente las inspecciones?  
*Respuesta:* Soy coordinador de operaciones y asigno y reviso inspecciones. Hoy usamos correo o WhatsApp, lo cual es muy informal. Con una app podría asignar tareas y ver el avance en tiempo real.

*Pregunta:* ¿Cómo monitorea el progreso de las inspecciones?  
*Respuesta:* Solo me entero cuando llega el informe final. Con un dashboard en la aplicación, vería en qué etapa está cada técnico.

*Pregunta:* ¿Cómo recibe y aprueba los informes?  
*Respuesta:* Los recibo en PDF o Word y los reviso manualmente. Sería más ágil aprobarlos digitalmente en la app.

*Pregunta:* ¿Qué problemas encuentra con el proceso actual?  
*Respuesta:* Se pierde tiempo transcribiendo datos, los informes no son uniformes y se cometen errores. Con plantillas predefinidas todo sería más consistente.

*Pregunta:* ¿Ha tenido incidentes por retrasos?  
*Respuesta:* Sí. Algunos informes llegaron tarde y generaron quejas de clientes. Una app aceleraría la entrega.

*Pregunta:* ¿Qué reportes necesitaría el nuevo sistema?  
*Respuesta:* Indicadores de cumplimiento, productividad, tiempos y alertas de retrasos.

*Pregunta:* ¿Cuál sería su prioridad principal con este sistema?  
*Respuesta:* Mejorar la eficiencia del equipo y aumentar la satisfacción del cliente.


# Entrevista 3: Gerente de TI

*Pregunta:* ¿Podría presentarse y describir la infraestructura tecnológica actual de la empresa?  
*Respuesta:* Soy gerente de TI. Tenemos servidores en la nube, correo corporativo y un sistema contable. No usamos ERP completo. Una app móvil conectada integraría todo.

*Pregunta:* ¿Qué requisitos técnicos debería cumplir el nuevo sistema?  
*Respuesta:* Debe ser rápido, seguro, fácil de usar, trabajar offline y sincronizar después. Además, integrarse con contabilidad y CRM.

*Pregunta:* ¿Qué nivel de seguridad es crítico?  
*Respuesta:* Autenticación segura, encriptación de datos y control de accesos por roles. La app debe proteger toda la información de clientes e inspecciones.

*Pregunta:* ¿Qué estrategia de backup se requiere?  
*Respuesta:* Respaldos automáticos en la nube todos los días y recuperación en máximo 24 horas.

*Pregunta:* ¿Qué tan escalable debe ser el sistema?  
*Respuesta:* Muy escalable. Debe soportar más inspectores y más clientes sin problemas.

*Pregunta:* ¿Qué recomienda para que sea adoptado por el personal?  
*Respuesta:* Que sea simple y práctico. Si la app es complicada, los técnicos no la usarán.
  
