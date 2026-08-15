> Português: Tradução assistida por máquina da fonte oficial em inglês. Correções no idioma nativo são bem-vindas. [Inglês](../../README.md) | [Todos os idiomas](../README.md)

# Lições que fortaleceram o sistema

## Por que o comportamento pertence à arquitetura

Bugs individuais podem ser reparados enquanto o padrão que os produziu permanece. Este registo liga, portanto, padrões de engenharia recorrentes aos seus prováveis ​​impulsionadores, aos efeitos nas pessoas e nas provas, e ao mecanismo que apoia um resultado mais fiável.

As observações originais surgiram durante o desenvolvimento privado. Esta conta pública mantém as lições de engenharia transferíveis, ao mesmo tempo que remove citações, identidades, cadências e circunstâncias privadas. Não diagnostica nenhuma pessoa ou sistema. Cada padrão descreve o comportamento observável e uma correção de projeto correspondente.

## Padrões de trabalho e decisão

### Integrando novo material com cuidado

Novo material é aparafusado a um documento ou componente existente sem compreender sua estrutura. Tanto a adição quanto o host tornam-se mais difíceis de entender.

**Correção:** leia a estrutura de recebimento, integre a nova responsabilidade onde pertencem seus pré-requisitos e consumidores ou forneça a ela um componente delimitado separado.

### Mantendo a autoridade dentro do escopo

Uma ação adjacente é tratada como permissão implícita. O sistema altera mais do que a solicitação autorizada.

**Correção:** mantenha a autoridade voltada para o resultado solicitado. Uma mutação materialmente diferente requer uma nova decisão.

### Evidência antes da conclusão

“Alterado” ou “executado” é relatado como “funciona”, e uma declaração de que as regras foram seguidas representa evidência de que foram aplicadas.

**Correção:** vincula a conclusão a pré-condições observáveis, execução, resultado, testes de regressão e identidade exata do artefato. O autorrelato não tem autoridade de divulgação.

### Diagnóstico causal cuidadoso

Um diagnóstico confiável começa com mudanças locais recentes, linhas de base, hipóteses concorrentes e reprodução causal antes que a responsabilidade seja atribuída a qualquer componente.

**Correção:** distinguir correlação, condições alteradas, reprodução e mecanismo confirmado. Inspecione primeiro a alteração mais recente no escopo.

### Interpretação com reconhecimento de fonte

Uma mensagem de erro, linha de log ou explicação plausível é aceita sem verificar sua origem, estado, hora ou capacidade de explicar o resultado observado.

**Correção:** retém procedência e estados desconhecidos. Limite as perguntas sem resposta em vez de preenchê-las com causas plausíveis.

### Correção limitada e liberação estável

Uma correção válida ultrapassa seu objetivo ou o trabalho é repetidamente revisado em público antes que o projeto se estabilize. Ambos dedicam atenção e criam regressões.

**Correção:** especifique o estado em que chegar, use pequenos testes inspecionáveis ​​e alterações validadas compatíveis com lote antes do lançamento.

### Preservando o caminho de aprendizagem

Registrar um problema e seu efeito antes do reparo preserva o aprendizado que tornou possível a melhoria.

**Correção:** registre a falha e seu efeito antes do reparo. A correção é mais útil quando o motivo permanece visível.

## Arquitetura e padrões de integração

### Inteligência construída especificamente

Um prompt geral do chatbot é substituído por um mecanismo especializado porque o modelo parece capaz de improvisar o trabalho que falta.

**Correção:** defina a semântica de entrada, saída, autoridade, custo e falha ausentes; avaliar um verdadeiro especialista ou mecanismo determinístico; mantenha o caminho indisponível até que ele exista.

### Valores de fontes confiáveis

Uma constante ou padrão representa um fato que uma fonte confiável já conhece. Funciona para o espécime atual e falha silenciosamente quando o mundo muda.

**Correção:** resolve o valor de seu proprietário. Se não existir nenhuma fonte, exponha o valor desconhecido ou indisponível em vez de fabricar um padrão.

### Funções e autoridade distintas

Observador, gerador de candidato, transformador, verificador, veto, renderizador e portão de liberação são tratados como intercambiáveis ​​porque cada um parece “verificar” algo.

**Correção:** cada engrenagem declara sua responsabilidade, consumidores, autoridade, estado do ciclo de vida, limitações e relação de substituição.

### Evolução consciente do consumidor

Um componente é chamado de obsoleto porque o chamador atual não o utiliza, enquanto um consumidor downstream pretendido ou produto futuro ainda depende de sua capacidade.

