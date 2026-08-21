# Normativa Ambiental — Semana 2026-W34 (18-24 agosto 2026)

Archivo de esta semana: https://github.com/darioEVA/normativa-ambiental-zarey/blob/claude/awesome-franklin-mthc2o/normativa-ambiental-semana-2026-W34.md

> **Nota:** esta ejecución (viernes 21 de agosto de 2026) es la primera corrida registrada para esta semana ISO. Semana iniciada desde viernes 21 de agosto de 2026 — no cubre días previos de esta semana (lunes 17 a jueves 20 de agosto), salvo hallazgos puntuales del 18-19/08 detectados dentro de la ventana ampliada de 3 días y registrados a continuación.
>
> El link de archivo apunta a la rama de trabajo `claude/awesome-franklin-mthc2o` (no `main`), que es donde este repositorio recibe las actualizaciones de esta rutina hasta que se integre a la rama principal.

## ⚠️ Incidencia técnica general (afecta a toda la ejecución de hoy)

Durante esta ejecución, la herramienta de acceso directo a URL (WebFetch/`curl` vía proxy de egress) devolvió error de bloqueo (`EGRESS_BLOCKED` / 403 en el túnel del proxy) para **prácticamente todos los dominios probados**, incluyendo sitios de control neutros (google.com, wikipedia.org) y fuentes que normalmente no bloquean acceso directo (mma.gob.cl, contraloria.cl, sernageomin.cl, dga.mop.gob.cl, diariooficial.interior.gob.cl). Por tratarse de un bloqueo que afectó también a los sitios de control, se clasifica como **"fallo técnico temporal, no específico de la fuente"** (política de egress del entorno de ejecución), y no como el bloqueo anti-bot 403 específico que el procedimiento anticipa solo para SMA/SNIFA/RETC.

Toda la revisión de hoy se apoyó exclusivamente en búsqueda web (WebSearch), que sí funcionó con normalidad. Esto tiene dos consecuencias que deben tenerse presente:
- No fue posible leer el texto íntegro de ningún PDF/HTML fuente directamente; todo se basó en fragmentos indexados por buscadores.
- La confianza de varios hallazgos se limitó a "Media" en vez de "Alta" por esta razón, aun cuando la fuente de origen es oficial.

**Recomendación:** reintentar manualmente el acceso directo a estas fuentes (o repetir la ejecución) para elevar la confianza de los hallazgos marcados como Media, especialmente el Diario Oficial, donde no se pudo confirmar contenido alguno.

---

## Tabla resumen acumulada — Semana 2026-W34

| Mes | Día | Tipo de Norma | N° de Norma | Ministerio/Servicio | Link | Origen | Clasificación |
|---|---|---|---|---|---|---|---|
| Agosto | 18 | Comunicado/Proceso administrativo | Pendiente | MMA (RETC) | https://retc.mma.gob.cl/ministerio-del-medio-ambiente-inicia-proceso-de-rectificacion-de-informacion-ruea-sinader/ | Fuente fija | Aplicable |
| Agosto | 18 | Inicio proceso revisión de norma | Pendiente | MMA | https://mma.gob.cl/ministerio-del-medio-ambiente-inicia-revision-de-la-norma-de-calidad-del-aire-para-material-particulado-respirable-mp10/ | Fuente fija | De interés |
| Agosto | 18 | Comunicado institucional | No aplica | MMA | https://mma.gob.cl/chile-avanza-en-transparencia-del-sector-extractivo-y-abre-dialogo-sobre-desafios-socioambientales/ | Fuente fija | De interés |
| Agosto | 19 | Informe Final de Auditoría | 853/2025 | Contraloría General de la República | No verificado (bloqueo de acceso) | Fuente fija | De interés |
| Agosto | 19 | Posible episodio crítico (no confirmado) | Pendiente | Delegación Presidencial Regional (Los Lagos) — no confirmado | No verificado (bloqueo de acceso) | Ronda transversal | De interés — ALTA PRIORIDAD |
| Agosto | 20 | Resolución de reactivación operacional | Pendiente | SERNAGEOMIN | No verificado (bloqueo de acceso) | Fuente fija | De interés |
| Agosto | 21 | Instancia de participación ciudadana | Res. Ex. 4890/2025 (base) | MMA | https://mma.gob.cl/ministerio-del-medio-ambiente-abre-convocatoria-al-primer-grupo-ampliado-publico-privado-de-escazu/ | Fuente fija | De interés |

