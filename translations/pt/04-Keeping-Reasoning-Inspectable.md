> Português: Tradução assistida por máquina da fonte oficial em inglês. Correções no idioma nativo são bem-vindas. [Inglês](../../README.md) | [Todos os idiomas](../README.md)

# Mantendo o raciocínio inspecionável

![Especialistas independentes traçando caminhos de raciocínio aceitos e rejeitados até evidências exatas](../../assets/reasoning-engine-inspectable-path.png)

## Raciocínio inspecionável

O mecanismo de raciocínio é uma sequência de especialistas limitados e projeções determinísticas. Seu objetivo é construir um gráfico de proposição e relação inspecionável a partir de evidências de fontes exatas. Não é um prompt genérico de conclusão solicitado para inferir todo o documento.

```text
EXACT EVIDENCE ITEMS AND SOURCE SPANS
        |
DISCOURSE AND REFERENCE PREPROCESSING
        |
PROPOSITION AND RELATION CANDIDATES
        |
ARGUMENT RELATION CLASSIFICATION
        |
TYPED PROVENANCE GRAPH
        |
DETERMINISTIC DEPENDENCY AND WHY PROJECTION
        |
PRODUCT-SPECIFIC SELECTION AND RECONSTRUCTION
        |
INDEPENDENT VERIFIER AND RECEIPT
```

## Pré-processamento linguístico

A evidência é dividida em fatias delimitadas e sem intervalos, vinculadas a identidades de origem imutáveis ​​e deslocamentos de caracteres. A análise de correferência propõe cadeias de referência. A análise da Teoria da Estrutura Retórica propõe estrutura do discurso e pares de operandos. Estruturas superdimensionadas ou não vinculadas permanecem explícitas, em vez de serem silenciosamente truncadas ou mapeadas para a primeira frase correspondente.

Essas ferramentas expõem a estrutura linguística. Eles não estabelecem motivos pessoais ou argumentos verdadeiros por si próprios.

## Classificação de relação de argumento

Os pares de proposições derivadas do discurso são classificados em um pequeno inventário de relações, incluindo apoio, conflito, equivalência ou nenhuma relação de autoridade. Cada tentativa retém seus operandos, distribuição de pontuação, identidade de modelo e disposição. Um resultado abaixo do limite permanece visível e não cria uma borda.

As relações aceitas tornam-se arestas de gráfico direcionadas com extensões de origem e identidade de método exatas. A ligação de origem ambígua falha ao fechar.

## Projeção gráfica

A visão da dependência e do “porquê” é uma projeção determinística de arestas já classificadas. Pode expor uma cadeia de apoio ou conflito de uma forma mais utilizável. Não pode inventar novas razões, riscos ou consequências e alegar que um especialista as derivou.

O gráfico pode ser exportado através de estruturas de intercâmbio de argumentos estabelecidas, mas uma representação de intercâmbio não é um segundo armazenamento de verdade e não requer um modelo ou acelerador.

## Limites de recursos

A co-referência e a análise de discurso podem usar a capacidade do acelerador alugado porque esses modelos são carregados para trabalhos de pré-processamento limitados. A classificação de argumentos é projetada para percorrer um caminho de inferência especializado e compacto. Projeção gráfica, seleção, resolução de restrições, verificações de procedência e verificação de recebimento são trabalhos comuns da CPU.

O projeto evita manter todos os modelos residentes e proíbe iniciar trabalhadores duplicados para escapar do mecanismo de arrendamento compartilhado.

## O que o verificador prova e não prova

O verificador pode provar que os componentes necessários foram executados, os intervalos exatos sobreviveram, a projeção do gráfico é reproduzível, as ligações do produto são consistentes e os bytes promovidos correspondem ao pacote aceito. Ele pode rejeitar manifestos fabricados, prosa sem suporte, direção errada, alternativas ocultas e recursos ausentes em sua política.

A correção estrutural não prova automaticamente que todos os rótulos de relação concordam com o julgamento humano especializado. A avaliação da qualidade da relação requer exemplos rotulados de forma independente e análise de precisão, recall, direção e calibração. Essa porta de qualidade semântica continua a ser uma responsabilidade distinta.

Esta fronteira também impede que um modelo externo a jusante se torne a autoridade de raciocínio. Pode receber proposições apoiadas e relações digitadas para uma tarefa de realização limitada, enquanto as evidências, tentativas, gráfico e critérios de aceitação permanecem disponíveis de forma independente. A Fluency não se apropria do raciocínio que tornou a carga útil.
