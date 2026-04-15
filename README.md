# Documento de Especificação de Requisitos da Ontologia (ORSD)

**Domínio:** Processo Administrativo de Registro de Recusa Escolar (_Futoko_) **Versão:** 1.1 **Base documental primária:** 不登校対策（COCOLOプラン等）について — Ministério da Educação, Cultura, Esportes, Ciência e Tecnologia do Japão (MEXT), 2023.

---

## 1. Escopo

O escopo desta ontologia compreende o processo administrativo de identificação, classificação e registro de estudantes enquadrados na categoria de _Futoko_ (recusa escolar) conforme definição e regulamentação institucionais do MEXT.

São objetos diretos de modelagem: os critérios quantitativos e qualitativos de classificação estabelecidos pelo MEXT; os instrumentos de coleta e consolidação de dados, incluindo o 問題行動等調査 (levantamento anual sobre comportamentos problemáticos e ausências escolares); os agentes administrativos envolvidos no processo de registro, desde o nível da escola até os órgãos municipais, prefeiturais e nacionais; e os instrumentos e estruturas de suporte institucionalizados pelo COCOLOプラン, publicado pelo MEXT em 2023.

Estão fora do escopo desta ontologia: intervenções clínicas, terapêuticas ou pedagógicas para casos de recusa escolar; análises de eficácia das políticas de suporte; aspectos jurídicos da obrigatoriedade escolar; e qualquer sistema educacional externo ao Japão.

---
## 2. Objetivo

O objetivo desta ontologia é produzir uma representação formal e explícita do processo administrativo de registro da recusa escolar (_Futoko_) tal como estruturado pelo MEXT, com base nos documentos institucionais vigentes.

Operacionalmente, a ontologia deve: (i) formalizar os conceitos, critérios e relações que constituem a classificação administrativa de _Futoko_; (ii) representar o fluxo de registro da ausência escolar, da unidade de ensino até a consolidação nos levantamentos nacionais; e %% (iii) modelar os instrumentos de suporte previstos pelo COCOLOプラン e sua articulação com o processo administrativo de acompanhamento do estudante. %%

---
## 3. Linguagens

A ontologia será desenvolvida em duas camadas distintas e complementares.

Na camada conceitual será utilizada a linguagem OntoUML, que permite a modelagem guiada pela Unified Foundational Ontology (UFO). Essa camada priorizará a representação precisa dos tipos ontológicos envolvidos, como papéis, eventos, relações e qualidades. Será elaborada com a  ferramentas de modelagem Visual Paradigm compatível com OntoUML a partir de um plug-in público.

Na camada de implementação formal, a ontologia será expressa em Web Ontology Language (OWL 2), viabilizando raciocínio automatizado, integração com outros artefatos semânticos e publicação em conformidade com os padrões da Web Semântica.

As anotações de classes e propriedades serão redigidas em português, com inclusão dos termos japoneses originais em kanji/kana e romaji como metadados, de modo a preservar a fidelidade terminológica à fonte primária. %%Talvez até a data da publicação seja traduzida para inglês %%

---

## 4. Usuários

A ontologia é destinada a três perfis de usuários:

==Pesquisadores acadêmicos== das áreas de educação comparada, sociologia da educação e psiquiatria infantojuvenil, com interesse na caracterização formal do processo administrativo de registro da recusa escolar no Japão.

==Gestores e técnicos== de políticas educacionais com interesse no modelo institucional japonês de classificação e acompanhamento do _Futoko_, para fins de estudo e referência.

==Especialistas em ontologias== e engenharia do conhecimento que utilizarão o artefato como referência para desenvolvimento, alinhamento ou extensão de ontologias no domínio educacional.

---

## 5. Casos de Uso

**CU01 — Consulta aos critérios de classificação de _Futoko_.** Um pesquisador de educação necessita compreender quais critérios formais o MEXT adota para classificar um estudante com _Futoko_. A ontologia deve permitir a recuperação estruturada desses critérios, incluindo limiares quantitativos (número de dias de ausência), exclusões categóricas (doença, razões econômicas) e a tipologia dos motivos de ausência reconhecidos.