---

## Bloques detallados de hallazgos

### 1. Proceso de Rectificación de Información RUEA/SINADER
- **Tipo de norma:** Comunicado administrativo / apertura de proceso de rectificación de datos declarados.
- **N° de norma:** Pendiente de publicación oficial — solo comunicado institucional disponible a la fecha de esta revisión (no se identificó resolución exenta asociada tras búsqueda adicional).
- **Ministerio/Servicio emisor:** Ministerio del Medio Ambiente — Departamento de Información Ambiental (Ventanilla Única del RETC).
- **Fecha de publicación:** 18 de agosto de 2026 (un día antes del inicio estricto de la ventana de 3 días; se incluye porque el proceso está activo durante la ventana 19-21/08 y fue detectado recién en esta revisión).
- **Link:** https://retc.mma.gob.cl/ministerio-del-medio-ambiente-inicia-proceso-de-rectificacion-de-informacion-ruea-sinader/
- **Contenido:**
  - **Qué establece/obliga:** Abre un proceso para que los establecimientos **notificados individualmente** por el MMA rectifiquen, completen o corrijan información previamente declarada en el RUEA (Registro Único de Emisiones Atmosféricas, DS 138) y en SINADER (residuos no peligrosos), ambos dentro de la Ventanilla Única del RETC.
  - **Alcance:** Solo aplica a los establecimientos que reciban notificación individual del MMA — no es una obligación universal para todo declarante RETC.
  - **Excepciones:** Establecimientos no notificados quedan fuera del proceso.
  - **Vigencia:** No se pudo determinar el plazo de cierre del proceso con la información disponible.
  - **Obligación de reporte/plazo:** Sí — los establecimientos notificados deben rectificar dentro del plazo que fije el Ministerio (plazo específico no confirmado; pendiente de verificación manual).
- **Clasificación:** Aplicable (acotada al universo de establecimientos que reciban notificación individual).
- **Confianza:** Media — fuente oficial (MMA/RETC), pero sin poder confirmar plazo exacto ni encontrar cobertura de prensa independiente para verificación cruzada.
- **Acción sugerida:** Zarey debe verificar si alguno de sus clientes declarantes RETC recibió esta notificación individual.

### 2. Inicio de revisión de la Norma de Calidad del Aire para MP10
- **Tipo de norma:** Apertura formal de proceso de revisión de norma primaria de calidad ambiental.
- **N° de norma:** Pendiente de publicación oficial — solo comunicados institucionales/de prensa disponibles a la fecha de esta revisión.
- **Ministerio/Servicio emisor:** Ministerio del Medio Ambiente.
- **Fecha:** inicio del cómputo el 13 de agosto de 2026; comunicado difundido el 18 de agosto de 2026 (fuera de la ventana estricta, pero el proceso —incluida la consulta de antecedentes— permanece abierto durante la ventana 19-21/08 y más allá).
- **Link:** https://mma.gob.cl/ministerio-del-medio-ambiente-inicia-revision-de-la-norma-de-calidad-del-aire-para-material-particulado-respirable-mp10/
- **Contenido:**
  - **Qué establece:** Inicia el proceso de revisión del estándar de calidad del aire vigente para material particulado respirable (MP10), para evaluar si sigue protegiendo adecuadamente la salud a la luz de nueva evidencia científica. Aún no modifica el estándar vigente.
  - **Alcance:** Nacional. Especialmente relevante para instalaciones ubicadas en las 22 zonas declaradas latentes o saturadas por MP10, en 13 regiones del país (de Antofagasta a Aysén), 20 de ellas con Plan de Prevención/Descontaminación activo.
  - **Excepciones:** No aplica — no hay obligación nueva todavía, es etapa de recopilación de antecedentes.
  - **Vigencia:** El proceso de revisión tiene un plazo de 12 meses desde el 13/08/2026 para elaborar el anteproyecto de norma, con posibilidad de ampliación.
  - **Obligación de reporte/plazo:** Ventana de 45 días hábiles desde el 13/08/2026, **hasta el 19 de octubre de 2026**, para que cualquier persona natural o jurídica aporte antecedentes científicos, técnicos, económicos, jurídicos y/o sociales sobre el estándar.
