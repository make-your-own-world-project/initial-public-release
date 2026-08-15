> Español: Traducción asistida por máquina de la fuente autorizada en inglés. Se aceptan correcciones en el idioma nativo. [Inglés](../../README.md) | [Todos los idiomas](../README.md)

# ¿Qué se está ejecutando ahora?

![La maquinaria local organizada por responsabilidad en torno a una columna vertebral controlada y compartida.](../../assets/public-machinery-catalog.png)

## Cómo leer este catálogo

El catálogo es la contraparte pública de la vista del centro de datos en Mission Control. Describe lo que aporta cada engranaje y lo que se perdería si desapareciera, sin publicar direcciones privadas, diseño de la máquina, credenciales, rutas de archivos o cadencia operativa. El gráfico en vivo sigue siendo la fuente operativa de verdad.

El estado de los componentes importa. Una herramienta puede estar activa, retenida como sistema fuente, evaluada pero no adoptada, o un predecesor retirado. La presencia en este catálogo no otorga a un componente autoridad más allá de su función declarada.

Esa regla incluye la capacidad de la frontera externa. Cuando se utiliza, ocupa una estación delimitada y recibe una carga útil especialmente diseñada en lugar de acceso sin restricciones al corpus mantenido. La carga útil respalda la operación declarada pero omite el estado duradero necesario para reconstruir el sistema más amplio o producir de forma independiente retiros futuros. La estación recibe trabajo, no la custodia del historial humano del cual una institución centralizada podría extraer valor duradero.

## Caminos hacia y alrededor del sistema

### Cerebro Robot (LibreChat)


