# Normativa Ambiental — Semana 2026-W32 (3 al 9 de agosto de 2026)

**Archivo de esta semana:** https://github.com/darioeva/normativa-ambiental-zarey/blob/claude/awesome-franklin-4rxx2z/normativa-ambiental-semana-2026-W32.md

**Procedimiento:** ZP-027 "Servicio de Identificación de Normativa Aplicable a Clientes" — Zarey Consultores. Ámbito: Ambiental.

> **Nota:** esta ejecución se activó por primera vez el **viernes 7 de agosto de 2026** (no un lunes). No existe archivo previo de la semana 2026-W32, por lo que esta tabla **no cubre los días previos de la semana (lunes 3 a jueves 6 de agosto)** salvo por hallazgos detectados retroactivamente dentro de la ventana de revisión de 3 días corridos (4–7 de agosto).

---

## Incidencia técnica transversal (afecta a todas las fuentes de esta ejecución)

Durante toda la ejecución del 7 de agosto de 2026, la herramienta de acceso directo (fetch de URL) devolvió `EGRESS_BLOCKED` en **todos** los dominios probados, incluyendo sitios de control neutros ajenos al ámbito regulatorio (google.com, example.com, mercadopublico.cl, wikipedia.org). Esto confirma que se trata de un **fallo técnico general del entorno de ejecución** (bloqueo del proxy de red saliente), **no** del bloqueo anti-bot específico que suelen presentar SMA/SNIFA/RETC. Como respaldo, toda la revisión se realizó con búsqueda web (WebSearch), tal como contempla el protocolo de la rutina. Esto implica que ningún hallazgo pudo confirmarse por lectura directa de la fuente primaria (HTML/PDF oficial); la confianza de varios hallazgos se limita por esto a "Media" en vez de "Alta". **Recomendación:** reintentar acceso directo (fetch) a `snifa.sma.gob.cl`, `www.dga.cl` / `dga.mop.gob.cl`, `www.contraloria.cl` y `www.sernageomin.cl` en la próxima ejecución para elevar la confianza de las conclusiones de "sin novedades" reportadas esta semana, ya que la ausencia de resultados de búsqueda es una evidencia más débil que un fetch directo confirmado.

---

## Tabla resumen acumulada — Semana 2026-W32

| Mes | Día | Tipo de Norma | N° de Norma | Ministerio/Servicio | Link | Origen | Clasificación |
|---|---|---|---|---|---|---|---|
| Agosto | 5 | Informativo institucional | No aplica | SMA | https://portal.sma.gob.cl/index.php/cuenta-publica-participativa-superintendencia-del-medio-ambiente-2026/ | Fuente fija | Interés |
| Agosto | 5 | Resolución Exenta | 4.225/2026 | MMA | https://mma.gob.cl/ley-rep-se-extiende-el-plazo-para-la-elaboracion-del-decreto-supremo-de-baterias/ | Fuente fija | Interés |
| Agosto | 7 | Comunicado operativo | Pendiente | RETC / MMA | https://retc.mma.gob.cl/ministerio-del-medio-ambiente-inicia-proceso-de-rectificacion-de-informacion-ruea-sinader/ | Fuente fija | Interés |
| Agosto | 5 | Comunicado técnico | No aplica | SERNAGEOMIN | https://chilepaisminero.com/sernageomin-desarrolla-un-observatorio-nacional-de-relaves/ | Fuente fija | Interés |

*Ningún hallazgo de esta semana se clasificó como "Aplicable". La ronda transversal (episodios críticos/alertas ambientales, SEREMI, Delegación Presidencial Regional, Gobierno Regional) no produjo hallazgos que superaran el filtro de relevancia del punto 5.1 del ZP-027 — ver sección correspondiente más abajo.*

---

## Bloques de detalle — Hallazgos nuevos (7 de agosto de 2026)

### 1. SMA — Cuenta Pública Participativa 2026