- **Clasificación:** De interés (no genera obligación nueva aún, pero podría derivar en un estándar más exigente para fuentes de MP10 — relevante para fundiciones y plantas de proceso).
- **Confianza:** Alta en los hechos (confirmado por múltiples medios independientes: El Mostrador, Revista Electricidad, trendTIC, Induambiente, Radio Maray) — Media respecto del ajuste estricto a la ventana de fechas solicitada (evento del 13-18/08, no 19-21/08).
- **Nota de seguimiento:** existe un eco regional de este mismo proceso en la Región de Atacama (nota de SEREMI de Medio Ambiente, 18/08/2026) detectado en la ronda transversal; no se registra como hallazgo separado por ser el mismo proceso nacional, pero se recomienda que la revisión de mañana confirme si ya existe resolución formal publicada.

### 3. Chile ingresa al Estándar EITI (transparencia sector extractivo)
- **Tipo de norma:** Comunicado institucional / instancia de diálogo (no es acto normativo).
- **N° de norma:** No aplica.
- **Ministerio/Servicio emisor:** Ministerio del Medio Ambiente.
- **Fecha:** 18 de agosto de 2026 (fuera de la ventana estricta, incluido por relevancia directa para clientes mineros).
- **Link:** https://mma.gob.cl/chile-avanza-en-transparencia-del-sector-extractivo-y-abre-dialogo-sobre-desafios-socioambientales/
- **Contenido:**
  - **Qué establece:** Chile fue admitido como 55º miembro mundial (11º en Latinoamérica) del Estándar Internacional para la Transparencia de las Industrias Extractivas (EITI). El encuentro reunió a sociedad civil, sector público, privado y academia para definir la agenda de implementación.
  - **Alcance:** Sector extractivo, principalmente minería — divulgación de gobernanza: contratos, empresas estatales, distribución de ingresos, beneficiarios finales, impactos socioambientales.
  - **Excepciones:** No aplica.
  - **Vigencia:** Etapa de definición de agenda de implementación; sin fecha de entrada en vigor de obligaciones concretas todavía.
  - **Obligación de reporte/plazo:** Ninguna obligación de reporte formal por ahora.
- **Clasificación:** De interés (sin obligación nueva actual; relevante para clientes mineros por una eventual obligación futura de divulgación de gobernanza).
- **Confianza:** Media-Alta (confirmado también por Fundación Terram y Mch.cl, independientes del MMA).

### 4. Contraloría — Informe Final de Auditoría N° 853/2025 (Estero Llico – Lago Vichuquén – Laguna Torca)
- **Tipo de documento:** Informe Final de Auditoría de la División de Fiscalización de la Contraloría Regional del Maule. **Aclaración importante:** no es un Dictamen jurídico (jurisprudencia administrativa), sino un informe de la línea de auditoría/fiscalización de CGR — se reporta con esta salvedad porque el criterio original buscaba específicamente dictámenes.
- **N° de documento:** Informe Final N° 853, de 2025. **Discrepancia detectada y no resuelta:** el documento está etiquetado "de 2025", pero toda su cobertura y conocimiento público ocurrió el 19 de agosto de 2026; no se pudo determinar si la emisión formal fue en 2025 con difusión diferida, o si hay un error de numeración en la prensa.
- **Servicio emisor:** Contraloría General de la República, Contraloría Regional del Maule.
- **Fecha:** conocimiento público/cobertura de prensa el 19 de agosto de 2026 (dentro de la ventana).
- **Link:** no se pudo verificar una URL directa en contraloria.cl por la incidencia de acceso de hoy. Cobertura de prensa (sin URL confirmada): El Mostrador, Emol, La Tercera, Diario Talca, Diario El Centro, Publimicro — todas del 19/08/2026.
- **Contenido:**
  - **Qué establece:** CGR detectó débil coordinación interinstitucional e insuficiente gobernanza ambiental en la gestión del sistema Estero Llico – Lago Vichuquén – Laguna Torca (Región del Maule). Constató que los organismos con competencia en la materia carecen de mecanismos formales de seguimiento de medidas preventivas y correctivas, y que la Municipalidad de Vichuquén no cuenta con ordenanza específica de protección de humedales.
  - **Alcance:** Dirigido a organismos públicos (Municipalidad de Vichuquén, Gobierno Regional del Maule, SEREMI de Salud y, según algunas coberturas, la SMA); no crea obligación directa sobre privados. Relevancia indirecta para clientes: las causas de deterioro identificadas en estudios asociados apuntan a expansión forestal, contaminación agrícola y aguas servidas — no a actividad minera.
  - **Excepciones:** No aplica.
  - **Vigencia:** No especifica plazo de vigencia; es un informe de seguimiento/fiscalización.
  - **Obligación de reporte/plazo:** CGR instruyó a los organismos públicos acreditar medidas conjuntas frente al deterioro; no se encontró un plazo específico en días/meses en las fuentes disponibles.