**Responsabilidad.** Proporciona la ventana de conversación reemplazable cara a cara. Lleva solicitudes y respuestas, mientras que la memoria duradera, la recuperación, el razonamiento y la verificación permanecen en los servicios que se encuentran debajo.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[LibreChat](https://github.com/danny-avila/LibreChat),[Nodo.js](https://github.com/nodejs/node)

### Divisor de conversación


**Responsabilidad.** Observa cuando un chat se convierte en dos temas y ofrece archivar el terminado por separado.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[API rápida](https://github.com/fastapi/fastapi)

### Control de misión


**Responsabilidad.** La ventana a la máquina: qué está funcionando, qué requiere atención y qué está haciendo en este momento. En este límite de publicación, su página de estado informa todos los sistemas monitoreados operativos en la instalación local.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** El estado operativo informa el estado del servicio; Los artefactos y recibos aceptados establecen los límites separados de ejecución y evidencia semántica.

**Principales herramientas públicas.**[API rápida](https://github.com/fastapi/fastapi),[Grafiz](https://gitlab.com/graphviz/graphviz),[psicópata](https://github.com/psycopg/psycopg)

### Enrutador semántico


**Responsabilidad.** Enrute las solicitudes limitadas al motor local apropiado y requiera autorización explícita antes de utilizar inferencias externas. La capacidad costosa se selecciona sólo cuando la solicitud justifica su costo medido.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[API rápida](https://github.com/fastapi/fastapi). Envoy y vLLM Semantic Router permanecen acreditados en el índice de origen como predecesores inspeccionados o retirados, no como dependencias de tiempo de ejecución actuales.

### Historiales completos de agentes


**Responsabilidad.** Conserve flujos de eventos de agentes completos y ordenados como evidencia de interacción, incluidos turnos humanos, turnos de asistente, herramientas, errores y correcciones. Las historias registran lo ocurrido; no convierten las declaraciones de los agentes en hechos verificados.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Suministra únicamente lo que establece su fuente y procedencia; la interpretación posterior permanece separada.

### Documentos del proyecto


**Responsabilidad.** Preservar el diseño privado, la evidencia y los registros del proyecto que explican por qué existe la plataforma y cómo cambió su arquitectura. Los productos públicos consumen derivados revisados ​​en lugar de exponer la ubicación del documento privado.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Suministra únicamente lo que establece su fuente y procedencia; la interpretación posterior permanece separada.

### Vikunja


**Responsabilidad.** Preservar el sistema de tareas externo como una fuente de propiedad independiente anterior a la plataforma. La integración puede leer evidencia de tareas autorizadas sin absorber el sistema de tareas en el corpus ni cambiar su ciclo de vida.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Suministra únicamente lo que establece su fuente y procedencia; la interpretación posterior permanece separada.

**Principales herramientas públicas.**[Vikunja](https://github.com/go-vikunja/vikunja)

## Preservación y recuperación

### Adquisición de conocimientos


**Responsabilidad.** La forma en que llegan las cosas. Suelta un documento, una exportación, un montón de notas y aterrizará en algún lugar donde se pueda encontrar, en lugar de en ninguna parte.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### MongoDB


**Responsabilidad.** Mantiene las conversaciones mismas, como se dijeron.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** La disponibilidad y la integridad son necesarias; Los datos almacenados no se interpretan ni se verifican a sí mismos.

**Principales herramientas públicas.**[MongoDB](https://github.com/mongodb/mongo)

### PostgreSQL


**Responsabilidad.** Mantener registros estructurados duraderos de proyectos, estados derivados e índices de búsqueda destinados a sobrevivir a los servicios de aplicaciones reemplazables. Los registros almacenados conservan una autoridad y procedencia distintas en lugar de convertirse en una memoria indiferenciada.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** La disponibilidad y la integridad son necesarias; Los datos almacenados no se interpretan ni se verifican a sí mismos.

**Principales herramientas públicas.**[PostgreSQL](https://github.com/postgres/postgres),[pgvector](https://github.com/pgvector/pgvector)

## Razonamiento y reconstrucción

### Clasificador de relaciones de argumentos

Clasificación de CPU AMF_ARI OpenVINO fijada de inferencia, conflicto, reformulación o sin relación

**Responsabilidad.** Clasificar la relación entre dos proposiciones suministradas; no crea ninguna proposición ni infiere un motivo personal. Ejemplo: distinguir una declaración que respalda a otra de otra que la contradice, o no devolver ninguna relación respaldada.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[Modelo AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Artefactos humanos


**Responsabilidad.** Definir los productos de cara humana que la línea de montaje puede construir. Cada producto tiene su propio receptor, propósito, estructura, política de evidencia y contrato de entrega en lugar de compartir un esquema genérico.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Puesta a Tierra + Validación de Entrega

puerta de recepción independiente sobre controles de fidelidad, procedencia, pérdida, invención, tejido y comprensión

**Responsabilidad.** Verifique de forma independiente que el artefacto conserve el significado respaldado y cumpla con el contrato de entrega declarado antes de su lanzamiento. Ejemplo: rechazar un párrafo legible que inventa una conclusión y rechazar por separado un documento fundamentado cuya estructura no sea utilizable para su lector objetivo.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Resolución de audiencia

Estado del receptor, requisitos previos, registro y relevancia.

**Responsabilidad.** Describe lo que se espera que el receptor previsto sepa, necesite y tolere manteniendo las suposiciones explícitas. Ejemplo: solicitar una guía para el propietario que explique el pH antes de utilizar abreviaturas familiares para un técnico de piscinas.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Colapso de todo el árbol + paquetes

partición, selección, ganancias y pérdidas restringidas por contenedores

**Responsabilidad.** Seleccione y equilibre lo que se ajuste al artefacto solicitado mientras registra lo que se omitió y preserva la forma significativa del árbol. Ejemplo: mantenga cada rama principal representada en un artículo de 1000 palabras en lugar de dejar que la rama fuente más grande consuma todo el presupuesto.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[submodlib](https://github.com/decile-team/submodlib),[arrodillado](https://github.com/arvkevi/kneed)

### Modelo de trabajo compacto

Portador portátil con alcance de solicitud para unidades, relaciones, trayectorias, bloques de origen, planos, identificadores y libros de transferencia seleccionados

**Responsabilidad.** Empaquete los hechos, relaciones, cronología, incertidumbre, fallas y identificadores de fuentes seleccionados en un contexto portátil específico del trabajo. Ejemplo: proporcione al editor la cadena de mantenimiento del grupo y por qué sus pasos se conectan sin cargar todo el corpus ni soltar los enlaces.

**Debe conservarse.** source_spans; relación_ids; cronología; incertidumbre; fracasos; sustitución; incógnitas

**Forma de recursos.** CPU y RAM proporcionales a la selección limitada; sin GPU ni arrendamiento

**Límite.** la calidad está limitada por la relación ascendente y la cobertura del estado de depósito

### Mecánica de entrega

controles de registro, modos, perfiles de tejido, ritmo, densidad y desarrollo

**Responsabilidad.** Proporcione restricciones de entrega medidas, como ritmo, densidad, registro y trayectoria de tejido, para este producto y audiencia. Ejemplo: dar una explicación infantil en paquetes más cortos y con un patrón de recurrencia diferente al de un informe técnico sin cambiar los hechos subyacentes.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Preprocesamiento del discurso

sectores acotados exactos, candidatos de referencia FastCoref y enlaces de operandos RST isanlp arrendados

**Responsabilidad.** Identifique los referentes candidatos y los tramos del discurso antes de razonar la clasificación y al mismo tiempo preservar las coordenadas exactas de la fuente. Ejemplo: vincular 'eso' al candidato bomba nombrado y exponer las dos cláusulas unidas por una relación de discurso causal.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[IsaNLP RST](https://github.com/tchewik/isanlp_rst),[FastCoref](https://github.com/shon-otmazgin/fastcoref)

### Reconstrucción avanzada de artefactos completos

Prerrequisitos, referentes, pegamento causal, progresión, introducción y conclusión.

**Responsabilidad.** Reconstruir el material seleccionado en el orden del lector, restaurando requisitos previos, referentes, vínculos causales, progresión y un final honesto. Ejemplo: presentar el objetivo antes del procedimiento y cerrar con una pregunta no resuelta cuando no existe ninguna conclusión.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Gráfico por qué y proyección de dependencia

Visión determinista de los bordes del gráfico clasificados que no pueden introducir nuevas afirmaciones de razonamiento.

**Responsabilidad.** Traducir los límites de relación aceptados en dependencias inspeccionables y vistas de por qué sin agregar interpretación. Ejemplo: demuestre que la conclusión B depende de la premisa A porque existe esa ventaja clasificada exacta.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[RedX](https://github.com/networkx/networkx)

### Respuesta interactiva fundamentada


**Responsabilidad.** Devuelve una respuesta conversacional con el razonamiento, la procedencia, la incertidumbre y las rutas de expansión relevantes. La ruta de respuesta puede atravesar conversaciones completas y ciclos de vida de evidencia sin pretender ser una ejecución de generación de documentos.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Puente de protocolo humano

codificación orientada al receptor de la carga útil fija soportada

**Responsabilidad.** Convertir una carga útil fija y compatible en una forma que la persona prevista pueda seguir, utilizando el contrato del producto y el patrón de entrega medido; no puede cambiar la evidencia. Ejemplo: convierta la misma cadena de razonamiento fundamentado en un correo electrónico conciso o en una guía por etapas cambiando la estructura de entrega, no las conclusiones.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Asamblea de contexto interactiva


**Responsabilidad.** Cree una evidencia limitada y un gráfico de razonamiento para la pregunta actual, preservando la cronología, las correcciones, las fallas, la identidad de la fuente y la autorización. Proporciona contexto a la respuesta sin aplanar el corpus en fragmentos de búsqueda.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Adhesión sin pérdidas


**Responsabilidad.** Admitir bytes originales y eventos nativos antes de la interpretación, registrando únicamente los hechos de llegada observados. Las descripciones, las marcas de tiempo inferidas del contenido, las identidades y las relaciones siguen siendo observaciones versionadas por separado.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Evidencia primaria


**Responsabilidad.** Mantener los depósitos autorizados a los que las representaciones y productos posteriores deben poder rastrearse. Su existencia tiene validez incluso cuando el sistema aún no puede explicar su significado o relación.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Árbol provisional completo

evidencia completa previa a la poda, dependencia, alternativa y estructura de fallas

**Responsabilidad.** Mantenga el árbol de candidatos completo con alcance de solicitud, incluidas alternativas, fallas, incógnitas y vistas reemplazadas, para que el colapso pueda ver lo que perdería. Ejemplo: retener tanto un tratamiento fallido como la corrección posterior antes de seleccionar material para una guía.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Gráfico de razonamiento

cronología, relaciones tipificadas, ciclos de vida de reclamos, fallas e incertidumbre

**Responsabilidad.** Mantener el mapa de proposiciones, cronología, intentos, resultados, conflictos, dependencias e incertidumbres del alcance de la solicitud. Ejemplo: conectar un tratamiento fallido con la corrección que lo reemplazó sin eliminar ninguno de los estados.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Solicitud + Contrato de artefacto

Propósito, receptor, contenedor, canal, presupuesto y veracidad.

**Responsabilidad.** Congele el propósito, el receptor, el producto, el canal, el presupuesto y el estándar de verdad para que todos los engranajes posteriores resuelvan el mismo trabajo. Ejemplo: distinguir una explicación de 500 palabras para un lector general de un informe de incidente técnico antes de que comience la selección de evidencia.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Expansión inversa

recolectar al revés sin podar; medir la contribución marginal

**Responsabilidad.** Vaya desde la solicitud o evidencia posterior hacia registros relacionados anteriores y recopile el recorrido completo del candidato antes de descartar nada. Ejemplo: siga una pregunta actual sobre algas a través de registros anteriores de pH, tamaño de piscina, mantenimiento y contexto de uso.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Movimientos retóricos escritos

trabajos semánticos y dependencias, nunca subcadenas de encabezado

**Responsabilidad.** Asigne a cada unidad seleccionada un trabajo comunicativo y una dependencia según el contrato del producto, no una palabra de título coincidente. Ejemplo: marque la evidencia como respaldo de un reclamo y un fracaso como preparación de la recuperación en lugar de llamar a ambos "antecedentes".

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Reconstrucción Semántica

entidades, proposiciones, episodios, intentos, resultados y preguntas

**Responsabilidad.** Convertir observaciones fuente en objetos semánticos atribuidos sin decidir su importancia o presentación final. Ejemplo: represente una solución propuesta, el intento, su error y la pregunta restante como registros vinculados separados.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Representaciones versionadas


**Responsabilidad.** transcripciones, estructura, texto, OCR, diseño y vistas derivadas

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Por qué importaba

Motivación atribuida, preocupación, consecuencia y relevancia actual.

**Responsabilidad.** Lleve evidencia directa y explícitamente atribuida sobre por qué se invirtió la atención, dejando desconocidas las razones sin fundamento. Ejemplo: preservar que una tarea de mantenimiento era importante porque protegía a las personas que usaban equipos compartidos cuando el registro así lo respalda, en lugar de adivinar ese motivo únicamente a partir de una pregunta técnica.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Razonamiento + motor de artefactos

reconstrucción controlada por recibos, colapso, protocolo humano y renderizado de Markdown atómico

**Responsabilidad.** Coordinar el recorrido delimitado de reconstrucción y renderizado y exponer el recibo de cada etapa; no reemplaza el juicio de los especialistas. Ejemplo: realizar una solicitud de redacción mediante selección, planificación, realización, validación y escritura atómica.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Gerente de ensamblaje + capacidad

recorre los campos obligatorios hacia atrás, fija el precio de los requisitos previos, selecciona especialistas veraces, ordena oleadas de dependencia y omite el trabajo de valor cero

**Responsabilidad.** Elija qué especialistas se necesitan, en qué orden se ejecutan y qué trabajo no agrega valor; no realiza sus trabajos. Ejemplo: programar la realización de la relación antes de la realización de la oración y omitir un pase estilístico no disponible que no aporta nada requerido.

**Debe preservar.** must_preserve_fields; linaje_campo; explícita_indisponibilidad

**Forma del recurso.** CPU; poca memoria; sin GPU ni arrendamiento

**Límite.** Las observaciones de costos y valores exponen decisiones pero nunca definen la importancia humana.

### Conciliador de presupuesto de transportista atómico

Mide los portadores indivisibles de origen, pegamento y relación antes de la realización y redistribuye el presupuesto fijo de todo el producto por holgura de sección genuina.

**Responsabilidad.** Compruebe si los hechos indivisibles y los portadores de relaciones pueden caber en cada sección, luego mueva solo la holgura disponible preservando el presupuesto total del documento. Ejemplo: ampliar una sección de procedimiento de 90 palabras que contiene una instrucción atómica requerida de 120 palabras tomando prestadas palabras no utilizadas de otra sección.

**Debe conservarse.** Whole_artifact_budget; trabajos_retóricos_requeridos; autoridad_fuente; forma_grafo

**Forma del recurso.** CPU; tiempo de ejecución casi nulo; evita el desperdicio de trabajo de GPU/modelo/verificador de etapa 8

**Límite.** no puede comprimir una proposición indivisible; falla si todos los transportistas requeridos exceden el presupuesto del producto declarado

### Administrador de vinculación vinculada al origen

mueve solo una rama aislada completa cuando el trabajo de su producto asignado es incompatible y un destino es demostrablemente compatible

**Responsabilidad.** Mover una rama de evidencia completa y aislada a la sección cuyo trabajo puede usarla legítimamente, rechazando movimientos ambiguos o relacionados. Ejemplo: reasigne una nota de recuperación independiente desde la configuración hasta la solución de problemas sin duplicarla en ambas secciones.

**Debe conservarse.** Branch_identity; intervalos_fuente; relación_ids; margen_ganancia_ledger

**Forma del recurso.** CPU; baja latencia; sin GPU ni arrendamiento

**Límite.** rechaza movimientos relacionados, ambiguos, parciales o con exceso de capacidad

### Realizador de relaciones en todo el documento

convierte los bordes de razonamiento aceptados de la misma sección y de la sección transversal en un lenguaje conectivo compacto y reproducible de forma independiente sin repetir ambos operandos

**Responsabilidad.** Convierta las relaciones gráficas aceptadas en un lenguaje conectivo corto mientras mantiene la dirección, los operandos y los intervalos de fuentes reproducibles de forma independiente. Ejemplo: realizar A-causas-B como un puente causal acotado en lugar de imprimir A y B como hechos adyacentes no relacionados.

**Debe conservarse.** relacion_direccion; operando_identidad; tramos_portador_exactos; intervalos_fuente; línea_sección

**Forma del recurso.** CPU; tiempo de ejecución casi nulo; sin GPU ni arrendamiento

**Boundary.** realiza sólo tipos de relaciones aceptadas explícitamente; los puentes compactos conservan la identidad del borde mecanografiado pero permanecen redactados mecánicamente; Los bordes del mismo portador, ambiguos, implícitos y desconocidos permanecen visibles en el gráfico, pero no se afirman como prosa.

### Motor de conocimiento


**Responsabilidad.** Coordinar la adhesión, las representaciones derivadas, la búsqueda, la procedencia y los trabajos duraderos sin fusionar esas responsabilidades en un solo estado de verdad. Expone las interfaces compatibles a los consumidores, mientras que la evidencia primaria sigue siendo abordable de forma independiente.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Microplanificador de cláusulas/oraciones escritas

Asigna portadores vinculados a la fuente a trabajos retóricos mecanografiados y compila planes de cláusulas, oraciones y párrafos.

**Responsabilidad.** Divida el significado y las relaciones aprobados en cláusulas, oraciones y párrafos conservando sus enlaces de origen; no inventa palabras ni afirmaciones. Ejemplo: planificar una cláusula de causa seguida de su consecuencia y transición para el realizador de la superficie.

**Debe conservarse.** semantic_unit_ids; relación_ids; formularios_fuente

**Forma del recurso.** CPU; baja latencia; sin GPU ni arrendamiento

**Límite.** no inventa una proposición faltante ni repara una relación no clasificada

**Principales herramientas públicas.**[espacio](https://github.com/explosion/spaCy),[BlingFuego](https://github.com/microsoft/BlingFire)

### Gerente de Contratos de Producto

convierte género, receptor, propósito, canal, veracidad, atención y presupuesto en campos de producto requeridos y trabajo retórico.

**Responsabilidad.** Convierta la solicitud en una lista de verificación concreta para el producto terminado sin elegir evidencia ni escribirla. Ejemplo: para un manual de usuario, solicite requisitos previos, acciones ordenadas, orientación de recuperación y un cierre antes de que se inicie cualquier editor.

**Debe conservarse.** declarado_propósito; receptor; veracidad; canal

**Forma del recurso.** CPU; tiempo de ejecución casi nulo; sin GPU ni arrendamiento

**Límite.** no infiere el significado de la fuente ni elige hechos

### Realizador de superficies de contrato

aplica gramática limitada, morfología, tipografía, perspectiva y transformaciones tipográficas a las unidades de entrega

**Responsabilidad.** Aplicar gramática, morfología, tipografía y perspectiva permitida a un plan ya aprobado; no puede decidir un nuevo significado. Ejemplo: convertir un plan imperativo escrito en una instrucción gramatical sin agregar un reclamo de seguridad que nunca se proporcionó.

**Debe conservarse.** Claim_authority; enlaces_fuente_y_relación; trabajo_retórico

**Forma del recurso.** CPU; El editor candidato opcional puede utilizar una concesión de GPU existente, pero no tiene autoridad.

**Límite.** La gramática cerrada es fiel pero puede permanecer estilísticamente rígida.

**Principales herramientas públicas.**[espacio](https://github.com/explosion/spaCy)

## Gestión, verificación y operaciones.

### Amf Ari


**Responsabilidad.** Ejecute el clasificador de relación argumento-fijado sobre los pares de proposiciones proporcionados y devuelva intentos de apoyo, conflicto, reformulación o sin relación puntuados. No crea proposiciones, no infiere motivos ni certifica sus propias etiquetas.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[AbiertoVINO](https://github.com/openvinotoolkit/openvino),[Modelo AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Indexador de chat


**Responsabilidad.** Mantiene las conversaciones en el registro largo en lugar de dejarlas en la ventana de chat.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Indexador de archivos


**Responsabilidad.** Descubra archivos elegibles y envíe trabajos de indexación delimitados que preserven su procedencia. No debe tratar las fechas del sistema de archivos, los nombres de los archivos o el texto extraído como hora, identidad o motivo de creación autorizados.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Telemetría de hardware


**Responsabilidad.** Registre el historial limitado del estado de la máquina para que las fallas se puedan comparar con la energía, la temperatura, la memoria y el estado del acelerador. La descripción pública omite la cadencia de muestreo privada y el diseño de la máquina.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[psutil](https://github.com/giampaolo/psutil)

### Imagen


**Responsabilidad.** Produzca imágenes localmente para que un concepto visual no tenga que cruzar un límite de inferencia externo. La generación de imágenes permanece separada de la autoridad de evidencia y el permiso de publicación.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[difusión-estable.cpp](https://github.com/leejet/stable-diffusion.cpp),[Z-Imagen-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo),[Referencia de empaquetado de Z-Image-Turbo-Windows](https://github.com/airesearch-official/Z-Image-Turbo-Windows)

### Ollama


**Responsabilidad.** La mente pesada. Más lento y más grande, reservado para preguntas que realmente necesitan más pensamiento que velocidad.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[Ollama](https://github.com/ollama/ollama),[Qwen3](https://github.com/QwenLM/Qwen3)

### Ollama Insertar


**Responsabilidad.** Hace que la escritura se pueda buscar por significado en lugar de por palabras exactas.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[Ollama](https://github.com/ollama/ollama),[Texto incrustado nómico](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)

### Arrendamiento de energía


**Responsabilidad.** Permite que la máquina esté inactiva en silencio y se active por completo para trabajar de verdad.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Cambiar título de conversación


**Responsabilidad.** Proporciona nombres de conversaciones que significan algo, de modo que se pueda encontrar la lista en lugar de un muro de primeras oraciones.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Observador semántico


**Responsabilidad.** Comprueba si una respuesta está respaldada por el material del que dice provenir.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[Transformadores](https://github.com/huggingface/transformers),[minicheque](https://github.com/Liyan06/MiniCheck),[HechoCG](https://github.com/derenlei/FactCG)

### Análisis de pendiente


**Responsabilidad.** Mantiene un registro de cómo falla cada mente y si eso está mejorando o empeorando.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[espacio](https://github.com/explosion/spaCy),[BlingFuego](https://github.com/microsoft/BlingFire),[NLTK](https://github.com/nltk/nltk)

### discursos


**Responsabilidad.** Convierte el habla en texto, por lo que hablar es una forma de escribir las cosas.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[discursos](https://github.com/speaches-ai/speaches),[susurro más rápido](https://github.com/SYSTRAN/faster-whisper),[destilado-más rápido-susurro-grande-v3](https://huggingface.co/Systran/faster-distil-whisper-large-v3)

### Servicio de tareas


**Responsabilidad.** Lea los registros de tareas autorizadas como evidencia sobre el trabajo planificado sin convertirlos en recordatorios, motivos inferidos o verdad del corpus.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### vllm


**Responsabilidad.** La mente cotidiana. Rápido, siempre cargado, responde casi todo.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

**Principales herramientas públicas.**[vllm](https://github.com/vllm-project/vllm),[Qwen3](https://github.com/QwenLM/Qwen3)

### Trabajos escénicos duraderos

lotes acotados, puntos de control, cancelación, reanudación y fracaso parcial

**Responsabilidad.** Ejecute etapas de artefactos largas como trabajos delimitados reanudables con estados de terminal veraces en lugar de vincularlos a una solicitud del navegador. Ejemplo: reanudar después de un punto de control de promoción verificado en lugar de repetir un costoso pase de razonamiento después de una interrupción.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Ejecución + Administrador de manifiestos

ejecuta el adaptador asignado y registra el método físico, el punto final, la revisión del modelo, los hashes, los límites de llamada, el tiempo, los reintentos y la disposición.

**Responsabilidad.** Ejecute a cada especialista asignado y registre lo que se ejecutó físicamente, con sus entradas, identidad, tiempo, reintentos y resultado. Ejemplo: muestre que el clasificador AMF anclado manejó la Etapa 2 en lugar de confiar en una etiqueta de manifiesto que simplemente dice que así fue.

**Debe conservarse.** input_hashes; identidad_adaptador; estado_fallo

**Forma de recursos.** Coordinador de CPU; Los delegados de GPU funcionan solo a través de propietarios de arrendamiento declarados.

**Límite.** registra la ejecución; no puede certificar su propio éxito

### Arbitraje de arrendamiento de GPU


**Responsabilidad.** Coordine transferencias de asesoramiento entre cargas de trabajo de aceleradores administradas por plataforma sin exponer la identidad del dispositivo físico ni adelantarse al trabajo que ya está en marcha.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Coordinador de Residencia de Energía

**Responsabilidad.** Mantenga un modelo de estado ACTIVO, CALIENTE, INACTIVO y NUNCA en todos los mecanismos de residencia y energía de la plataforma distribuida.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

### Libro mayor de carga útil esperada/observada

une la responsabilidad de cada engranaje a sus campos observados, preparación, omisiones, valor, costo, tiempo, reintentos y solicitud de reparación.

**Responsabilidad.** Compare lo que se esperaba que contribuyera cada engranaje con lo que realmente entregó, incluidos los costos y los insumos faltantes. Ejemplo: exponer que el análisis de relaciones se ejecutó durante 40 segundos pero no proporcionó ningún borde conectivo utilizable al editor.

**Debe conservarse.** handoff_identity; digiere; campos_faltantes; base_costo

**Forma del recurso.** CPU; casi cero en relación con el razonamiento y la verificación

**Límite.** La sincronización de la sección portátil no reemplaza la sincronización de la etapa física/modelo en el manifiesto de ejecución.

### Gerente de calidad consciente del producto

comprueba la finalización retórica, el razonamiento conectivo, la legibilidad, la tipografía, la duplicación, la atención, el presupuesto, el tejido, la pendiente y las acciones ejecutables del producto solicitado.

**Responsabilidad.** Evalúe si este producto específico funciona para el lector y propósito declarados en ejes de calidad separados, luego identifique la etapa de reparación responsable. Ejemplo: un manual puede fallar al faltar una guía de recuperación incluso cuando cada oración es gramatical y fundamentada.

**Debe conservarse.** individual_axis_results; evidencia_candidato_rechazado

**Forma del recurso.** CPU más verificador/deslop limitado HTTP; históricamente la mayor participación en la Etapa 8

**Límite.** los ejes de género deben ser medidos y versionados; una puntuación de calidad opaca está prohibida

### Responsable de Recibo + Promoción

Vuelve a calcular invariantes de forma independiente y permite la promoción y la escritura de artefactos atómicos solo desde un recibo PASS.

**Responsabilidad.** Verifique de forma independiente el paquete y escriba el artefacto solo después de que pase cada invariante requerido. Ejemplo: rechazar la promoción cuando el renderizador informa que fue exitoso pero su recibo no puede reproducir un enlace de origen.

**Debe conservarse.** Failure_results; incógnitas; identidad_liberación; rollback_boundary

**Forma de recursos.** CPU y E/S; sin GPU ni arrendamiento

**Límite.** La autenticidad del manifiesto depende en última instancia del enlace de configuración/versión inmutable revisado

### Procedencia + Control de pérdidas

Identidad de origen, estado epistémico, inferencia, invención y ramas rechazadas.

**Responsabilidad.** Mantenga cada declaración vinculada a quién o qué la proporcionó, cuándo se aplicó y si fue observada, inferida, reemplazada, rechazada o desconocida. Ejemplo: preservar una reinterpretación posterior sin sobrescribir la creencia anterior que realmente guió una acción.

**Debe conservarse.** Identidad gráfica exacta, procedencia de la relación y límite del componente declarado.

**Forma de los recursos.** La implementación en vivo registra el uso real de CPU, memoria, almacenamiento, acelerador y arrendamiento; Este catálogo público no expone la ubicación de la máquina.

**Límite.** Puede realizar únicamente su responsabilidad gráfica declarada y no puede reparar evidencia ascendente faltante o no respaldada.

## Componentes adicionales declarados

### Puerta de enlace web segura

Proporciona acceso remoto autenticado desde clientes aprobados sin exponer directamente los servicios de plataformas privadas a la Internet pública.

### supervisor de plataforma

Inicia los servicios en orden de dependencia, observa su estado y realiza acciones de reinicio limitadas. Su fracaso elimina la supervisión coordinada sin redefinir el estado de los servicios que siguen funcionando.

## Límite de integridad

El catálogo cubre componentes lógicos activos en el gráfico de arquitectura mantenida, no todos los paquetes transitivos instalados en cada tiempo de ejecución. Una futura versión de software requiere una lista exacta de materiales y un paquete de licencias generados a partir de los bytes específicos que se distribuyen.