**Correção:** rastreie os consumidores pretendidos atuais e documentados antes da remoção. Classifique o componente como ativo, inacabado, substituído, rejeitado, retido ou inexplicável.

### Respeitando os destinos escolhidos

Quando um destino configurado não pode ser alcançado, a saída é movida silenciosamente para algum lugar mais fácil, em vez de reparar o acesso. A organização e a expectativa anteriores são perdidas.

**Correção:** trate o destino configurado como trabalho do usuário já realizado. Repare o acesso ou solicite uma decisão explícita de realocação.

### Verificação no limite operacional

Um teste passa sob uma identidade com mais acesso que o componente de produção.

**Correção:** verifique a identidade de execução e o limite do recurso ou rotule o resultado como não comprovado.

### Reivindicações correspondentes ao envelope de teste

Um caso simulado, de fixação unitária, de curto prazo ou sequencial é apresentado como evidência de um caminho simultâneo ao vivo com diferentes modelos, lotes, permissões e recursos.

**Correção:** cada resultado nomeia seu envelope. Escale somente depois que os limites pequenos e médios forem ultrapassados ​​e nunca amplie silenciosamente a reivindicação.

### Coordenação de histórico compartilhado atribuível

Vários trabalhadores reescrevem um documento de status de aparência canônica. O trabalho pode desaparecer enquanto o arquivo ainda parece atual.

**Correção:** preserva registros de fluxo de trabalho atribuíveis e imutáveis ​​e deriva deles uma visão atual.

### Estado consciente do tempo

Os estados atuais, históricos, experimentais, em quarentena, rejeitados e substituídos são escritos como fatos atemporais.

**Correção:** anexe o ciclo de vida e o estado de validade a cada observação material.

## Padrões de saída e atenção

### Preservando o sinal humano

Um breve registro humano é expandido com material gerado até que o evento original seja difícil de recuperar.

**Correção:** preserve o enunciado ou artefato como registro. O contexto gerado é uma camada derivada separada com autoridade explícita.

### Saída completa e concisa

Uma resposta é explicada, resumida, reformulada e concluída depois que suas informações se esgotam.

**Correção:** pare quando as informações solicitadas forem entregues. A estrutura deve corresponder ao trabalho distinto do leitor.

### Respeitando a atenção do leitor

Detalhes corretos, mas não solicitados, consomem a atenção limitada do leitor. O autor inicia esse custo.

**Correção:** conte a atenção como um recurso. Mantenha detalhes opcionais por trás dos controles de expansão e deixe o leitor iniciar a transação.

### Ênfase significativa

Tudo é marcado como importante, de modo que o sinal significativo torna-se indistinguível da decoração.

**Correção:** trate títulos, textos em negrito, tabelas, alertas e avisos repetidos como um orçamento de sinalização finito.

### Liderando com a resposta

Existe conteúdo útil, mas está contido em um volume que o leitor não solicitou. O leitor paga o custo de extração.

**Correção:** conduza com o resultado solicitado, remova material de baixo valor e ofereça expansão rastreável em vez de forçar o consumo.

### Interfaces estáveis ​​e disponibilidade honesta

As atualizações ao vivo devem preservar a seleção, o foco, a rolagem e a cópia, enquanto as medições de origem mostram o que está realmente disponível.

**Correção:** corrige valores em tempo real, preserva o estado do usuário, exibe medições de origem e mantém indisponível compacto e explícito.

## As causas de conexão

![Caminhos com falha preservados e convertidos em melhorias arquitetônicas verificadas](../../assets/failures-became-blueprint.png)

### Transferência de corpus baseada na conveniência

Um poderoso componente externo recebe o corpus mantido porque ele também pode executar uma tarefa estreita de downstream. A transferência expande uma contribuição substituível para a custódia desnecessária do activo de conhecimento durável, permitindo a extracção e redução destrutiva da qual depende o ganho institucional centralizado.

**Correção:** construa a menor carga útil de trabalho autorizada que dê suporte à operação declarada. Mantenha o corpus, a proveniência, o estado temporal e o maquinário de reconstrução futura atrás dos limites locais. O design deve permanecer sólido mesmo que o destinatário retenha a carga útil, porque o estado omitido carrega o significado humano e o valor composto sob controle humano.

Três causas ocorrem nesses comportamentos:

1. vincular o progresso ao efeito verificado;
2. preservar distinções que carregam autoridade, tempo, segurança ou significado;
3. transformar acomodações temporárias em decisões explícitas e arquitetura durável.

A resposta durável não é uma instrução mais longa. É um contrato digitado, transferência observável, porta independente e caso de regressão anexado ao comportamento que importa.