- **Tipo de norma:** Evento institucional (no es acto normativo ni resolución)
- **N° de norma:** No aplica
- **Ministerio/Servicio emisor:** Superintendencia del Medio Ambiente (SMA)
- **Fecha de publicación:** 5 de agosto de 2026
- **Link:** https://portal.sma.gob.cl/index.php/cuenta-publica-participativa-superintendencia-del-medio-ambiente-2026/
- **Qué establece:** La SMA presentó su Cuenta Pública Participativa 2026 (balance de gestión 2025): 8.222 denuncias ambientales ingresadas (récord histórico) y 5.446 resueltas en 2025; declara como línea de trabajo declarada fortalecer el enfoque preventivo vía reporte y monitoreo ambiental de titulares.
- **Alcance:** General/institucional. No crea obligación de cumplimiento nueva para titulares.
- **Excepciones:** No aplica.
- **Vigencia:** No aplica (evento de rendición de cuentas, no norma).
- **Obligación de reporte/plazo:** No genera obligación directa. Abre ventana de observaciones ciudadanas del **5 al 14 de agosto de 2026**; informe final anunciado para el 30 de septiembre de 2026. Cierra el 14-08-2026 para comentarios.
- **Clasificación:** De interés
- **Confianza: Media** — confirmado por múltiples referencias del propio portal.sma.gob.cl; no se pudo leer la página completa por la incidencia técnica de acceso directo descrita arriba.

### 2. MMA — Resolución Exenta N° 4.225/2026 (Ley REP — plazo Decreto Supremo de baterías)

- **Tipo de norma:** Resolución Exenta (acto administrativo que prorroga un plazo de tramitación regulatoria)
- **N° de norma:** 4.225/2026
- **Ministerio/Servicio emisor:** Ministerio del Medio Ambiente (MMA)
- **Fecha de publicación:** El acto está fechado 29 de julio de 2026; su circulación y cobertura (oficial y gremial) ocurrió el 5 de agosto de 2026, fecha en que fue detectado en esta revisión — se deja constancia de ambas fechas.
- **Link:** https://mma.gob.cl/ley-rep-se-extiende-el-plazo-para-la-elaboracion-del-decreto-supremo-de-baterias/
- **Qué establece:** Extiende por 6 meses (hasta el **29 de enero de 2027**) el plazo que tiene el MMA para elaborar la propuesta definitiva del Decreto Supremo que fijará las metas de recolección y valorización y demás obligaciones del producto prioritario **"baterías"** bajo la Ley REP (Ley 20.920). El motivo declarado es la recepción de 451 observaciones ciudadanas y 33 consultas internacionales durante la consulta pública del anteproyecto.
- **Alcance:** Nacional. Afecta el cronograma regulatorio de futuros obligados REP del producto prioritario "baterías" (productores, importadores).
- **Excepciones:** No aplica — es una prórroga de plazo administrativo interno, sin excepciones sustantivas.
- **Vigencia:** Resolución rige desde el 29-07-2026; nuevo plazo del Decreto Supremo vence el 29-01-2027.
- **Obligación de reporte/plazo:** Ninguna obligación de reporte inmediata para empresas; deben seguir el proceso en economiacircular.mma.gob.cl/baterias/ para el futuro Decreto Supremo.
- **Clasificación:** De interés (relevante a mediano plazo para clientes con productos "baterías" bajo Ley REP; sin obligación operativa inmediata).
- **Confianza: Alta** — triple corroboración (fuente oficial MMA + Revista Electricidad e Industria + Cámara de Comercio de Santiago), datos coincidentes en número, fecha y contenido. Nota: una búsqueda independiente sobre el Diario Oficial detectó menciones sueltas a esta misma resolución con una fecha distinta (4 de agosto) sin poder verificarlas; se resuelve la eventual discrepancia a favor de esta fuente triple-verificada (29-07-2026 como fecha del acto).

### 3. RETC / MMA — Proceso de rectificación de información RUEA y SINADER

