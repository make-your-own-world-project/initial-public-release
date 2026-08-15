> Português: Tradução assistida por máquina da fonte oficial em inglês. Correções no idioma nativo são bem-vindas. [Inglês](../../README.md) | [Todos os idiomas](../README.md)

# O que está funcionando agora

![A maquinaria local organizada por responsabilidade em torno de uma espinha dorsal controlada e compartilhada](../../assets/public-machinery-catalog.png)

## Como ler este catálogo

O catálogo é a contrapartida pública da visualização Datacenter no Mission Control. Ele descreve a contribuição de cada engrenagem e o que seria perdido se desaparecesse, sem publicar endereços privados, layout da máquina, credenciais, caminhos de arquivos ou cadência operacional. O gráfico ao vivo continua sendo a fonte operacional da verdade.

O status do componente é importante. Uma ferramenta pode estar ativa, mantida como sistema de origem, avaliada, mas não adotada, ou ser um antecessor retirado. A presença neste catálogo não concede autoridade a um componente além de sua função declarada.

Essa regra inclui capacidade de fronteira externa. Quando usado, ele ocupa uma estação delimitada e recebe uma carga útil específica, em vez de acesso irrestrito ao corpus mantido. A carga suporta a operação declarada, mas omite o estado durável necessário para reconstruir o sistema mais amplo ou produzir retiradas futuras de forma independente. A estação recebe trabalho, não a custódia do registo humano do qual uma instituição centralizada poderia extrair valor durável.

## Caminhos para dentro e ao redor do sistema

### Cérebro Robô (LibreChat)