**CU02 — Rastreamento do fluxo administrativo de registro.** Um especialista em engenharia do conhecimento precisa mapear o caminho percorrido pela informação de ausência: desde o registro inicial pelo docente ou pela escola, passando pela consolidação junto aos órgãos municipais e prefeituras, até a incorporação no levantamento anual do MEXT (問題行動等調査). A ontologia deve representar os agentes, os eventos e os instrumentos documentais envolvidos em cada etapa desse fluxo.

**CU03 — Identificação e modelagem dos instrumentos de suporte do COCOLOプラン.** Um pesquisador de políticas públicas necessita identificar quais instrumentos administrativos e de suporte foram instituídos pelo COCOLOプラン para estudantes com _Futoko_, como a Ficha de Suporte Individual (支援シート) e os Centros de Apoio Educacional (教育支援センター) e de que forma esses instrumentos se articulam com o processo de registro e acompanhamento do estudante.

**CU04 — Pesquisa Comparativa de Modelos de Ausência Escolar.** Um pesquisador interessado em educação comparada busca analisar como o modelo administrativo japonês do _Futoko_ se relaciona ou se diferencia de outros sistemas internacionais de gestão de abandono ou recusa escolar. A ontologia deve atuar como um referencial semântico que permita identificar pontos de convergência e divergência entre o sistema do MEXT e frameworks educacionais de outros países, facilitando a transposição e o mapeamento de conceitos para estudos globais.

---

## 6. Requisitos Funcionais — Questões de Competência

**CQ1:** Quais são os critérios formais estabelecidos pelo MEXT para classificar um estudante como _Futoko_?

**CQ2:** Quais categorias de motivo de ausência são reconhecidas pelo MEXT, e quais delas são explicitamente excluídas da classificação de _Futoko_?

**CQ3:** Quem são os agentes administrativos responsáveis pelo registro da ausência em cada etapa do fluxo da escola ao levantamento nacional e quais instrumentos documentais formalizam cada transferência de informação?

%%**CQ4:** Quais instrumentos de suporte foram instituídos pelo COCOLOプラン para estudantes identificados como _Futoko_, e como sua aplicação é registrada administrativamente? %%

%%**CQ5:** De que modo a frequência em estruturas externas à escola regular como os Centros de Apoio Educacional (教育支援センター) e as escolas de diversificação da aprendizagem (学びの多様化学校) é contabilizada e registrada para fins administrativos? %%

**CQ6:** Como o processo administrativo de acompanhamento do estudante com _Futoko_ é documentado ao longo do tempo, e quais são os eventos que marcam transições de estado nesse processo?

---

## 7. Requisitos Não-Funcionais — Princípios FAIR

**Findable:** Todas as classes, propriedades e instâncias da ontologia receberão identificadores únicos e persistentes (URIs), acompanhados de metadados descritivos que incluam título, domínio, versão, data de criação e referências bibliográficas às fontes primárias do MEXT. A ontologia será registrada em repositórios de ontologias reconhecidos, como o BioPortal ou o LOV (Linked Open Vocabularies).

**Accessible:** A ontologia será disponibilizada em formato OWL 2, acessível via protocolo HTTP/HTTPS padrão, sem restrição de autenticação para leitura. A documentação em linguagem natural em <!-- português-->, com os termos japoneses originais em kanji/kana e romaji estará associada a cada elemento por meio de anotações.

**Interoperable:** A modelagem conceitual será guiada pela UFO por meio da OntoUML, garantindo compatibilidade com outros artefatos desenvolvidos sob o mesmo fundamento ontológico. Na camada OWL, serão utilizadas propriedades de alinhamento (`owl:equivalentClass`, `skos:exactMatch`, `skos:closeMatch`) para articulação com vocabulários educacionais externos relevantes.

**Reusable:** Cada elemento da ontologia será acompanhado de definição explícita, contexto de uso e referência direta ao documento-fonte do MEXT. A ontologia será publicada sob licença aberta (Creative Commons CC BY 4.0), e sua estrutura modular permitirá que componentes específicos como o modelo de fluxo administrativo ou a taxonomia de motivos de ausência sejam reutilizados de forma independente.