- **Tipo de norma:** Comunicado operativo del RETC (Ventanilla Única), no es un acto normativo con número propio identificado
- **N° de norma:** Pendiente de publicación oficial — solo comunicado disponible a la fecha de esta revisión (se hicieron búsquedas adicionales específicas sin ubicar un número de resolución asociado)
- **Ministerio/Servicio emisor:** Ministerio del Medio Ambiente (MMA) — RETC / Portal Ventanilla Única
- **Fecha de publicación:** No confirmada con precisión dentro de los últimos 3 días; detectada en esta revisión del 7 de agosto de 2026. Solo se confirmó que el proceso operativo estará habilitado entre el 18 y el 29 de agosto de 2026 (con una semana adicional para casos pendientes).
- **Link:** https://retc.mma.gob.cl/ministerio-del-medio-ambiente-inicia-proceso-de-rectificacion-de-informacion-ruea-sinader/
- **Qué establece:** El MMA inicia un proceso de **rectificación de información** en los sistemas sectoriales **RUEA** (Registro Único de Emisiones Atmosféricas, DS 138) y **SINADER** (Sistema Nacional de Declaración de Residuos No Peligrosos), ambos parte de la Ventanilla Única del RETC. Solo los establecimientos **previamente notificados** deben reingresar exclusivamente la información solicitada (no la declaración completa), para corregir omisiones o inconsistencias por errores de sistema o de usuario. La información rectificada se incorporará a las estimaciones de emisiones usadas en la Declaración Jurada Anual (DJA), que comienza el 1 de octubre de 2026.
- **Alcance:** Limitado a establecimientos específicamente notificados por el MMA (deben verificar su inclusión en un listado publicado); no es universal para todos los declarantes RETC.
- **Excepciones:** Establecimientos no notificados no deben participar.
- **Vigencia:** Ventana habilitada del 18 al 29 de agosto de 2026, con una semana adicional para casos pendientes.
- **Obligación de reporte/plazo:** Establecimientos notificados deben reingresar la información solicitada dentro de la ventana 18–29 de agosto de 2026 (con extensión).
- **Clasificación:** De interés — **ALTA PRIORIDAD DE VALIDACIÓN** (posible impacto operativo directo si algún cliente de Zarey está entre los establecimientos notificados; no se pudo confirmar con certeza la fecha exacta de publicación ni el número de acto administrativo).
- **Confianza: Media** — contenido consistente en fuente oficial RETC y su réplica en Portal VU, pero sin poder confirmar fecha exacta de publicación por la incidencia de acceso directo.
- **Acción sugerida:** validar antes del 18-08-2026 si AA Chagres, Ventanas o RHONA figuran en el listado de establecimientos notificados.

### 4. SERNAGEOMIN — Observatorio Nacional de Relaves (desarrollo tecnológico, no norma)

- **Tipo de norma:** No aplica — desarrollo de plataforma/herramienta de monitoreo técnico, no es acto administrativo ni resolución
- **N° de norma:** No aplica
- **Ministerio/Servicio emisor:** SERNAGEOMIN (Ministerio de Minería), en conjunto con AMTC – Universidad de Chile, financiamiento Corfo
- **Fecha de publicación:** Cobertura de prensa entre el 3 y el 5 de agosto de 2026
- **Link:** https://chilepaisminero.com/sernageomin-desarrolla-un-observatorio-nacional-de-relaves/
- **Qué establece:** Avance del "Observatorio Nacional de Relaves / de Peligros Geológicos y Mineros", que integrará el Índice de Estabilidad Física (IEF) actualizado, datos en tiempo real e inteligencia artificial, para pasar de monitoreo reactivo a preventivo de depósitos de relaves activos. Entrada en operación proyectada para 2027. No impone obligación jurídica nueva ni modifica las obligaciones de reporte de incidentes ya vigentes en depósitos de relaves.
- **Alcance:** Depósitos de relaves activos a nivel nacional (proyecto en desarrollo, aún sin entrada en vigor).
- **Excepciones:** No aplica.
- **Vigencia:** No aplica — proyecto en desarrollo.
- **Obligación de reporte/plazo:** No aplica actualmente.
- **Clasificación:** De interés (seguimiento pasivo — relevante para clientes con depósitos de relaves, ej. rubro minero, ante un eventual cambio futuro de estándar de monitoreo).
- **Confianza: Media** — fechas consistentes entre 3 medios especializados (mineria-pa.com, construnoticias.com, chilepaisminero.com), pero sin confirmación directa en sernageomin.cl por la incidencia de acceso descrita arriba.

