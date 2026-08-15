> Português: Tradução assistida por máquina da fonte oficial em inglês. Correções no idioma nativo são bem-vindas. [Inglês](../../README.md) | [Todos os idiomas](../README.md)

# Dando crédito e devolvendo valor

![Caminhos de conhecimento atribuídos que retornam mapas públicos úteis sem apagar suas fontes](../../assets/publish-reciprocity-open-paths.png)

O sistema foi montado independentemente de hardware em grande parte de segunda mão, recursos pessoais e esforço substancial fora do emprego. A sua base intelectual veio de pessoas e instituições dispostas a publicar trabalhos que outros pudessem inspecionar, testar, adaptar dentro dos seus termos, criticar e desenvolver. A atribuição regista, portanto, tanto a linhagem técnica como uma obrigação recíproca: o trabalho público tornou o trabalho possível, e a edição pública devolve os seus resultados delimitados sem reivindicar a propriedade dos contextos que os produziram.

## Por que esse livro-razão existe

O trabalho não poderia existir sem pessoas que escolhessem publicar pesquisas, escrever e manter software, preservar obras culturais, traduzir textos, fazer curadoria de corpora, operar arquivos e disponibilizar seu trabalho para reutilização ou estudo. A sua decisão de partilhar é um exercício de soberania. A disponibilidade pública não torna a sua contribuição anônima ou sem dono.

O livro registra as principais contribuições utilizadas na arquitetura pública. Afirma o que cada fonte forneceu, como foi utilizado e a relação entre a fonte e este projeto. As categorias são importantes:

- **dependência ativa** significa que o software ou modelo é executado em um caminho atual;
- **método adaptado** significa que uma implementação usa um mecanismo publicado sem
  reivindicar o código original como de autoria do projeto;
- **fonte de calibração** significa que o material foi medido e não reproduzido em público
  liberar;
- **influência do projeto** significa que a obra alterou uma decisão arquitetônica;
- **avaliado ou rejeitado** preserva o crédito e o resultado de um experimento sem
  implicando adoção.

Nenhuma entrada implica que seus autores, mantenedores, comunidades, editores, arquivos ou instituições endossem este projeto. Este ZIP de documentação não redistribui nenhum código, pesos de modelo, texto do conjunto de dados ou texto do artigo.

## Fundamentos literários, linguísticos e de comunicação

| Contribuição | Fonte pública ou trabalho de identificação | O que isso contribui aqui | Relação |
|---|---|---|---|
| Carlota S. Smith | *Modos de discurso: a estrutura local dos textos* | Distinções gramaticais entre modos de discurso; suporta análise de entrega digitada. | Influência do design |
| MAK Halliday e Ruqaiya Hasan | *Coesão em inglês* | Separa a coesão superficial da coerência real. | Influência do projeto e base de medição |
| MAK Halliday | Registre-se como campo, teor e modo | Trata o público e a situação comunicativa como dimensões medidas, em vez de decoração imediata. | Influência do design |
| Douglas Biber | *Variação entre fala e escrita* | Análise de registro multidimensional usando características observáveis ​​co-ocorrentes. | Linhagem de medição de tecelagem |
| William Mann e Sandra Thompson | Teoria da Estrutura Retórica | Relações discursivas, nuclearidade e distinção entre material central e de apoio. | Linhagem especializada ativa |
| John Swales | *Análise de gênero* | Movimentos retóricos e etapas usadas para descrever a estrutura do produto. | Linhagem de contrato de produto |
| Gérard Genette e a tradição formalista russa | *Discurso Narrativo*; fabula e sjuzhet | Separa o material do evento da ordem e do ponto de vista de sua narrativa. | Influência narrativa e de reconstrução |
| HP Grice | “Lógica e Conversação” | Máximas cooperativas e a diferença entre desrespeito deliberado e violação acidental. | Protocolo Humano e design de detector |
| Douglas Walton | Esquemas de argumentação e questões críticas | Fornece padrões de desafio inspecionáveis ​​em vez de uma pontuação de argumento opaca. | Influência da análise de argumentos |
| Alexandra Aikhenvald | *Evidência* | Trata a marcação de fontes e evidências como uma responsabilidade linguística. | Influência do papel epistêmico |
| Claude Shannon | “Uma Teoria Matemática da Comunicação” | Fornece o vocabulário formal de comunicação para informações, limites de canais, redundância e perdas. | Influência da arquitetura de comunicação |
| Herbert Clark e Susan Haviland | Novo contrato dado | Suporta a medição do que se presume que um receptor sabe e o que deve ser introduzido. | Linhagem de medição de tecelagem |
| Morton Ann Gernsbacher | Estrutura de construção de estrutura | Suporta estabelecimento, mapeamento e análise de coerência orientados ao receptor. | Influência do Protocolo Humano |
| Benjamim Bloom; Lorin Anderson e David Krathwohl | Taxonomias objetivas educacionais | Fornece um vocabulário explicitamente limitado para a profundidade esperada do receptor. | Influência do contrato de público |