- **Clasificación:** De interés (no genera obligación directa para clientes industriales/mineros; señal de mayor escrutinio de CGR sobre gobernanza de cuerpos de agua, lo que puede anticipar criterios más exigentes en fiscalizaciones futuras relacionadas con recursos hídricos).
- **Confianza:** Media — número y fecha de difusión corroborados de forma consistente por al menos cinco medios de prensa distintos (sin discrepancias entre ellos), pero sin acceso al documento primario en contraloria.cl por el bloqueo de acceso de hoy. **Requiere verificación manual del documento original antes de comunicarse a clientes.**

### 5. Posible episodio de calidad del aire en Osorno (NO CONFIRMADO — requiere verificación manual prioritaria)
- **Tipo de norma:** Posible episodio crítico ambiental (restricción de fuentes fijas/calefacción) — **no confirmado como acto administrativo formal**.
- **N° de norma:** Pendiente — no se encontró número de resolución. Búsqueda adicional específica ("resolución preemergencia Osorno agosto 2026") tampoco arrojó resultados.
- **Ministerio/Servicio emisor (no confirmado):** posiblemente Delegación Presidencial Regional/Provincial de Los Lagos, en el marco del Plan de Descontaminación Atmosférica de Osorno — sin confirmar.
- **Fecha:** dato de calidad del aire del 19 de agosto de 2026.
- **Link:** no verificado — proviene de menciones de prensa (Infobae, T13, La Tercera) sin URL específica confirmada; se descarta inventar un enlace.
- **Contenido:**
  - **Qué se detectó:** se registró en Osorno un índice de MP2.5 de 116 µg/m³ e ICAP 320 el 19 de agosto de 2026 — rango que en otras zonas del país corresponde a niveles de preemergencia. **No se encontró evidencia de la resolución formal** que declare preemergencia/emergencia ambiental para esa fecha específica; solo hay datos de calidad del aire, no el acto administrativo.
  - **Alcance (si se confirmara):** típicamente restricción de calefactores a leña y/o fuentes fijas en la comuna de Osorno.
  - **Excepciones:** desconocidas — no confirmado.
  - **Vigencia:** desconocida — no confirmado.
  - **Obligación de reporte/plazo:** no aplica hasta confirmar el acto.
- **Clasificación:** **De interés — ALTA PRIORIDAD DE VALIDACIÓN** (excepción del criterio conservador: un episodio crítico ambiental tiene impacto operativo directo e inmediato para instalaciones en la zona afectada, por lo que se prioriza aunque la confirmación sea incierta).
- **Confianza:** Baja — un solo dato de calidad del aire sin acto administrativo confirmado; **requiere verificación manual prioritaria** en airerm.mma.gob.cl / Delegación Presidencial de Los Lagos antes de comunicarse a cualquier cliente.
- **Nota relacionada (transparencia del proceso):** se investigó también una mención de "Alerta Sanitaria en Quintero-Puchuncaví desde el martes 21 de agosto", zona directamente relevante para clientes en el cordón industrial de Ventanas. Tras verificación cruzada se determinó que esa frase corresponde a una página histórica indexada sin año explícito, referida al **21 de agosto de 2018** (inicio de la crisis de intoxicaciones de Quintero-Puchuncaví de ese año), no a 2026. **Se descarta explícitamente**: no hay evidencia de una nueva alerta sanitaria en Quintero/Puchuncaví/Concón vigente en esta ventana. Se documenta para evitar que se reporte por error en revisiones futuras.