---

## Ronda transversal — resultado

Se ejecutaron 9 búsquedas ampliadas (episodios críticos/alertas ambientales en RM y Valparaíso, SEREMI de Medio Ambiente, Delegación Presidencial Regional, Gobierno Regional, normativa general de emisión/descontaminación) para el rango 4–7 de agosto de 2026. **No se encontró ningún hallazgo que superara el filtro de relevancia ambiental del punto 5.1 del ZP-027** dentro de la ventana temporal: no hubo declaración de Alerta Ambiental, Preemergencia ni Emergencia en la Región Metropolitana durante esos días (calidad del aire "Regular"), y los candidatos evaluados (plan de descontaminación de Valdivia, Ñuble, alerta sanitaria Quintero-Puchuncaví, etc.) quedaron descartados por estar fuera de ventana o por corresponder a fuentes fijas ya cubiertas.

**Recomendación para el Jefe de Gestión Ambiental:** el equipo de ronda transversal sugiere evaluar si conviene incorporar de forma **permanente** a la Tabla 1 de fuentes fijas —al menos durante la temporada otoño-invierno (mayo-agosto)— las declaraciones de episodios críticos (GEC) de la **Delegación Presidencial Regional** (RM y Valparaíso), dado su alto impacto operativo directo e inmediato sobre fuentes fijas de clientes industriales cuando sí se activan, y que hoy solo se capturarían vía ronda transversal (con posible rezago).

---

## Sin novedades hoy en:

- **Diario Oficial** — sin publicaciones ambientales nuevas confirmadas en el rango 4–7 de agosto de 2026, tras ~20 búsquedas cruzadas. (Una mención suelta y no verificable a una "Resolución Exenta N°4225/2026" fue descartada como hallazgo independiente por falta de fuente confiable; corresponde en realidad al hallazgo N°2 de esta tabla, ya verificado por la vía MMA/RETC.)
- **SMA — Sanciones y procedimientos sancionatorios** — sin resoluciones sancionatorias, formulaciones de cargos o inicios de procedimiento nuevos y verificables en el rango.
- **SNIFA — Instrucciones de carácter general y Programas de fiscalización** — sin hallazgos confirmados en el rango. Confianza de esta ausencia: **Baja** (no se pudo verificar por fetch directo debido a la incidencia técnica); se recomienda confirmación manual antes de cerrar el ítem.
- **DGA** — sin resoluciones de derechos de agua, extracción/vertimiento o planes de gestión de cuenca nuevos en el rango.
- **Contraloría General de la República** — sin dictámenes nuevos relevantes en materia ambiental, minera o hídrica en el rango (confianza Media, misma limitación de acceso directo).
- **Ronda transversal** — sin hallazgos que superaran el filtro de relevancia (ver sección dedicada arriba).

*(Fuentes semanales del SEA/MMA/consultas ciudadanas y fuentes mensuales de INN/ISO no se ejecutan hoy: el 7 de agosto de 2026 es viernes, no lunes ni primer día hábil del mes.)*

---

## Resumen de la semana (2026-W32, acumulado al 7 de agosto de 2026)

- **Total Aplicable:** 0
- **Total De interés:** 4 (de los cuales 1 marcado "ALTA PRIORIDAD DE VALIDACIÓN")
- **Pendientes de validación por el Jefe de Gestión Ambiental:** 4 de 4
- **Incidencias reportadas:** 1 (fallo técnico general de acceso directo — EGRESS_BLOCKED — en todas las fuentes; no bloqueo anti-bot específico)
- **Vencimientos activos a monitorear:** ventana de observaciones ciudadanas SMA cierra el 14-08-2026; ventana de rectificación RETC (RUEA/SINADER) corre del 18 al 29-08-2026

---

**Nota:** Hallazgos marcados como "De interés" con duda de aplicabilidad requieren validación del Jefe de Gestión Ambiental antes de comunicarse como aplicables a clientes.