---

## 8. Glossário

Os termos abaixo constituem o vocabulário central da ontologia. As definições marcadas como [MEXT] derivam diretamente dos documentos institucionais do Ministério da Educação, Cultura, Esportes, Ciência e Tecnologia do Japão.

---

**不登校 | Futoko | Recusa Escolar** Condição do estudante do ensino fundamental ou médio que está ausente da escola por 30 ou mais dias letivos no ano, por razões psicológicas, emocionais, físicas (como letargia e ansiedade) ou sociais, excluídos os casos motivados exclusivamente por doença física orgânica ou por condições econômicas. [MEXT]

**問題行動等調査 | Mondai Kōdō-tō Chōsa | Levantamento sobre Comportamentos Problemáticos e Outros** Pesquisa estatística anual conduzida pelo MEXT junto às escolas públicas e privadas do Japão, que coleta dados sobre bullying, violência escolar, abandono e _Futoko_. Constitui a principal fonte de dados administrativos nacionais sobre ausência escolar. [MEXT]

**COCOLOプラン | COCOLO Plan | Plano COCOLO** Conjunto de medidas de enfrentamento ao _Futoko_ publicado pelo MEXT em 2023, intitulado formalmente 「誰一人取り残されない学びの保障に向けた不登校対策」(_Futoko Taisaku_). O plano articula cinco eixos de ação: detecção precoce de sinais de sofrimento; criação de espaços de pertencimento dentro das escolas; criação de espaços fora das escolas; expansão das 学びの多様化学校; e fortalecimento do suporte individualizado. [MEXT]

**支援シート | Shien Shīto | Ficha de Suporte Individual** Instrumento documental utilizado pelas escolas para registrar o acompanhamento de cada estudante identificado com _Futoko_, contendo o histórico de ausências, as intervenções realizadas e os encaminhamentos feitos a outros serviços. Representa o principal artefato administrativo individualizado do processo de registro e acompanhamento. [MEXT]

**教育支援センター | Kyōiku Shien Sentā | Centro de Apoio Educacional** Estrutura de suporte externo à escola regular, mantida pelos municípios (市区町村), destinada a receber estudantes com _Futoko_ e garantir continuidade de aprendizagem fora do ambiente escolar convencional. A frequência nesses centros pode ser contabilizada como presença escolar para fins do registro administrativo. [MEXT]

%%**学びの多様化学校 | Manabi no Tayōka Gakkō | Escola de Diversificação da Aprendizagem** Denominação adotada pelo COCOLOプラン para instituições autorizadas pelo MEXT a operar com currículos e estruturas de horário adaptados, destinadas a atender estudantes com _Futoko_. Substituiu a denominação anterior 不登校特例校, com vistas à redução do estigma associado ao termo. [MEXT] %%

%%**不登校特例校 | Futoko Tokurei Kō | Escola de Exceção para Recusa Escolar** Denominação anterior às 学びの多様化学校, utilizada para escolas com autorização especial do MEXT para adequar currículo e carga horária a estudantes com _Futoko_. O termo foi reformulado pelo COCOLOプラン. [MEXT] %%

**欠席 | Kesseki | Ausência / Falta** Registro administrativo do não comparecimento do estudante a um dia letivo. A acumulação de _kesseki_ por 30 ou mais dias no ano letivo, sob os critérios específicos do MEXT, aciona o processo de classificação formal como _Futoko_. [MEXT]

**登校拒否 | Tōkō Kyohi | Recusa de Comparecimento** Termo utilizado anteriormente pelo MEXT, de conotação mais volitiva, para designar o não comparecimento à escola. Foi progressivamente substituído por _Futoko_ a partir dos anos 1990, refletindo uma mudança de perspectiva institucional de comportamento recusante para condição que requer suporte. [MEXT]

**都道府県 | Todōfuken | Prefeitura** Unidade administrativa regional do Japão, responsável pela supervisão das escolas de ensino médio e pela consolidação dos dados municipais antes do repasse ao MEXT. [MEXT]