Essas obras forneceram métodos e perguntas, e não respostas universais sobre uma pessoa. A contribuição arquitetônica é conectar seus mecanismos limitados a uma linha de montagem que preserva a proveniência e manter cada inferência reversível e inspecionável.

## Seleção, edição e realização

| Contribuição | Fonte pública | O que isso contribui aqui | Relação |
|---|---|---|---|
| Jaime Carbonell e Jade Goldstein | “O uso de MMR, reclassificação baseada na diversidade para reordenar documentos e produzir resumos” | Equilibra relevância e novidade durante a seleção limitada. | Método adaptado |
| Hui Lin e Jeff Bilmes | Resumo submodular abaixo do orçamento | Seleção com retorno decrescente sob um orçamento explícito. | Método adaptado |
| Eric Malmi, Sebastian Krause, Sascha Rothe, Daniil Mirylenka e Aliaksei Severyn | Laser Tag | Demonstra edição restrita com um vocabulário de inserção fechado. | Influência do design avaliada |
| Kostiantyn Omelianchuk, Vitaliy Atrasevych, Artem Chernodub e Oleksandr Skurzhanskyi | GECToR | Demonstra transformações marcadas e correção iterativa. | Influência do design avaliada |
| Jonathan Mallinson, Jakub Adamek, Eric Malmi e Aliaksei Severyn | Editar5 | Demonstra reordenação baseada em ponteiro que limita a invenção. | Influência do design avaliada |
| Eric Malmi e colaboradores; a comunidade mais ampla de realização de superfície | Trabalho de realização baseado em gramática, gráfico para texto e restrito | Reforça a separação entre determinação, planejamento, realização e verificação de conteúdo. | Influência da arquitetura; sem adoção geral de tempo de execução |

## Especialistas em raciocínio, discurso e verificação

