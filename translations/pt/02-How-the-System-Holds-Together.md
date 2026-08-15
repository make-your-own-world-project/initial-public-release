> Português: Tradução assistida por máquina da fonte oficial em inglês. Correções no idioma nativo são bem-vindas. [Inglês](../../README.md) | [Todos os idiomas](../README.md)

# Como o sistema se mantém unido

![O registro preservado apoiando especialistas substituíveis e um plano de controle inspecionável](../../assets/core-architecture-layers.png)

## Separação de responsabilidades

A plataforma separa quatro preocupações que cooperam sem se transformarem:

1. **Preservação** retém evidências originais e procedência observada.
2. **Compreensão** adiciona objetos semânticos versionados, relacionamentos, estados temporais,
  e interpretações apoiadas.
3. **Recuperação e interação** reúne evidências específicas da solicitação para perguntas,
  exploração e conversação.
4. **Reconstrução de artefato** converte um mundo de evidências limitadas em um mundo declarado
  produto para um receptor declarado.

As instruções do produto não retrocedem na verdade do corpus. Um capítulo, público, gênero, movimento retórico ou orçamento de palavras pertencem a uma retirada. Não é um rótulo intrínseco em um artefato de origem.

## Topologia em camadas

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

## A adesão não finge saber

O registro de chegada pode indicar que bytes específicos chegaram ao sistema através de um canal específico. Ele não decide silenciosamente quem criou o artefato, quem aparece nele, quando seu assunto ocorreu, se o nome do arquivo é preciso, por que ele é importante ou quem é o proprietário de seu conteúdo. Essas são observações separadas com evidências e autoridade separadas.

A arquitetura distingue o artefato original das representações dele derivadas. Texto extraído, descrições, incorporações, classificações, resumos e relacionamentos podem ser regenerados ou substituídos. Eles não substituem a fonte.

## Caminhos interativos e de documentos

A resposta interativa e a geração de artefatos compartilham evidências, proveniência, relacionamentos digitados, incerteza e mecanismos de validação. Eles permanecem distintos do mesmo fluxo de trabalho.

Uma solicitação interativa pode precisar de uma conversa completa, um ciclo de vida de tarefa, uma passagem estreita de relacionamento ou um esclarecimento. Não é necessário construir um contêiner de livros e colapsar globalmente uma árvore histórica.

A geração de artefatos precisa de um produto declarado, receptor, orçamento e plano completo do artefato. Deve ver a estrutura provisória relevante antes da poda e deve dar conta do que foi deixado de fora.

## Arquitetura dinâmica em vez de uma cadeia fixa

A linha de montagem é compilada para o produto. Resultados diferentes podem usar especialistas diferentes, ordenar os mesmos especialistas de maneira diferente ou exigir múltiplas instâncias de um recurso. O gerente usa contratos de capacidade e evidências prévias, em vez de apenas nomes artísticos codificados.

Os invariantes universais permanecem estáveis ​​em todas as linhas: identidade da fonte, propriedade, estado epistêmico, incerteza, contabilização de perdas, transferências digitadas, observação de custos, verificação independente e reversão.

Um modelo geral externo pode ocupar uma estação digitada quando sua contribuição medida justifica o handoff. Ele recebe apenas a carga útil com escopo de solicitação exigida por aquela estação, não o corpus mantido ou a autoridade codificada pelo plano de controle mais amplo. Substituir ou remover essa estação deixa intactos o registro durável e a capacidade de reconstrução futura. A estação delimitada pode contribuir sem receber o conhecimento humano que, de outra forma, um sistema centralizado se transformaria em valor institucional.