### 6. SERNAGEOMIN — Reactivación de Botaderos de Ripios VII, VIII y IX, proyecto Andacollo Oro
- **Tipo de norma:** Resolución de modificación/reactivación operacional de un permiso sectorial de Sernageomin (acto base: Resolución N° 1242/2015).
- **N° de norma:** Pendiente de publicación oficial — solo comunicado corporativo/de prensa disponible a la fecha de esta revisión (se hizo búsqueda adicional específica combinando "Andacollo Oro Sernageomin resolución agosto 2026" sin obtener el número de la enmienda 2026).
- **Ministerio/Servicio emisor:** SERNAGEOMIN (Servicio Nacional de Geología y Minería), Ministerio de Minería.
- **Fecha:** 20 de agosto de 2026.
- **Link:** no verificado con URL exacta — cobertura en portalminero.com, chilepaisminero.com, investingnews.com, pr-inside.com, The Globe and Mail y dipromin.com, todas replicando el mismo comunicado de la empresa Galantas Gold Corporation. Sin URL oficial de sernageomin.cl confirmada por la incidencia de acceso de hoy.
- **Contenido:**
  - **Qué establece:** Sernageomin aprobó la enmienda que permite reactivar la operación de los **Botaderos de Ripios VII, VIII y IX** (depósitos de residuos de lixiviación) del proyecto Andacollo Oro (ex Teck), operado por Galantas Gold Corporation, en la Región de Coquimbo.
  - **Alcance:** Autoriza continuar la operación de esos botaderos específicos bajo las mismas condiciones técnicas, operacionales, ambientales y de seguridad ya aprobadas en la RCA N° 151/2014 y la Resolución N° 1242/2015 — no es un proyecto nuevo, es reactivación de capacidad ya autorizada. Capacidad remanente autorizada: aprox. 16,4 millones de toneladas (~81% del total aprobado).
  - **Excepciones:** ninguna mencionada — se mantiene el marco de condiciones ya vigente.
  - **Vigencia:** hasta 4 años desde el inicio de la extracción, o hasta agotar la capacidad remanente autorizada, lo que ocurra primero.
  - **Obligación de reporte/plazo:** no se detalla un plazo nuevo distinto del régimen ordinario de fiscalización de Sernageomin sobre depósitos de relaves/ripios (DS 248).
- **Clasificación:** De interés (no genera obligación para clientes de Zarey directamente — es un permiso de un tercero en Coquimbo — pero es relevante como precedente de los criterios que usa Sernageomin para reactivar/enmendar depósitos de ripios/estériles, aplicable por analogía a instalaciones similares de clientes mineros).
- **Confianza:** Media — toda la cadena de verificación remite en última instancia al mismo comunicado corporativo de Galantas Gold; no se logró una fuente de prensa chilena totalmente independiente ni confirmación desde el sitio oficial de Sernageomin. **Requiere verificación manual prioritaria del número de resolución** cuando se restablezca el acceso a sernageomin.cl.

### 7. Primera sesión del Grupo Ampliado Público-Privado de Escazú
- **Tipo de norma:** Instancia de participación ciudadana (no es acto normativo nuevo).
- **N° de norma:** Resolución Exenta N° 4890/2025 del MMA (norma habilitante de la gobernanza del Acuerdo de Escazú en Chile; no es una norma nueva de 2026).
- **Ministerio/Servicio emisor:** Ministerio del Medio Ambiente — Consejo Nacional de Escazú.
- **Fecha del evento:** 21 de agosto de 2026, 11:00-12:35 hrs, modalidad virtual (Zoom) — dentro de la ventana de revisión.
- **Link:** https://mma.gob.cl/ministerio-del-medio-ambiente-abre-convocatoria-al-primer-grupo-ampliado-publico-privado-de-escazu/
- **Contenido:**
  - **Qué establece:** instancia anual de diálogo para informar avances del Plan Nacional de Implementación Participativa del Acuerdo de Escazú 2024-2030, y fortalecer participación, transparencia y monitoreo ciudadano en materia ambiental.
  - **Alcance:** general — acceso a información ambiental, participación y justicia ambiental; no un sector productivo específico.
  - **Excepciones:** no aplica obligación de cumplimiento.
  - **Vigencia:** instancia puntual (sesión única del 21/08); inscripción previa cerró el 17/08/2026.
  - **Obligación de reporte/plazo:** ninguna para empresas.
- **Clasificación:** De interés (bajo impacto operativo directo; relevante solo si algún cliente participa en procesos de evaluación ambiental donde aplique participación ciudadana/Escazú).
- **Confianza:** Media — solo confirmado por la fuente oficial MMA; sin cobertura de prensa independiente para verificación cruzada.

---

## Fuentes sin publicaciones nuevas relevantes en la ventana 19-21/08/2026