| Contribuição | Fonte pública | O que isso contribui aqui | Relação |
|---|---|---|---|
| Elena Chistova e contribuidores IsaNLP | [Placa modelo IsaNLP RST Parser v3](https://huggingface.co/tchewik/isanlp_rst_v3)e seu trabalho ACL citado; modelo de cartão registra CC BY-NC 4.0 | Produz estruturas de discurso limitadas e candidatos de relação. Não determina o significado pessoal. | Especialista ativo; modelo é usado dentro dos limites da licença não comercial e não é redistribuído aqui |
| Shon Otmazgin, Arie Cattan, Yoav Goldberg e colaboradores FastCoref | [Artigo F-COREF e implementação oficial](https://github.com/shon-otmazgin/fastcoref), MIT | Produz cadeias de correferências candidatas para validação posterior vinculada à origem. | Especialista ativo |
| Chris Reed, grupo ARG-tech, contribuidores AIF/xAIF e contribuidores AMF/ARI | [Registro do módulo oAMF](https://github.com/arg-tech/oAMF),[Conjunto de dados AIF e registro de modelo](https://github.com/arg-tech/aif-arg-datasets)e especificações vinculadas | Classifica relacionamentos de proposições limitadas e fornece vocabulário de gráfico-argumento interoperável. | AMF/ARI é uma linhagem especializada ativa; oAMF foi avaliado como arte anterior de orquestração, em vez de adoção no atacado |
| Liyan Tang, Philippe Laban e Greg Durrett | [MiniCheck](https://aclanthology.org/2024.emnlp-main.499/);[código oficial](https://github.com/Liyan06/MiniCheck) | Observações eficientes de factualidade sobre reivindicações e documentos de fundamentação. | Especialista avaliado; não liberar autoridade |
| Deren Lei, Yaxi Li, Siyao Li, Mengya Hu, Rui Xu, Ken Archer, Mingyu Wang, Emily Ching e Alex Deng | [FatoCG](https://aclanthology.org/2025.naacl-long.258/);[código oficial](https://github.com/derenlei/FactCG) | Observações de factualidade multi-hop informadas por gráfico. | Especialista avaliado; não liberar autoridade |
| Philippe Laban, Tobias Schnabel, Paul N. Bennett e Marti A. Hearst | [SummaC](https://aclanthology.org/2022.tacl-1.10/) | Expõe problemas de granularidade de frases/documentos na verificação de consistência. | Influência do design |
| Lorena Scirè, Simone Conia e Roberto Navigli | [FENICE](https://arxiv.org/abs/2403.02270) | Extração de declarações e alinhamento de evidências para avaliação de sumarização. | Influência do design |
| Xiangkun Hu e colaboradores | [Verificador de referência](https://github.com/amazon-science/RefChecker) | Suporte refinado, refutação e registros desconhecidos. | Influência do design avaliada |
| Trieu H. Trinh e colaboradores | [AlfaGeometria](https://github.com/google-deepmind/alphageometry) | Fechamento de dedução monotônico e traços explícitos de dependência de prova. Regras de geometria não são usadas. | Influência do design |

MiniCheck e FactCG foram avaliados com revisões públicas fixadas e suas licenças publicadas. Suas pontuações não eram separáveis ​​em mutações importantes no formato do projeto, então eles foram removidos da autoridade de divulgação. Preservar esse resultado negativo faz parte da reciprocidade: as ferramentas são creditadas pelo que conseguem observar sem deturpar o que os seus autores alegaram que poderiam provar.

## Contribuidores de software

Os seguintes projetos de software público fornecem maquinário limitado. Seus respectivos avisos e licenças de direitos autorais regem qualquer redistribuição de seu código; esta documentação pública não a redistribui.

| Programas | Contribuintes ou administrador | Licença gravada | Função limitada |
|---|---|---|---|
| spaCy e seus modelos de linguagem | Explosion AI, Matthew Honnibal, Ines Montani e colaboradores | MIT | Classe gramatical, morfologia, análise de dependência e medidas estruturais |
| BlingFire | Microsoft e colaboradores | MIT | Segmentação de frases |
| LemmInflect | Brad Jacob e colaboradores | MIT | Inflexão inglesa |
| submodlib | Vishal Kaushal, Rishabh Iyer, Ganesh Ramakrishnan e colaboradores DECILE | MIT | Seleção submodular |
| NLTK | Steven Bird, Edward Loper, Ewan Klein e colaboradores | Apache-2.0 | Acesso ao corpus e utilidades linguísticas |
| NumPy | Contribuidores NumPy | Cláusula BSD-3 | Matrizes numéricas e matrizes de similaridade |
| SciPy | Colaboradores do SciPy | Cláusula BSD-3 | Clustering e operações estatísticas |
| RedeX | Colaboradores da NetworkX | Cláusula BSD-3 | Operações e medições gráficas direcionadas |
| joelhada | Kevin Arvai e colaboradores | Cláusula BSD-3 | Detecção de ponto de joelho para curvas de calibração medidas |
| PyYAML | Kirill Simonov e colaboradores | MIT | Intercâmbio de configuração estruturada |
| httpx | Tom Christie e colaboradores | Cláusula BSD-3 | Transporte HTTP de limite de serviço |
| psicopg | Daniele Varrazzo e colaboradores | LGPL-3.0 | Acesso PostgreSQL |
| Pidantico | Contribuidores Pydanticos | MIT | Validação digitada e serialização |
| OpenVINO | Intel e colaboradores | Apache-2.0 | Inferência de modelo limitado onde configurada |
| descritivos de texto | Lasse Hansen, Kenneth Enevoldsen e colaboradores | Apache-2.0 | Medições de legibilidade, coerência e teoria da informação |
| LFTK | Bruce W. Lee e Jason Hyung-Jong Lee | Licença pública de projeto; verifique com qualquer versão redistribuída | Extração de características linguísticas avaliada para calibração |

A tabela é um inventário principal e não um substituto para avisos de dependência gerados por máquina em uma distribuição de código futura. Versões exatas, hashes, licenças transitivas e textos de licença completos devem acompanhar qualquer versão que redistribua software ou arquivos de modelo.

## Obras culturais, corpora, arquivos e comunidades

A análise mede padrões de entrega e propriedades estruturais. A menos que uma licença separada permita a reprodução, a produção pública contém medidas agregadas e identidades de origem, e não texto de origem.

| Fonte | Pessoas ou instituições sendo creditadas | Limite de permissão e uso | Contribuição |
|---|---|---|---|
| Projeto Gutenberg | Michael S. Hart, revisores distribuídos, autores, editores, tradutores e voluntários participantes | Textos verificados de domínio público são medidos; Os termos da edição e marca registrada do Project Gutenberg permanecem respeitados. | Calibração literária e de formato de produto de longo período |
| LibriVox | Leitores voluntários, mantenedores e autores de textos-fonte de domínio público | LibriVox registra textos de domínio público e dedica suas gravações ao domínio público de acordo com sua política declarada. | Calibração da entrega falada do candidato; não silenciosamente agrupado com impressão |
| Corpus Marrom | W. Nelson Francis, Henry Kučera, Brown University e curadores | Usado por meio de seus termos de corpus distribuído para medição agregada. | Contrastes de registro rotulados por gênero |
| Reuters-21578 | Reuters, David Lewis e curadores | Agregue medições apenas sob os termos de distribuição do conjunto de dados. | Comparação densa de cópia eletrônica |
| Corpus de bate-papo NPS | Eric Forsyth, Jane Lin, Craig Martell e a Escola de Pós-Graduação Naval | Medição agregada; o texto pessoal não é reproduzido publicamente. | Comparação de bate-papo entre humanos |
| Traduções da Declaração Universal dos Direitos Humanos | ACNUDH e tradutores das Nações Unidas | Traduções paralelas medidas como controle; atribuição mantida. | Separa padrões de protocolo entre idiomas dos hábitos do inglês |
| arXiv | Cornell University, arXiv, autores submissos e mantenedores | Os metadados são tratados de acordo com os termos publicados; os resumos permanecem como trabalhos dos autores e não são reproduzidos. | Medição longitudinal de registro científico |
| PubMed/MEDLINE | Biblioteca Nacional de Medicina dos EUA, periódicos participantes e autores | Somente medição agregada; os resumos não são redistribuídos e nenhum endosso do NLM está implícito. | Comparação de prosa científica |
| Delpher | Koninklijke Bibliotheek, colaboradores, editores e autores de digitalização | Medição agregada apenas porque os direitos em nível de item variam. | Comparação de jornais de longo período |
| Wikipédia | Fundação Wikimedia e editores colaboradores | Fonte CC BY-SA; nenhum texto do artigo é reproduzido nesta publicação. | Comparação de registro da enciclopédia |
| Estouro de pilha | Stack Exchange e a comunidade de resposta | Fonte CC BY-SA; nenhum texto da postagem é reproduzido aqui. | Comparação fórum-resposta |
| Amostras de Hacker News e Mastodon | Operadores de plataforma e autores individuais da comunidade | Nenhuma licença de conteúdo geral é assumida; apenas observações agregadas não identificadoras são publicáveis. | Comparação exploratória de formato moderno |

O retorno recíproco do projeto público não é a posse dessas obras. É um relato auditável dos métodos que eles possibilitaram, dos limites encontrados, das hipóteses fracassadas que ajudaram a falsificar e de medições reutilizáveis ​​que preservam um caminho de volta aos seus colaboradores.

A reciprocidade também rege o uso de modelos externos. Fornecer uma carga útil de trabalho autorizada para uma contribuição limitada não torna o serviço externo o proprietário do corpus mantido, assim como o uso de pesquisas publicadas não apaga sua autoria. A contribuição deve ser creditada e medida, enquanto a fonte, a autoridade e o valor contínuo do registo subjacente permanecem distintos. A reciprocidade evita que a derivação útil se torne uma desculpa para destruir o contexto humano e concentrar o seu valor na instituição receptora.

## Limite de direitos e integridade

Status de domínio público, acesso aberto, código aberto e permissão para análise computacional são estados de direitos diferentes. O livro-razão registra a base aplicável em vez de tratar “disponível on-line” como permissão. Fontes que exigem evasão, autorização incerta ou uma teoria de uso justo não revisada são excluídas dos novos conjuntos de dados de publicação.

O livro-razão cobre os principais fundamentos visíveis na documentação pública. O projeto privado mantém um inventário evolutivo maior, incluindo candidatos avaliados e rejeitados. Uma futura versão acadêmica ou de software deve produzir uma lista de materiais de software específica para o artefato, modelo e livro-razão de conjunto de dados, bibliografia, pacote de licença e registro de transformação. A omissão deste resumo não apaga o crédito nem concede permissão.