**Responsabilidade.** Forneça uma janela de conversa humana substituível. Ele carrega solicitações e respostas enquanto memória durável, recuperação, raciocínio e verificação permanecem nos serviços abaixo dele.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[Chat Livre](https://github.com/danny-avila/LibreChat),[Node.js](https://github.com/nodejs/node)

### Divisor de conversa


**Responsabilidade.** Avisa quando um chat se transforma em dois assuntos e se oferece para arquivar o assunto finalizado separadamente.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[API rápida](https://github.com/fastapi/fastapi)

### Controle da Missão


**Responsabilidade.** A janela para a máquina: o que está em execução, o que requer atenção e o que ela está fazendo no momento. Neste limite de publicação, sua página de status relata todos os sistemas monitorados operacionais na instalação local.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** O status operacional informa o estado do serviço; artefatos e recibos aceitos estabelecem os limites separados de execução e evidência semântica.

**Principais ferramentas públicas.**[API rápida](https://github.com/fastapi/fastapi),[Gráficoviz](https://gitlab.com/graphviz/graphviz),[Psicopg](https://github.com/psycopg/psycopg)

### Roteador Semântico


**Responsabilidade.** Encaminhe solicitações limitadas para o mecanismo local apropriado e exija autorização explícita antes de usar inferência externa. A capacidade cara é selecionada somente quando a solicitação justifica seu custo medido.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[API rápida](https://github.com/fastapi/fastapi). O Envoy e o vLLM Semantic Router permanecem creditados no índice de origem como predecessores inspecionados ou retirados, e não como dependências de tempo de execução atuais.

### Históricos completos de agentes


**Responsabilidade.** Preservar fluxos de eventos completos e ordenados do agente como evidência de interação, incluindo turnos humanos, turnos de assistentes, ferramentas, erros e correções. As histórias registram o que ocorreu; eles não transformam as declarações dos agentes em fatos verificados.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Fornece apenas o que sua fonte e procedência estabelecem; a interpretação a jusante permanece separada.

### Documentos do Projeto


**Responsabilidade.** Preservar o design privado, as evidências e os registros do projeto que explicam por que a plataforma existe e como sua arquitetura mudou. Os produtos públicos consomem derivativos revisados ​​em vez de expor a localização do documento privado.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Fornece apenas o que sua fonte e procedência estabelecem; a interpretação a jusante permanece separada.

### Vikunja


**Responsabilidade.** Preservar o sistema de tarefas externo como uma fonte de propriedade independente anterior à plataforma. A integração pode ler evidências de tarefas autorizadas sem absorver o sistema de tarefas no corpus ou alterar seu ciclo de vida.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Fornece apenas o que sua fonte e procedência estabelecem; a interpretação a jusante permanece separada.

**Principais ferramentas públicas.**[Vikunja](https://github.com/go-vikunja/vikunja)

## Preservação e recuperação

### Ingestão de Conhecimento


**Responsabilidade.** A forma como as coisas entram. Deixe cair um documento, uma exportação, uma pilha de notas e ele vai parar em algum lugar onde possa ser encontrado, em vez de em lugar nenhum.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### MongoDB


**Responsabilidade.** Conduz as próprias conversas, conforme foram ditas.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Disponibilidade e integridade são necessárias; os dados armazenados não se interpretam nem se verificam.

**Principais ferramentas públicas.**[MongoDB](https://github.com/mongodb/mongo)

### PostgreSQL


**Responsabilidade.** Mantenha registros de projetos estruturados e duráveis, estados derivados e índices de pesquisa destinados a sobreviver a serviços de aplicativos substituíveis. Os registros armazenados retêm autoridade e procedência distintas, em vez de se tornarem uma memória indiferenciada.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Disponibilidade e integridade são necessárias; os dados armazenados não se interpretam nem se verificam.

**Principais ferramentas públicas.**[PostgreSQL](https://github.com/postgres/postgres),[vetor pg](https://github.com/pgvector/pgvector)

## Raciocínio e reconstrução

### Classificador de relação de argumento

classificação de CPU AMF_ARI OpenVINO fixada de inferência, conflito, reformulação ou nenhuma relação

**Responsabilidade.** Classificar a relação entre duas proposições fornecidas; não cria nenhuma proposição nem infere motivos pessoais. Exemplo: distinguir uma afirmação que apoia outra de outra que a contradiz, ou não retornar nenhuma relação apoiada.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[Modelo AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Artefatos Humanos


**Responsabilidade.** Defina os produtos humanos que a linha de montagem pode construir. Cada produto carrega seu próprio receptor, propósito, estrutura, política de evidências e contrato de entrega, em vez de compartilhar um esboço genérico.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Aterramento + Validação de Entrega

portão de recebimento independente sobre verificações de fidelidade, procedência, perda, invenção, trama e compreensão

**Responsabilidade.** Verifique de forma independente se o artefato preserva o significado suportado e satisfaz seu contrato de entrega declarado antes do lançamento. Exemplo: rejeitar um parágrafo legível que inventa uma conclusão e rejeitar separadamente um documento fundamentado cuja estrutura é inutilizável para o leitor-alvo.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Resolução de público

estado do receptor, pré-requisitos, registro e relevância

**Responsabilidade.** Descreva o que se espera que o receptor pretendido saiba, precise e tolere, mantendo as suposições explícitas. Exemplo: exija que um guia do proprietário explique o pH antes de usar abreviações familiares a um técnico de piscinas.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Colapso de árvore inteira + pacotes

partição, seleção, ganhos e perdas restritas ao contêiner

**Responsabilidade.** Selecionar e equilibrar o que pode caber no artefato solicitado enquanto registra o que foi omitido e preserva a forma significativa da árvore. Exemplo: mantenha cada ramo principal representado em um artigo de 1.000 palavras em vez de deixar que o ramo fonte maior consuma todo o orçamento.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[submodlib](https://github.com/decile-team/submodlib),[joelhada](https://github.com/arvkevi/kneed)

### Modelo de trabalho compacto

transportador portátil com escopo de solicitação para unidades selecionadas, relações, trajetórias, blocos de origem, planos, identificadores e livros de transferência

**Responsabilidade.** Agrupe os fatos, relacionamentos, cronologia, incertezas, falhas e identificações de origem selecionados em um contexto portátil específico do trabalho. Exemplo: forneça ao editor a cadeia de manutenção do pool e por que suas etapas se conectam sem carregar todo o corpus ou descartar os links.

**Deve preservar.** source_spans; relação_ids; cronologia; incerteza; falhas; substituição; incógnitas

**Forma do recurso.** CPU e RAM proporcionais à seleção limitada; sem GPU ou aluguel

**Limite.** A qualidade é limitada pelo relacionamento upstream e pela cobertura do estado do depósito

### Mecânica de Entrega

registro, modos, perfis de tecelagem, ritmo, densidade e controles de deslop

**Responsabilidade.** Forneça restrições de entrega medidas, como ritmo, densidade, registro e trajetória de trama, para este produto e público. Exemplo: dar a uma explicação infantil pacotes mais curtos e um padrão de recorrência diferente de um relatório técnico, sem alterar os factos subjacentes.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Pré-processamento de discurso

fatias limitadas exatas, candidatos de referência FastCoref e links de operando isanlp RST alugados

**Responsabilidade.** Identifique os referentes candidatos e os intervalos de discurso antes de raciocinar a classificação, preservando as coordenadas exatas da fonte. Exemplo: vincule 'isso' ao candidato à bomba nomeado e exponha as duas orações unidas por uma relação discursiva causal.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[IsaNLP RST](https://github.com/tchewik/isanlp_rst),[FastCoref](https://github.com/shon-otmazgin/fastcoref)

### Reconstrução direta de artefato inteiro

pré-requisitos, referentes, cola causal, progressão, introdução e conclusão

**Responsabilidade.** Reconstrua o material selecionado na ordem do leitor, restaurando pré-requisitos, referentes, vínculos causais, progressão e um final honesto. Exemplo: apresente o objetivo antes do procedimento e encerre uma questão não resolvida quando não houver conclusão.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Gráfico do porquê e projeção de dependência

visão determinística de arestas de gráfico classificadas que não podem introduzir novas afirmações de raciocínio

**Responsabilidade.** Traduza bordas de relação aceitas em dependências inspecionáveis ​​e visualizações de porquê sem adicionar interpretação. Exemplo: mostre que a conclusão B depende da premissa A porque existe essa aresta classificada exata.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[RedeX](https://github.com/networkx/networkx)

### Resposta interativa fundamentada


**Responsabilidade.** Retorne uma resposta conversacional com o raciocínio relevante, proveniência, incerteza e caminhos de expansão. O caminho da resposta pode passar por conversas completas e ciclos de vida de evidências sem pretender ser uma execução de geração de documentos.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Ponte de Protocolo Humano

codificação orientada ao receptor da carga útil fixa suportada

**Responsabilidade.** Converter uma carga útil fixa e suportada em um formato que a pessoa pretendida possa seguir, usando o contrato do produto e o padrão de entrega medido; não pode mudar as evidências. Exemplo: transformar a mesma cadeia de raciocínio fundamentada em um e-mail conciso ou em um guia passo a passo, alterando a estrutura de entrega, não as conclusões.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Montagem de Contexto Interativo


**Responsabilidade.** Crie um gráfico de evidências e raciocínio limitado para a questão atual, preservando a cronologia, as correções, as falhas, a identidade da fonte e a autorização. Ele fornece contexto para a resposta sem nivelar o corpus em trechos de pesquisa.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Adesão sem perdas


**Responsabilidade.** Admitir bytes originais e eventos nativos antes da interpretação, registrando apenas fatos de chegada observados. Descrições, carimbos de data/hora inferidos de conteúdo, identidades e relacionamentos permanecem observações com versões separadas.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Evidência Primária


**Responsabilidade.** Manter os depósitos oficiais que representações e produtos posteriores deverão ser capazes de rastrear. A sua existência mantém-se mesmo quando o sistema ainda não consegue explicar o seu significado ou relação.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Árvore Provisória Completa

evidência completa de pré-remoção, dependência, alternativa e estrutura de falha

**Responsabilidade.** Manter a árvore candidata completa com escopo de solicitação, incluindo alternativas, falhas, incógnitas e visualizações substituídas, para que o colapso possa ver o que perderia. Exemplo: reter tanto um tratamento que falhou como a correção posterior antes de selecionar o material para uma guia.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Gráfico de raciocínio

cronologia, relações digitadas, ciclos de vida de reivindicações, falhas e incertezas

**Responsabilidade.** Manter o mapa de proposições, cronologia, tentativas, resultados, conflitos, dependências e incertezas no escopo da solicitação. Exemplo: conectar um tratamento que falhou à correção que o substituiu sem excluir nenhum dos estados.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Solicitação + Contrato de Artefato

propósito, receptor, contêiner, canal, orçamento e veracidade

**Responsabilidade.** Congele o propósito, o receptor, o produto, o canal, o orçamento e o padrão de verdade para que cada engrenagem posterior resolva o mesmo trabalho. Exemplo: distinguir uma explicação de 500 palavras para o leitor geral de um relatório técnico de incidente antes de começar a seleção de evidências.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Expansão reversa

junte para trás sem podar; medir a contribuição marginal

**Responsabilidade.** Passe da solicitação ou das evidências posteriores até os registros relacionados anteriores e reúna a jornada completa do candidato antes que qualquer coisa seja descartada. Exemplo: siga uma questão atual sobre algas através de registros anteriores de pH, tamanho da piscina, manutenção e contexto de uso.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Movimentos retóricos digitados

trabalhos semânticos e dependências, nunca substrings de cabeçalho

**Responsabilidade.** Atribua a cada unidade selecionada uma tarefa comunicativa e uma dependência com base no contrato do produto, e não em uma palavra de título correspondente. Exemplo: marque as evidências como apoiando uma reivindicação e uma falha como configurando a recuperação, em vez de chamar ambas de 'antecedentes'.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Reconstrução Semântica

entidades, proposições, episódios, tentativas, resultados e questões

**Responsabilidade.** Converta observações originais em objetos semânticos atribuídos sem decidir sua importância ou apresentação final. Exemplo: represente uma solução proposta, a tentativa, sua falha e a questão restante como registros vinculados separados.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Representações versionadas


**Responsabilidade.** transcrições, estrutura, texto, OCR, layout e visualizações derivadas

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Por que isso importava

motivação atribuída, preocupação, consequência e relevância atual

**Responsabilidade.** Leve evidências diretas e explicitamente atribuídas sobre o motivo pelo qual a atenção foi investida, deixando desconhecidas as razões não comprovadas. Exemplo: preservar que uma tarefa de manutenção é importante porque protege as pessoas que utilizam equipamento partilhado quando o registo o apoia, em vez de adivinhar esse motivo apenas a partir de uma questão técnica.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Raciocínio + Mecanismo de Artefato

reconstrução controlada por recibo, colapso, protocolo humano e renderização atômica de Markdown

**Responsabilidade.** Coordenar o caminho delimitado de reconstrução e renderização e expor o recebimento de cada etapa; não substitui o julgamento especializado. Exemplo: transportar uma solicitação de composição por meio de seleção, planejamento, realização, validação e gravação atômica.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Gerente de Montagem + Capacidade

caminha os campos obrigatórios para trás, avalia os pré-requisitos, seleciona especialistas verdadeiros, ordena ondas de dependência e ignora o trabalho de valor zero

**Responsabilidade.** Escolha quais especialistas são necessários, em que ordem eles são executados e qual trabalho não agrega valor; não realiza seu trabalho. Exemplo: agende a realização da relação antes da realização da frase e pule uma passagem estilística indisponível que não contribui com nada necessário.

**Deve preservar.** must_preserve_fields; linhagem_campo; explícito_unavailability

**Forma do recurso.** CPU; pouca memória; sem GPU ou aluguel

**Limite.** Observações de custo e valor expõem decisões, mas nunca definem a importância humana

### Reconciliador de orçamento da operadora atômica

mede a fonte indivisível, a cola e os portadores de relação antes da realização e redistribui o orçamento fixo do produto inteiro por uma folga de seção genuína

**Responsabilidade.** Verifique se fatos indivisíveis e portadores de relação cabem em cada seção e, em seguida, mova apenas a folga disponível, preservando o orçamento total do documento. Exemplo: amplie uma seção de procedimento de 90 palavras que contém uma instrução atômica obrigatória de 120 palavras, emprestando palavras não utilizadas de outra seção.

**Deve preservar.** whole_artifact_budget; trabalhos_retóricos obrigatórios; autoridade_fonte; forma_grafo

**Forma do recurso.** CPU; tempo de execução quase zero; evita o desperdício de trabalho de GPU/modelo/verificador do Estágio 8

**Limite.** não pode comprimir uma proposição indivisível; falha se todas as transportadoras necessárias excederem o orçamento do produto declarado

### Gerenciador de religação vinculado à origem

move apenas uma ramificação isolada completa quando seu trabalho de produto atribuído é incompatível e um destino é comprovadamente compatível

**Responsabilidade.** Mova uma ramificação de evidências completa e isolada para a única seção cujo trabalho pode utilizá-la legitimamente, ao mesmo tempo que recusa movimentos ambíguos ou relacionados. Exemplo: reatribuir uma nota de recuperação independente da configuração para a solução de problemas sem duplicá-la em ambas as seções.

**Deve preservar.** branch_identity; source_spans; relação_ids; marginal_gain_ledger

**Forma do recurso.** CPU; baixa latência; sem GPU ou aluguel

**Limite.** recusa movimentos relacionados, ambíguos, parciais ou com excesso de capacidade

### Realizador de relações em todo o documento

transforma arestas de raciocínio aceitas de mesma seção e seção transversal em linguagem conectiva compacta e reproduzível de forma independente, sem repetir ambos os operandos

**Responsabilidade.** Transforme relações gráficas aceitas em linguagem conectiva curta, mantendo a direção, os operandos e os intervalos de origem reproduzíveis de forma independente. Exemplo: realize A-causa-B como uma ponte causal limitada em vez de imprimir A e B como fatos adjacentes não relacionados.

**Deve preservar.** Relationship_direction; operando_identidade; exact_carrier_spans; source_spans; seção_lineage

**Forma do recurso.** CPU; tempo de execução quase zero; sem GPU ou aluguel

**Boundary.** realiza apenas tipos de relacionamento aceitos explícitos; pontes compactas preservam a identidade da borda digitada, mas permanecem redigidas mecanicamente; arestas de mesma portadora, ambíguas, implícitas e desconhecidas permanecem visíveis no gráfico, mas não são afirmadas como prosa

### Motor de conhecimento


**Responsabilidade.** Coordenar acesso, representações derivadas, pesquisa, procedência e empregos duráveis ​​sem mesclar essas responsabilidades em um único estado de verdade. Ele expõe interfaces suportadas aos consumidores enquanto a evidência primária permanece endereçável de forma independente.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Microplanner de cláusula/frase digitada

atribui portadores vinculados à origem para trabalhos retóricos digitados e compila planos de cláusulas, sentenças e parágrafos

**Responsabilidade.** Divida o significado e as relações aprovados em cláusulas, sentenças e parágrafos, preservando suas ligações de origem; não inventa palavras ou reivindicações. Exemplo: planeje uma cláusula de causa seguida de sua consequência e transição para o realizador de superfície.

**Deve preservar.** semantic_unit_ids; relação_ids; formulários_fonte

**Forma do recurso.** CPU; baixa latência; sem GPU ou aluguel

**Boundary.** não inventa uma proposição faltante nem repara um relacionamento não classificado

**Principais ferramentas públicas.**[spaCy](https://github.com/explosion/spaCy),[BlingFire](https://github.com/microsoft/BlingFire)

### Gerente de Contrato de Produto

converte gênero, receptor, propósito, canal, veracidade, atenção e orçamento em campos de produtos necessários e trabalho retórico

**Responsabilidade.** Transforme a solicitação em um checklist concreto para o produto acabado sem escolher evidências ou escrevê-las. Exemplo: para um manual do usuário, exija pré-requisitos, ações ordenadas, orientação de recuperação e fechamento antes de qualquer editor iniciar.

**Deve preservar.** declarado_propósito; receptor; veracidade; canal

**Forma do recurso.** CPU; tempo de execução quase zero; sem GPU ou aluguel

**Limite.** não infere o significado da fonte nem escolhe fatos

### Realizador de superfície de contrato

aplica gramática limitada, morfologia, tipografia, perspectiva e transformações digitadas a unidades de entrega

**Responsabilidade.** Aplicar gramática, morfologia, tipografia e perspectiva permitida a um plano já aprovado; não pode decidir um novo significado. Exemplo: transformar um plano imperativo digitado em uma instrução gramatical sem adicionar uma afirmação de segurança que nunca foi fornecida.

**Deve preservar.** Claim_authority; source_and_relation_bindings; trabalho_retórico

**Forma do recurso.** CPU; o editor candidato opcional pode usar uma concessão de GPU existente, mas não tem autoridade

**Limite.** A gramática fechada é fiel, mas pode permanecer estilisticamente rígida

**Principais ferramentas públicas.**[spaCy](https://github.com/explosion/spaCy)

## Gerenciamento, verificação e operações

### Amf Ari


**Responsabilidade.** Execute o classificador de relação de argumento fixado sobre pares de proposições fornecidos e retorne tentativas pontuadas de suporte, conflito, reformulação ou ausência de relação. Não cria proposições, infere motivos ou certifica os seus próprios rótulos.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[OpenVINO](https://github.com/openvinotoolkit/openvino),[Modelo AMF ARI RoBERTa OpenVINO](https://huggingface.co/arg-tech/amf-ari-roberta-ov-int8)

### Indexador de bate-papo


**Responsabilidade.** Mantém as conversas em um registro longo em vez de deixá-las na janela de bate-papo.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Indexador de arquivos


**Responsabilidade.** Descubra arquivos qualificados e envie trabalhos de indexação limitados e que preservem a procedência. Ele não deve tratar datas do sistema de arquivos, nomes de arquivos ou texto extraído como hora de criação, identidade ou motivo oficial.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Telemetria de Hardware


**Responsabilidade.** Registre o histórico limitado das condições da máquina para que as falhas possam ser comparadas com energia, temperatura, memória e estado do acelerador. A descrição pública omite a cadência de amostragem privada e o layout da máquina.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[psutil](https://github.com/giampaolo/psutil)

### Imagem


**Responsabilidade.** Produza imagens localmente para que um conceito visual não precise cruzar um limite de inferência externa. A geração de imagens permanece separada da autoridade de evidência e da permissão de publicação.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[difusão estável.cpp](https://github.com/leejet/stable-diffusion.cpp),[Z-Imagem-Turbo](https://huggingface.co/Tongyi-MAI/Z-Image-Turbo),[Referência de embalagem Z-Image-Turbo-Windows](https://github.com/airesearch-official/Z-Image-Turbo-Windows)

### Ollama


**Responsabilidade.** A mente pesada. Mais lento e maior, reservado para questões que realmente precisam de mais reflexão do que velocidade.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[Ollama](https://github.com/ollama/ollama),[Qwen3](https://github.com/QwenLM/Qwen3)

### Incorporação de Ollama


**Responsabilidade.** Torna a escrita pesquisável por significado e não por palavras exatas.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[Ollama](https://github.com/ollama/ollama),[Texto incorporado Nômico](https://huggingface.co/nomic-ai/nomic-embed-text-v1.5)

### Locação de energia


**Responsabilidade.** Permite que a máquina fique ociosa silenciosamente e desperte totalmente para o trabalho real.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Retitulador de conversa


**Responsabilidade.** Dá nomes às conversas que significam algo, para que a lista seja localizável, em vez de uma parede de primeiras frases.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Observador Semântico


**Responsabilidade.** Verifica se uma resposta é apoiada pelo material de onde afirma vir.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[Transformadores](https://github.com/huggingface/transformers),[MiniCheck](https://github.com/Liyan06/MiniCheck),[FatoCG](https://github.com/derenlei/FactCG)

### Análise de Resíduos


**Responsabilidade.** Mantém um registro de como cada mente falha e se isso está melhorando ou piorando.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[spaCy](https://github.com/explosion/spaCy),[BlingFire](https://github.com/microsoft/BlingFire),[NLTK](https://github.com/nltk/nltk)

### Discursos


**Responsabilidade.** Transforma a fala em texto, então falar é uma forma de escrever as coisas.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[Discursos](https://github.com/speaches-ai/speaches),[sussurro mais rápido](https://github.com/SYSTRAN/faster-whisper),[mais rápido-destilar-sussurro-grande-v3](https://huggingface.co/Systran/faster-distil-whisper-large-v3)

### Serviço de Tarefas


**Responsabilidade.** Leia registros de tarefas autorizadas como evidência sobre o trabalho planejado, sem convertê-los em lembretes, motivos inferidos ou verdade de corpus.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### vLLM


**Responsabilidade.** A mente cotidiana. Rápido, sempre carregado, responde quase tudo.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

**Principais ferramentas públicas.**[vLLM](https://github.com/vllm-project/vllm),[Qwen3](https://github.com/QwenLM/Qwen3)

### Trabalhos de palco duráveis

lotes limitados, pontos de verificação, cancelamento, retomada e falha parcial

**Responsabilidade.** Execute longos estágios de artefato como trabalhos limitados recuperáveis ​​com estados de terminal verdadeiros, em vez de vinculá-los a uma solicitação do navegador. Exemplo: retomar após um ponto de verificação de promoção verificado, em vez de repetir uma dispendiosa passagem de raciocínio após a interrupção.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Execução + Gerenciador de Manifesto

executa o adaptador atribuído e registra método físico, endpoint, revisão de modelo, hashes, bordas de chamada, tempo, novas tentativas e disposição

**Responsabilidade.** Execute cada especialista designado e registre o que foi executado fisicamente, com suas entradas, identidade, tempo, novas tentativas e resultados. Exemplo: mostre que o classificador AMF fixado administrou o Estágio 2 em vez de confiar em um rótulo de manifesto que apenas diz que sim.

**Deve preservar.** input_hashes; identidade_adaptador; estado_de_falha

**Forma do recurso.** Coordenador da CPU; delegados GPU funcionam apenas através de proprietários de arrendamento declarados

**Boundary.** registra a execução; não pode certificar seu próprio sucesso

### Arbitragem de aluguel de GPU


**Responsabilidade.** Coordene transferências de consultoria entre cargas de trabalho de aceleradores gerenciados pela plataforma sem expor a identidade do dispositivo físico ou interromper o trabalho já em andamento.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Coordenador de Residência de Energia

**Responsabilidade.** Manter um modelo de estado ATIVO, QUENTE, IDLE e NUNCA em toda a energia da plataforma distribuída e mecanismos de residência.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

### Razão de carga útil esperada/observada

une cada responsabilidade da engrenagem aos seus campos observados, prontidão, omissões, valor, custo, tempo, novas tentativas e solicitação de reparo

**Responsabilidade.** Compare a contribuição esperada de cada engrenagem com o que ela realmente transferiu, incluindo custos e insumos ausentes. Exemplo: exponha que a análise de relação foi executada por 40 segundos, mas não forneceu nenhuma borda conectiva utilizável ao editor.

**Deve preservar.** handoff_identity; resumos; faltando_campos; custo_base

**Forma do recurso.** CPU; quase zero em relação ao raciocínio e verificação

**Limite.** O tempo da seção portátil não substitui o tempo do estágio/modelo físico no manifesto de execução

### Gerente de Qualidade Consciente do Produto

verifica a conclusão retórica, raciocínio conectivo, legibilidade, tipografia, duplicação, atenção, orçamento, trama, desleixo e ações executáveis ​​para o produto solicitado

**Responsabilidade.** Avalie se este produto específico funciona para seu leitor e finalidade declarados em eixos de qualidade separados e, em seguida, identifique o estágio de reparo responsável. Exemplo: um manual pode falhar ao perder orientações de recuperação mesmo quando cada frase é gramatical e fundamentada.

**Deve preservar.** individual_axis_results; rejeitado_candidato_evidência

**Forma do recurso.** CPU mais verificador/deslop limitado HTTP; historicamente a maior participação no Estágio 8

**Limite.** Os eixos de gênero devem ser medidos e versionados; um índice de qualidade opaco é proibido

### Gerente de recebimento + promoção

recalcula independentemente invariantes e permite gravação de promoção e artefato atômico somente a partir de um recibo PASS

**Responsabilidade.** Verifique o pacote de forma independente e grave o artefato somente depois que cada invariante necessária for aprovada. Exemplo: recusar promoção quando o renderizador relata sucesso, mas seu recebimento não consegue reproduzir uma ligação de origem.

**Deve preservar.** failed_results; incógnitas; identidade_liberação; limite_reversão

**Forma do recurso.** CPU e E/S; sem GPU ou aluguel

**Limite.** A autenticidade do manifesto depende, em última análise, da ligação imutável de versão/configuração revisada

### Proveniência + Controle de Perdas

identidade de origem, estado epistêmico, inferência, invenção e ramos rejeitados

**Responsabilidade.** Mantenha cada declaração vinculada a quem ou o que a forneceu, quando foi aplicada e se foi observada, inferida, substituída, rejeitada ou desconhecida. Exemplo: preservar uma reinterpretação posterior sem substituir a crença anterior que realmente orientou uma ação.

**Deve preservar.** Identidade exata do gráfico, origem do relacionamento e limite declarado do componente.

**Forma do recurso.** A implantação em tempo real registra o uso real de CPU, memória, armazenamento, acelerador e arrendamento; este catálogo público não expõe o posicionamento da máquina.

**Limite.** Pode executar apenas a responsabilidade declarada do gráfico e não pode reparar evidências upstream ausentes ou não suportadas.

## Componentes adicionais declarados

### Gateway da Web seguro

Fornece acesso remoto autenticado de clientes aprovados sem expor diretamente os serviços da plataforma privada à Internet pública.

### Supervisor de Plataforma

Inicia serviços em ordem de dependência, observa seu funcionamento e executa ações de reinicialização limitadas. A sua falha elimina a supervisão coordenada sem redefinir o estado dos serviços que permanecem em execução.

## Limite de integridade

O catálogo cobre componentes lógicos ativos no gráfico de arquitetura mantida, e não todos os pacotes transitivos instalados em cada tempo de execução. Uma versão futura de software requer uma lista de materiais de software exata e um pacote de licença gerado a partir dos bytes específicos que estão sendo distribuídos.
