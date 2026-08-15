> Español: Traducción asistida por máquina de la fuente autorizada en inglés. Se aceptan correcciones en el idioma nativo. [Inglés](../../README.md) | [Todos los idiomas](../README.md)

# Cómo se mantiene unido el sistema

![El registro conservado apoya a especialistas reemplazables y un avión de control inspeccionable.](../../assets/core-architecture-layers.png)

## Separación de responsabilidades

La plataforma separa cuatro empresas que cooperan sin convertirse entre sí:

1. **Preservación** conserva la evidencia original y la procedencia observada.
2. **Comprensión** añade objetos semánticos versionados, relaciones, estados temporales,
  e interpretaciones apoyadas.
3. **Recuperación e interacción** reúne evidencia específica de la solicitud para preguntas,
  exploración y conversación.
4. **Reconstrucción de artefactos** convierte un mundo de evidencia limitada en un mundo declarado
  Producto para un receptor declarado.

Las instrucciones del producto no se filtran hacia atrás en la verdad del corpus. Un capítulo, audiencia, género, movimiento retórico o presupuesto de palabras pertenecen a un retiro. No es una etiqueta intrínseca de un artefacto fuente.

## topología en capas

```text
PRIMARY EVIDENCE
  immutable artifacts, interaction events, source identity, observed arrival
        |
        v
VERSIONED REPRESENTATIONS
  extracted text, media observations, chunks, entities, embeddings, locators
        |
        v
SEMANTIC AND TEMPORAL MAPS
  propositions, discourse links, argument edges, chronology, supersession,
  uncertainty, open attachment points, Personal Meaning Matrix contributions
        |
        +---------------------------+
        |                           |
        v                           v
INTERACTIVE CONTEXT             ARTIFACT CONTRACT
  request-scoped traversal        receiver, purpose, form, budget, evidence rules
        |                           |
        |                           v
        |                       REVERSE EXPANSION
        |                           |
        |                       WHOLE-TREE COLLAPSE
        |                           |
        |                       FORWARD RECONSTRUCTION
        |                           |
        +----------------------> HUMAN PROTOCOL + WEAVE
                                    |
                                INDEPENDENT GATES
                                    |
                              RECEIPT-GATED PRODUCT
```

## La adhesión no pretende saber

El registro de llegada puede indicar que bytes particulares llegaron al sistema a través de un canal particular. No decide silenciosamente quién creó el artefacto, quién aparece en él, cuándo ocurrió el tema, si el nombre de un archivo es exacto, por qué importa o quién es el propietario de su contenido. Esas son observaciones separadas con evidencia y autoridad separadas.

La arquitectura distingue el artefacto original de las representaciones derivadas de él. El texto, las descripciones, las incrustaciones, las clasificaciones, los resúmenes y las relaciones extraídos se pueden regenerar o reemplazar. No reemplazan la fuente.

## Rutas interactivas y de documentos.

Las respuestas interactivas y la generación de artefactos comparten evidencia, procedencia, relaciones escritas, incertidumbre y mecanismos de validación. Siguen siendo distintos del mismo flujo de trabajo.

Una solicitud interactiva puede necesitar una conversación completa, un ciclo de vida de la tarea, un recorrido estrecho de la relación o una aclaración. No es necesario construir un contenedor de libros y colapsar globalmente un árbol histórico.

La generación de artefactos necesita un producto declarado, un receptor, un presupuesto y un plan completo del artefacto. Debe ver la estructura provisional pertinente antes de la poda y debe dar cuenta de lo que quedó fuera.

## Arquitectura dinámica en lugar de una cadena fija

La línea de montaje se compila para el producto. Diferentes resultados pueden utilizar diferentes especialistas, ordenar a los mismos especialistas de manera diferente o requerir múltiples instancias de una capacidad. El gerente utiliza contratos de capacidad y evidencia previa en lugar de nombres artísticos codificados únicamente.

Las invariantes universales permanecen estables en todas las líneas: identidad de la fuente, propiedad, estado epistémico, incertidumbre, contabilidad de pérdidas, transferencias mecanografiadas, observación de costos, verificación independiente y reversión.

Un modelo general externo puede ocupar una estación tipificada cuando su contribución medida justifica el traspaso. Recibe solo la carga útil solicitada requerida por esa estación, no el corpus mantenido ni la autoridad codificada por el plano de control más amplio. Reemplazar o eliminar esa estación deja intactos el historial duradero y la capacidad de reconstrucción futura. La estación delimitada puede contribuir sin recibir el conocimiento humano que de otro modo un sistema centralizado convertiría en valor institucional.
