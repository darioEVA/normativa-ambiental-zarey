# Revisión diaria de normativa ambiental — ZP-027
## Semana ISO 2026-W32 (lunes 3 de agosto – domingo 9 de agosto de 2026)

**Archivo de esta semana:** [https://github.com/darioeva/normativa-ambiental-zarey/blob/claude/awesome-franklin-kdn1cv/normativa-ambiental-semana-2026-W32.md](https://github.com/darioeva/normativa-ambiental-zarey/blob/claude/awesome-franklin-kdn1cv/normativa-ambiental-semana-2026-W32.md)

*Nota sobre el link: el repositorio configurado es `darioeva/normativa-ambiental-zarey`. Esta ejecución trabaja sobre la rama de desarrollo `claude/awesome-franklin-kdn1cv` (no se ha creado/mergeado un Pull Request), por lo que el link apunta a esa rama. Si el archivo se fusiona posteriormente a `main`, el link deberá actualizarse a `/blob/main/...`.*

Archivo creado hoy lunes 3 de agosto de 2026 (inicio de semana ISO 32). No se arrastran filas de la semana anterior (semana W31), conforme a la regla de reinicio de lunes.

---

## Incidencia técnica general (afecta a todas las fuentes de esta ejecución)

Durante toda la ejecución de hoy, el acceso HTTPS **directo** (fetch/WebFetch/curl) fue rechazado con **HTTP 403** en absolutamente todos los dominios probados — incluyendo `www.google.com` y `www.diariooficial.interior.gob.cl` (sitios que normalmente no presentan bloqueo anti-bot). Se confirmó mediante consulta al estado del proxy de salida (`$HTTPS_PROXY/__agentproxy/status`) que se trata de un **"policy denial" a nivel de gateway de red del entorno**, no de un bloqueo específico de ninguna fuente. Esto es distinto del bloqueo anti-bot ya conocido y esperado para SMA/SNIFA/RETC.

Conforme al punto 6 del procedimiento, esto se reporta como **"fallo técnico temporal, no específico de la fuente"** y **no se interpreta como ausencia de novedades**: toda la cobertura de esta ejecución se obtuvo exclusivamente vía búsqueda web (WebSearch), que funcionó con normalidad en todas las fuentes. Se recomienda que la próxima ejecución reintente el fetch directo para verificación textual completa de las fuentes oficiales (especialmente Diario Oficial, cuyo acceso directo normalmente sí funciona y permite revisar el sumario oficial día por día).

---

## Tabla resumen — Semana 2026-W32

| Mes | Día | Tipo de Norma | N° de Norma | Ministerio/Servicio | Link | Origen | Clasificación |
|---|---|---|---|---|---|---|---|
| Julio | 31 | Sentencia Tribunal Ambiental | Rol R-143-2025 (confirma Res. Ex. SMA N°17/2025) | SMA / 1er Tribunal Ambiental | [1ta.cl](https://www.1ta.cl/en-audiencia-empresa-recimat-reclamo-en-contra-de-resolucion-de-la-sma-que-rechazo-su-programa-de-cumplimiento/) | Fuente fija | Interés |
| Julio | 30 | Oficio judicial a la DGA | Pendiente de identificación (causa 1er T. Ambiental) | DGA Atacama / 1er T. Ambiental | No disponible esta semana — ver bloque de detalle | Fuente fija | Interés |
| Agosto | 2 | Declaración de episodio crítico (Preemergencia) | Sin número propio (marco: Res. Ex. N°8940/2026, PDA Coyhaique) | SEREMI Medio Ambiente Aysén | [Infobae](https://www.infobae.com/noticias/2026/08/02/estatus-de-la-calidad-del-aire-en-coyhaique-este-2-de-agosto-de-2026/) | Ronda transversal | Interés — ALTA PRIORIDAD |
| Agosto | 3 | Fiscalización/emergencia en curso | Res. Ex. SERNAGEOMIN N°063/2026 (antecedente) | SERNAGEOMIN / SENAPRED | No disponible esta semana — ver bloque de detalle | Fuente fija | Interés |
| Agosto | 3 | Proceso administrativo (rectificación RUEA/SINADER) | No aplica (comunicado) | MMA / RETC | [retc.mma.gob.cl](https://retc.mma.gob.cl/ministerio-del-medio-ambiente-inicia-proceso-de-rectificacion-de-informacion-ruea-sinader/) | Fuente fija | Interés |
| Agosto | 3 | Entrada en vigencia de Ley | Ley 21.100 | MMA | [mma.gob.cl](https://mma.gob.cl/desde-el-3-de-agosto-se-prohibe-la-entrega-de-bolsas-plasticas-en-el-pequeno-comercio/) | Fuente fija | Interés |
| Agosto | 3 | Consulta ciudadana (anteproyecto) | Res. Ex. N°03148/2026 | MMA | [consultasciudadanas.mma.gob.cl](https://consultasciudadanas.mma.gob.cl) | Fuente fija (semanal) | Interés |

---

## Bloques de detalle

### 1. SMA — Sentencia Tribunal Ambiental confirma rechazo del Programa de Cumplimiento de RECIMAT (Fuente fija)
- **Qué establece/obliga:** El Primer Tribunal Ambiental (Rol R-143-2025) rechazó en todas sus partes la reclamación de RECIMAT (Procesadora de Residuos Industriales Ltda., fábrica de ánodos de plomo, Calama) contra la Resolución Exenta N°17/2025 de la SMA, que había rechazado el sexto Programa de Cumplimiento (PdC) refundido presentado por la empresa. Con esto, **se reactiva el procedimiento sancionatorio original** (cargos formulados en 2020 por no contar con Entidad Técnica de Fiscalización Ambiental vigente para monitorear MP-10, plomo en aire y CO desde 2017), que ahora avanza a descargos y período probatorio.
- **Alcance:** Efectos particulares para RECIMAT (no identificada como cliente de Zarey). Se reporta por su valor de precedente: confirma el criterio estricto de la SMA y de los tribunales frente a Programas de Cumplimiento reiteradamente insuficientes — relevante para cualquier cliente con PdC en trámite.
- **Excepciones:** No aplica (acto de efectos particulares).
- **Vigencia:** El procedimiento sancionatorio de la SMA contra RECIMAT continúa su curso regular; no fija plazo para terceros.
- **Obligación de reporte/plazo:** Ninguna para terceros.
- **Confianza: Alta** — confirmado en el sitio oficial del Primer Tribunal Ambiental (1ta.cl) y coincidente con 3 medios de prensa (El America, Antofagasta Noticias, enlalinea.cl), sin discrepancias de fecha, rol ni contenido.

### 2. DGA/Tribunal Ambiental — Oficio exigiendo informe de riesgo hídrico a la DGA en proyecto "El Alto" (ex Pascua Lama, Barrick) (Fuente fija)
- **Qué establece/obliga:** El Primer Tribunal Ambiental (sede Antofagasta) ofició a la DGA Región de Atacama exigiendo que informe sobre el estado del sector, riesgos de desbordes/inundaciones y riesgos para la seguridad de trabajadores que realicen sondajes en los próximos meses, en el marco de la reclamación de la Comunidad Indígena Diaguita Alta Cordillera contra el rechazo del SEA a sus recursos administrativos sobre la RCA del proyecto de prospección minera "El Alto" (comuna de Alto del Carmen, Región de Atacama; ríos Tres Quebradas, El Toro, Potrerillos, Del Estrecho y Chollay). El contexto inmediato fue el rescate de 39 trabajadores de Barrick atrapados por nieve (hasta 7,5 m de acumulación, -15°C a -20°C) entre el 18 y 25 de julio de 2026.
- **Alcance:** Proyecto "El Alto" de Nevada Minera SpA (Barrick); no afecta otros proyectos directamente, pero sienta precedente de exigencia judicial de informes de riesgo hídrico/climático a la DGA para faenas de alta cordillera.
- **Excepciones:** No aplica.
- **Vigencia:** Requerimiento judicial en curso ante causa activa del Primer Tribunal Ambiental; no se identificó plazo exacto de respuesta de la DGA en las fuentes disponibles.
- **Obligación de reporte/plazo:** La DGA debe informar al Tribunal (plazo no precisado); no genera obligación directa para terceros.
- **Confianza: Media-Alta** — coincidente en 4 medios independientes (BioBioChile, Atacama Noticias, Diario El Día, Portal Minero/Dipromin/Terram) sobre fecha (30/07/2026), tribunal y contenido; no se pudo verificar el oficio original por bloqueo de fetch, ni se obtuvo URL exacta de artículo (solo dominios).

### 3. SEREMI Medio Ambiente Aysén — Preemergencia Ambiental en Coyhaique (Ronda transversal — EPISODIO CRÍTICO, alta prioridad)
- **Qué establece/restringe (concreto):** El 1 de agosto de 2026 se declaró **Alerta** (MP2,5: 80 µg/m³) y el 2 de agosto se agravó a **Preemergencia** en Coyhaique y su zona circundante, en el marco del Plan de Descontaminación Atmosférica (PDA) de Coyhaique (base normativa: Res. N°8940 Exenta, 2 de marzo de 2026, que aprobó el anteproyecto del PDA). La declaración de Preemergencia **prohíbe el uso de más de un calefactor a leña por vivienda** durante 24 horas y **prohíbe la emisión de humo visible** de artefactos a leña durante 24 horas. Se recomienda uso de mascarilla para adultos mayores, niños, embarazadas y enfermos crónicos, y evitar cocinar con leña o hacer fogatas.
- **Alcance:** Ciudad de Coyhaique y zona circundante (comuna de Coyhaique), Región de Aysén.
- **Excepciones:** Quedan exentos los artefactos que forman parte de programas de recambio validados por la SEREMI del Medio Ambiente, y aquellos certificados bajo el DS N°39/2011 (norma de emisión para calefactores a leña).
- **Vigencia:** Declaración de renovación diaria según pronóstico de MP2,5; al 2 de agosto de 2026 regía Preemergencia. Se levanta o cambia de categoría día a día mientras persistan las condiciones invernales adversas.
- **Obligación de reporte/plazo:** Fiscalización a cargo de SEREMI de Salud, municipalidad y Carabineros; no hay plazo de reporte para titulares, solo cumplimiento inmediato de la restricción.
- **Por qué Alta Prioridad:** Impacto operativo directo e inmediato (restricción de fuentes de calefacción) para cualquier persona/instalación ubicada en la zona afectada, conforme a la excepción 2b del procedimiento. Aún no se cuenta con la capa de ubicación por cliente, por lo que se marca para validación inmediata del Jefe de Gestión Ambiental (verificar si algún cliente de Zarey tiene personal, oficinas o instalaciones en Coyhaique/Aysén).
- **Confianza: Media-Alta** — dos lecturas diarias consecutivas coincidentes (Infobae/Aire Chile) más corroboración de Fundación Terram sobre refuerzo de fiscalización de calefactores en Coyhaique; no se pudo leer el bando oficial primario por bloqueo de fetch.

### 4. SERNAGEOMIN/SENAPRED — Emergencia en depósito de relaves espesados de ENAMI, Ovalle (Fuente fija)
- **Qué establece/restringe:** Tras precipitaciones superiores a 200 mm desde el 18 de julio de 2026, el agua sobrepasó el muro de contención del depósito de relaves espesados de ENAMI (Complejo Productivo Sur, ex Planta Delta, Ovalle) en 2 sectores, y la piscina de emergencia alcanzó su capacidad nominal. SERNAGEOMIN verificó agrietamiento y erosión en 3 puntos del muro (inspección del 21 de julio) y coordinó el envío de personal especializado y un dron de alta resolución para simular un eventual escenario de colapso. SENAPRED declaró un perímetro de seguridad y ordenó evacuación preventiva del sector colindante (Quebrada Alegre). ENAMI reforzó pretiles, ejecutó bombeo controlado y construyó piscinas temporales.
- **Alcance:** Depósito específico de ENAMI en Ovalle (capacidad autorizada 10 Mt; inventario ~9,13 Mt, 91% de capacidad). Es un antecedente directamente análogo para clientes con depósitos de relaves/estériles propios (ej. AA Chagres).
- **Excepciones:** No aplica.
- **Vigencia:** Situación de riesgo activa; SERNAGEOMIN anunció monitoreo reforzado (24/7) de depósitos de relaves a nivel nacional tras este episodio. Última cobertura confirmada al 28-29 de julio de 2026; no se confirmó comunicado nuevo específicamente dentro del 31 jul-3 ago, por lo que se reporta como situación en curso detectada esta semana.
- **Obligación de reporte/plazo:** No se identificó plazo de cierre de expediente; ENAMI está bajo seguimiento técnico continuo de SERNAGEOMIN.
- **Confianza: Media** — corroborado por 3 medios regionales/especializados (Reporte Minero, Diario El Día, El Ovallino) y por un número de resolución antecedente (Res. Ex. SERNAGEOMIN N°063/2026, que aprobó el estudio de peligro de ENAMI), pero sin verificación directa del texto oficial en sernageomin.cl (bloqueado) ni URLs exactas de artículo.

### 5. RETC/MMA — Proceso de rectificación de información RUEA y SINADER (Fuente fija)
- **Qué establece:** El MMA habilita una ventana para que los establecimientos **previamente seleccionados y notificados directamente** puedan corregir, completar o aclarar información ya declarada en el Registro Único de Emisiones Atmosféricas (RUEA) y en el Sistema Nacional de Declaración de Residuos (SINADER).
- **Alcance:** Solo establecimientos notificados por el MMA; no es una convocatoria abierta a todos los declarantes RETC.
- **Excepciones:** Los establecimientos no notificados no pueden usar esta ventana.
- **Vigencia:** Sistema habilitado del **18 al 29 de agosto de 2026** (con una semana adicional para casos pendientes).
- **Obligación de reporte/plazo:** Si un cliente fue notificado, debe rectificar su información RUEA/SINADER dentro de la ventana indicada.
- **Confianza: Media** — publicado en dos portales oficiales del propio MMA/RETC (coincidencia interna), sin cobertura de prensa independiente que confirme con certeza la fecha exacta de publicación dentro de la ventana de esta revisión. **Acción recomendada:** verificar si alguno de los clientes de Zarey (AA Chagres, Ventanas, RHONA) recibió notificación de rectificación.

### 6. MMA — Entrada en vigencia de la etapa definitiva de la Ley 21.100 ("Chao Bolsas Plásticas") para pequeño/mediano comercio (Fuente fija)
- **Qué establece/restringe (concreto):** Desde el 3 de agosto de 2026, **se prohíbe totalmente la entrega de bolsas plásticas** por parte de almacenes, negocios de barrio y en general micro/pequeñas/medianas empresas para transportar mercadería. Termina el régimen transitorio que permitía entregar hasta 2 bolsas plásticas por compra. Esta etapa culmina el proceso que ya regía para supermercados y grandes tiendas del retail desde 2019.
- **Alcance:** Todo el pequeño y mediano comercio a nivel nacional.
- **Excepciones:** No se reportaron excepciones adicionales específicas de esta etapa (persisten las excepciones generales de la ley, ej. bolsas para alimentos a granel/húmedos, no detalladas en las fuentes de esta ventana).
- **Vigencia:** Permanente desde el 3 de agosto de 2026.
- **Obligación de reporte/plazo:** Fiscalización a cargo de las municipalidades; multa de hasta 5 UTM por cada bolsa entregada indebidamente, aplicada al comercio infractor.
- **Clasificación — nota de validación:** Se clasifica como "De interés" bajo el criterio conservador, ya que los clientes identificados de Zarey (AA Chagres, Ventanas, RHONA) son de rubro industrial/minero, no comercio minorista. **Si algún cliente de Zarey opera puntos de venta o comercio minorista, esta norma pasa a ser "Aplicable" de forma directa** — requiere validación del Jefe de Gestión Ambiental.
- **Confianza: Alta** — confirmado en fuente oficial MMA y coincidente con múltiples medios serios (CNN Chile, País Circular, El Mostrador), sin discrepancias de fecha ni contenido.

### 7. MMA — Consulta ciudadana: Actualización de la Estrategia Climática de Largo Plazo (ECLP) (Fuente fija — revisión semanal)
- **Qué propone:** Anteproyecto de actualización de la Estrategia Climática de Largo Plazo de Chile, con lineamientos generales para enfrentar el cambio climático a 30 años (32 objetivos y 83 metas propuestas).
- **Alcance:** Instrumento de política pública nacional; no genera obligación de cumplimiento directa e inmediata, pero es relevante para clientes con exposición a regulación de cambio climático (reporte de GEI, riesgos climáticos).
- **Excepciones:** No aplica (instrumento de planificación, no regulación directa de emisiones).
- **Vigencia/plazo de comentarios:** Resolución Ex. N°03148/2026 (Diario Oficial, 25 de junio de 2026). **Consulta pública abierta desde el 25 de junio de 2026 — cierra el 22 de septiembre de 2026.** Nota de detección: el proceso se abrió en junio, pero se incluye recién en esta revisión por ser la primera semana de este archivo acumulado; sigue vigente y con plazo abierto para comentarios.
- **Obligación de reporte/plazo:** Quien desee comentar debe hacerlo antes del 22/09/2026 vía la plataforma consultasciudadanas.mma.gob.cl o presencialmente en las SEREMIs.
- **Confianza: Alta** — resolución numerada confirmada en mma.gob.cl y coincidente con Revista Electricidad, sin discrepancias.

---

## Notas adicionales de seguimiento (no requieren fila en la tabla — no son hallazgos nuevos de esta semana)

- **Alerta Sanitaria Concón/Quintero/Puchuncaví (relevante para clientes del cordón industrial, ej. Ventanas/Chagres):** se verificó específicamente por ser de alta relevancia para este tipo de cliente. El MINSAL decretó esta alerta el 9 de octubre de 2025, vigente hasta el **30 de enero de 2026**. Búsqueda de seguimiento realizada hoy no encontró evidencia de reactivación o renovación para julio/agosto de 2026. **Se considera cerrada/no vigente a la fecha de esta revisión**, sin nueva alerta activa detectada en la bahía de Quintero-Puchuncaví. Se recomienda mantener este ítem en el radar de búsquedas futuras dada la recurrencia histórica de episodios en esa zona.
- **SNIFA:** se detectó una mención de marcha blanca de una herramienta digital (SISAT) para reportes isocinéticos de material particulado en fundiciones de cobre (incluye Anglo American Chagres), pero no fue posible confirmar que su fecha de publicación caiga dentro de la ventana de esta semana. Confianza Baja — se recomienda validación manual y posible inclusión en el reporte de la próxima semana si se confirma la fecha.
- **Región Metropolitana:** sin alerta, preemergencia ni emergencia ambiental vigente en la ventana 31/07–03/08/2026 (calidad del aire "Regular"/"Buena" según MMA). Se descartan por desactualizados o de años anteriores varios titulares de prensa indexados sobre "emergencia ambiental" en Chillán/Temuco/Valdivia/Osorno y sobre alerta roja SENAPRED por temporal (esta última es de protección civil, no de naturaleza ambiental-regulatoria).
- **SEA:** las guías vigentes más recientes (modificación del Reglamento SEIA vía DS N°17/2025 y guía metodológica de GEI/forzantes climáticos de vida corta) datan de enero y marzo de 2026 respectivamente — no son novedad de esta semana. La Cuenta Pública Participativa del SEA (30/07/2026) fue revisada pero es institucional, no normativa.
- **Expedientes electrónicos de Normas de Emisión y Planes:** Norma de Emisión para Calderas, revisión del DS N°38/2020 (grupos electrógenos), PDA Valle Central de Ñuble y PDA Coyhaique tienen sus consultas públicas ya cerradas (entre febrero y mayo de 2026) y se encuentran en fase de análisis de observaciones — sin acción de comentario pendiente esta semana, solo seguimiento a la espera de sus decretos definitivos.
- **INN:** no se confirmaron Normas Chilenas (NCh) ambientales nuevas aprobadas específicamente en julio de 2026 (mes que corresponde revisar). La NCh-ISO 14001:2026 fue aprobada por el Consejo del INN en abril de 2026 (fuera del mes de revisión), por lo que no se reporta como hallazgo de este ciclo, solo como antecedente ya conocido.
- **ISO 14001/50001 (seguimiento de conocimiento, no normativa aplicable):** disponible nueva versión internacional ISO 14001:2026 (integra riesgos climáticos y enfoque de cadena de suministro); ISO 50001 permanece en su versión 2018, sin publicación confirmada de actualización.

---

## Gestión de vencimientos

No aplica en esta ejecución: es la primera del archivo semanal 2026-W32 (creado hoy, lunes), por lo que no hay Proyectos de Ley ni Consultas Ciudadanas previamente registrados en este archivo cuyo plazo deba revisarse por vencimiento.

---

## Sin novedades hoy en:
- Diario Oficial (sin publicaciones ambientales confirmadas en la ventana 31/07–03/08/2026; ver incidencia técnica general al inicio del reporte)
- SNIFA — Instrucciones de carácter general y Programas de fiscalización
- Contraloría General de la República — dictámenes ambientales, mineros o hídricos
- SEA — guías nuevas específicas de esta semana (las vigentes son de meses anteriores)
- MMA — área de interés Economía Circular (sin novedad puntual esta semana)
- Región Metropolitana — sin alerta/preemergencia/emergencia ambiental vigente
- INN — sin Normas Chilenas ambientales nuevas confirmadas para julio de 2026

**Nota:** Hallazgos marcados como "De interés" con duda de aplicabilidad requieren validación del Jefe de Gestión Ambiental antes de comunicarse como aplicables a clientes.

---

## Resumen de la semana (2026-W32, acumulado al 3 de agosto de 2026)

- **Total hallazgos Aplicable:** 0
- **Total hallazgos De interés:** 7 (de los cuales 1 marcado como ALTA PRIORIDAD DE VALIDACIÓN — Preemergencia Ambiental Coyhaique)
- **Pendientes de validación por el Jefe de Gestión Ambiental:** 7 de 7 (100%)