- **SMA (portal general, Sanciones, Procedimientos sancionatorios):** sin publicaciones nuevas. Se revisaron y descartaron por estar fuera de ventana: fiscalización a Minera El Toqui (rotura de tubería de relaves, incidente del 5/08), multa a Minera Centinela (resolución de enero 2026). El nombramiento del nuevo Superintendente del Medio Ambiente (19/08) es noticia institucional, no genera obligación ni sanción, no se registra como hallazgo.
- **SNIFA (Instrucciones generales, Programas de fiscalización):** sin publicaciones nuevas en la ventana.
- **DGA (resoluciones de derechos de agua/extracción, noticias):** sin publicaciones nuevas en la ventana. Actividad operativa sin acto normativo nuevo: catastro de canales afectados por mal tiempo (14/08) y reporte de estaciones de monitoreo (11/08), ambos fuera de ventana y de naturaleza informativa, no normativa.
- **RETC (dentro de la ventana estricta 19-21/08):** sin publicaciones nuevas estrictamente dentro de esos tres días; el hallazgo más cercano (RUEA/SINADER) es del 18/08 y se registró igualmente en la tabla por relevancia y vigencia activa.
- **Contraloría (dictámenes jurídicos propiamente tales):** sin dictámenes de jurisprudencia administrativa nuevos en materia ambiental/minera/hídrica en la ventana; el único documento relevante encontrado es el Informe Final de Auditoría 853/2025 (no es un dictamen, ver hallazgo 4).
- **Ronda transversal (SEREMI, Delegación Presidencial, Gobierno Regional):** no se identificó ningún acto administrativo nuevo con trazabilidad verificable dentro de la ventana estricta, más allá del episodio de Osorno no confirmado (hallazgo 5) y el eco regional del proceso MP10 en Atacama (mencionado como nota de seguimiento en el hallazgo 2).

## Diario Oficial — revisión incompleta por incidencia técnica (no se reporta como "sin novedades")

No fue posible confirmar el contenido de ninguna edición del Diario Oficial de la ventana 19-21/08/2026 (se confirmó la existencia de la edición N° 44.528 del 19/08/2026, pero no su contenido) debido al fallo técnico general de acceso descrito arriba. **Esto no debe interpretarse como ausencia de novedades** — el Diario Oficial requiere revisión manual o una nueva ejecución cuando se restablezca el acceso directo, dando prioridad al sumario completo de las ediciones del 19, 20 y 21 de agosto de 2026.

---

## Sugerencias de nuevas fuentes para la Tabla 1 (a evaluar por el Jefe de Gestión Ambiental)

Basado en lo detectado hoy en la ronda transversal:
1. **MINSAL / SEREMI de Salud regionales** — Alertas Sanitarias por episodios de contaminación (ej. Quintero-Puchuncaví-Concón): mecanismo recurrente en una zona directamente relevante para AA Chagres/Ventanas, con alto impacto operativo potencial (puede derivar en paralización de fuentes).
2. **airerm.mma.gob.cl / portales "Aire [Región]"** de Gestión de Episodios Críticos (GEC) — publican a diario las declaraciones de Alerta/Preemergencia/Emergencia Ambiental por región, con mayor precisión que la prensa. Habría evitado la incertidumbre del hallazgo 5 (Osorno).
3. **Consejos Consultivos Regionales del Medio Ambiente** — no generan normas pero anticipan agendas regulatorias regionales.
4. **GORE de regiones mineras** (Antofagasta, Atacama, Coquimbo) — instrumentos de ordenamiento territorial con componente ambiental que condicionan futuros proyectos industriales/mineros.

---

## Resumen de la semana (2026-W34, acumulado al 21 de agosto de 2026)

- **Total hallazgos registrados:** 7
- **Aplicable:** 1
- **De interés:** 5
- **De interés — ALTA PRIORIDAD DE VALIDACIÓN:** 1
- **Pendientes de validación por el Jefe de Gestión Ambiental:** 7 (todos — ver nota final)
- **Incidencias de acceso reportadas:** 1 incidencia general de fallo técnico (no específica de una fuente), que redujo la confianza de varios hallazgos a "Media" y dejó la revisión del Diario Oficial incompleta.

---

## Sin novedades hoy en:

SMA, SNIFA, DGA, RETC (dentro de la ventana estricta), Contraloría (dictámenes jurídicos propiamente tales), ronda transversal (fuera de los hallazgos 5 y de la nota de seguimiento MP10-Atacama).

**Nota:** Hallazgos marcados como "De interés" con duda de aplicabilidad requieren validación del Jefe de Gestión Ambiental antes de comunicarse como aplicables a clientes.
