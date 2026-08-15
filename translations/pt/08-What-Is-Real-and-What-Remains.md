> Português: Tradução assistida por máquina da fonte oficial em inglês. Correções no idioma nativo são bem-vindas. [Inglês](../../README.md) | [Todos os idiomas](../README.md)

# O que é real e o que permanece

![Ideias, testes, falhas e capacidades verificadas cruzando portas de implementação distintas](../../assets/evidence-implementation-gates.png)

## Aulas de evidências

O modelo de evidência mantém diversas classes distintas:

- **evidência primária:** artefatos de origem preservados e eventos de interação;
- **evidência derivada:** texto extraído, unidades semânticas, relacionamentos, classificações,
  observações temporais e outras representações versionadas;
- **evidência de execução:** manifestos, observações de chamada, custos, identidades de modelo e
  resultados da etapa;
- **evidência de aceitação:** invariantes independentes, recibos, pacotes promovidos e
  hashes de saída exatos;
- **intenção do projeto:** arquitetura e comportamento planejado ainda não comprovados em execução;
- **afirmações históricas:** o que um lançamento ou experimento anterior relatou sobre si mesmo.

Um teste aprovado é evidência apenas do envelope que ele exerce. Um documento de lançamento não é prova de que o tempo de execução atual ainda corresponde a ele. Uma biblioteca instalada não é um recurso implementado.

## Fundações implementadas

A implementação demonstrou as seguintes bases limitadas:

- preservação de fonte endereçada ao conteúdo e manipulação de evidências orientada a anexos;
- artefatos, representações, localizadores e eventos de origem separados;
- eventos de conversação vinculados a atores e sequências;
- pré-processamento de discurso e correferência com fatias de origem limitadas;
- classificação de relações de argumentos com extensões de origem exatas e tentativas retidas;
- um gráfico de proposição e relação digitado;
- projeção de dependência determinística;
- contribuições da Matriz de Significado Pessoal com escopo de solicitação com incerteza e
  bandeiras de proteção;
- seleção retroativa e objetos de reprodução direta do mesmo gráfico em testes limitados;
- alocação de unidades semânticas de propriedade global e planejamento de artefatos entrelaçados;
- pisos de renderização aterrados e comparação opcional de candidatos;
- promoção independente com recibo;
- trabalhos de artefatos duráveis ​​e um visualizador de raciocínio;
- um limite de publicação de documentos públicos com lançamentos endereçados ao conteúdo.

Estas declarações descrevem os limites demonstrados dos componentes, não uma afirmação de que toda a visão está completa.

A comparação demonstrada também registra um limite de engrenagem externa. Um modelo de fronteira recebeu uma carga útil preparada e específica para a solicitação e contribuiu com uma renderização mais refinada sem receber o corpus mantido ou se tornar autoridade de lançamento. A evidência apoia essa transação limitada; ela não estabelece o que qualquer provedor retém fora do caminho do artefato testado, o que permanece uma questão contratual e de privacidade separada. Estabelece que a contribuição útil não exigiu a transferência do registo humano para redução destrutiva em valor de propriedade do fornecedor.

## Balança de plataforma instalada

Um inventário limitado do sistema de arquivos da árvore de aplicativos instalados contou cerca de 566.000 arquivos e 218 GiB. Os ativos do modelo representaram aproximadamente 172 GiB, dependências e tempos de execução de linguagem por 25 GiB, estado de dados e outros ativos por 20 GiB e fonte de implementação por cerca de 184 MiB. O inventário encontrou algumas entradas ilegíveis ou alteradas, portanto, essas são estimativas de escala operacional, e não uma lista de materiais de software.

A assimetria é uma evidência intencional sobre a arquitetura. O código-fonte é uma pequena parte do espaço instalado; pesos de modelo e tempos de execução reutilizáveis ​​dominam-no. O plano de controle, portanto, rastreia o valor, a autoridade e o custo operacional de cada especialista, em vez de tratar o tamanho instalado como capacidade. Uma futura versão de código distribuível precisa de um inventário de dependência específico do artefato, versões exatas, licenças, hashes e limite de construção reproduzível.

## Aulas de engenharia preservadas pelo design

O desenvolvimento produziu várias lições de engenharia duráveis:

- solicitar um modelo geral para simular um especialista ausente;
- tratar uma saída de processo ou manifesto auto-relatado como prova de capacidade;
- conduzir o discurso após a classificação semântica e duplicar o trabalho especializado;
- atribuir a primeira ocorrência de citação repetida como proveniência;
- permitir que um item de evidência de todo o arquivo torne a composição inverificável;
- tratar relações zero aceitas como falha de pipeline;
- confundir uma projeção gráfica determinística com um especialista executado separadamente;
- combinar um perfil de trama enquanto produz prosa sem suporte ou ilegível;
- depuração com execuções de corpus inteiro quando casos pequenos e médios expuseram o defeito;
- ajustar um produto de uma forma que poderia regredir outro.

A arquitectura pública mantém estas correcções porque explicam a finalidade das restrições actuais e tornam mais fiáveis ​​os refinamentos futuros.

## Oportunidades atuais de desenvolvimento

Várias capacidades importantes permanecem incompletas ou requerem evidências mais amplas:

- rótulos de relacionamento precisam de avaliação independente de qualidade por especialistas, não apenas estruturais
  validação;
- links temporais de depósito cruzado e reatribuição precisam de testes contínuos em maiores
  limites de fontes mistas;
- motoristas pessoais de alto nível devem permanecer despovoados até que evidências vinculadas à fonte e
  o comportamento da lente os justifica;
- diferentes tipos de produtos precisam de linhas de montagem calibradas e protegidas contra regressão;
- O feedback do Protocolo Humano necessita de evidências de resultados longitudinais;
- mecanismos figurativos e narrativos exigem avaliação consciente do produto antes
  autoridade é concedida;
- a documentação pública completa requer revisão editorial contínua, pois o registro privado
  evolui.

## Escada de validação

O desenvolvimento prossegue de pequeno a grande porte:

1. esquema puro e fixtures invariantes;
2. exemplos semânticos curtos com topologia conhecida;
3. pequenas fatias reais da fonte;
4. fatias médias de formato misto e de tempo misto;
5. limites de escalabilidade maiores após a passagem dos níveis anteriores;
6. comparação de autoria humana versus geração de sistema sob a mesma evidência,
  receptor, formulário e orçamento.

A comparação diagnostica se a perda veio da seleção do gráfico, alocação de importância, reprodução direta, realização ou legibilidade final, em vez de atribuir cada defeito à “qualidade do modelo” genérica.
