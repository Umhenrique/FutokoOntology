# ENGLISH 

## Ontology Requirements Specification Document (ORSD)
Domain: Administrative Process for School Refusal Registration (Futoko) Version: 1.1 Primary documentary base: 不登校対策（COCOLOプラン等）について — Ministry of Education, Culture, Sports, Science and Technology of Japan (MEXT), 2023.
--- 
### 1. Scope

The scope of this ontology covers the administrative process of identifying, classifying, and registering students falling under the category of Futoko (school refusal) as defined and regulated by MEXT institutions.
The direct objects of modeling are: the quantitative and qualitative classification criteria established by MEXT; the data collection and consolidation instruments, including the 問題行動等調査 (annual survey on problematic behaviors and school absences); the administrative agents involved in the registration process, from the school level up to municipal, prefectural, and national bodies; and the support instruments and structures institutionalized by the COCOLOプラン, published by MEXT in 2023.
Outside the scope of this ontology are: clinical and therapeutic interventions for school refusal cases; analyses of the effectiveness of support policies; legal aspects of compulsory schooling; and any educational system outside Japan.
---
### 2. Objective

The objective of this ontology is to produce a formal and explicit representation of the administrative process for registering school refusal as structured by MEXT, based on current institutional documents. (The base documents are available in this repository.)
Operationally, the ontology must: (i) formalize the concepts, criteria, and relationships that constitute the administrative classification of school refusal; (ii) represent the flow of absence registration, from the educational unit through to consolidation in national surveys; (iii) model the support instruments provided by the COCOLOプラン and their articulation with the administrative process of student follow-up.
---
### 3. Languages

The ontology will be developed in two distinct and complementary layers.
The conceptual layer will use the OntoUML language. This layer will prioritize precise representation of the ontological types involved, such as roles, events, relations, and qualities. It will be developed using Visual Paradigm modeling tools compatible with OntoUML via a public plug-in.
In the formal implementation layer, the ontology will be expressed in Web Ontology Language (OWL), enabling automated reasoning, integration with other semantic artifacts, and publication in conformance with Semantic Web standards.
---
### 4. Users

The ontology is intended for three user profiles:
Academic researchers in the fields of comparative education, sociology of education, and child and adolescent psychiatry, with an interest in the formal characterization of the administrative process for registering school refusal in Japan.
Managers and technical staff in educational policy with an interest in the Japanese institutional model for classifying and monitoring school refusal, for study and reference purposes.
Ontology specialists and knowledge engineers who will use the artifact as a reference for developing, aligning, or extending ontologies in the educational domain.
---
### 5. Use Cases

UC01 — Query of school refusal classification criteria. An education researcher needs to understand which formal criteria MEXT adopts to classify a student as having school refusal. The ontology must allow the structured retrieval of these criteria, including quantitative thresholds, categorical exclusions, and the typology of recognized absence reasons.
UC02 — Tracing the administrative registration flow. A knowledge engineering specialist needs to map the path taken by absence information. The ontology must represent the agents, events, and documentary instruments involved at each stage of this flow.
UC03 — Identification and modeling of COCOLOプラン support instruments. A public policy researcher needs to identify which administrative and support instruments were established by the COCOLOプラン for students with school refusal — such as the Individual Support Sheet (支援シート) and the Educational Support Centers (教育支援センター) — and how these instruments articulate with the process of student registration and follow-up.
UC04 — Comparative Research on School Absence Models. A researcher interested in comparative education seeks to analyze how the Japanese administrative model of school refusal relates to or differs from other international systems for managing school dropout or refusal. The ontology should serve as a semantic reference that enables the identification of points of convergence and divergence between the MEXT system and educational frameworks from other countries, facilitating concept transposition and mapping for global studies.
---
### 6. Functional Requirements — Competency Questions

CQ1: What formal criteria are required to classify a student as having school refusal?
CQ2: What absence reasons exclude the school refusal classification?
CQ3: Which administrative agents register school absences?
CQ4: Which documentary instruments formalize the transfer of information?
CQ5: Which administrative processes account for attendance at external structures?
CQ6: Which events mark state transitions?
---
### 7. Non-Functional Requirements — FAIR Principles

Findable: All classes, properties, and instances of the ontology will receive unique and persistent identifiers (URIs), accompanied by descriptive metadata including title, domain, version, and creation date. The ontology will be registered in recognized ontology repositories such as BioPortal or LOV.
Accessible: The ontology will be made available in OWL 2 format, accessible via standard HTTP/HTTPS protocol, with no authentication required for reading.
Interoperable: Conceptual modeling will be carried out using OntoUML, ensuring compatibility with other artifacts developed under the same ontological foundation. In the OWL layer, alignment properties will be used for articulation with relevant external educational vocabularies.
Reusable: The ontology will be published under an open license, and its modular structure will allow specific components to be reused independently.
---
# PORTUGUES

## Documento de Especificação de Requisitos da Ontologia (ORSD)

Domínio: Processo Administrativo de Registro de Recusa Escolar (_Futoko_) **Versão:** 1.1 **Base documental primária:** 不登校対策（COCOLOプラン等）について — Ministério da Educação, Cultura, Esportes, Ciência e Tecnologia do Japão (MEXT), 2023.

---

### 1. Escopo

O escopo desta ontologia compreende o processo administrativo de identificação, classificação e registro de estudantes enquadrados na categoria de Futoko (recusa escolar) conforme definição e regulamentação institucionais do MEXT.
São objetos diretos de modelagem: os critérios quantitativos e qualitativos de classificação estabelecidos pelo MEXT; os instrumentos de coleta e consolidação de dados, incluindo o 問題行動等調査 (levantamento anual sobre comportamentos problemáticos e ausências escolares); os agentes administrativos envolvidos no processo de registro, desde o nível da escola até os órgãos municipais, prefeiturais e nacionais; e os instrumentos e estruturas de suporte institucionalizados pelo COCOLOプラン, publicado pelo MEXT em 2023.
Estão fora do escopo desta ontologia: intervenções clínicas e terapêuticas para casos de recusa escolar; análises de eficácia das políticas de suporte; aspectos jurídicos da obrigatoriedade escolar; e qualquer sistema educacional externo ao Japão.

---
### 2. Objetivo

O objetivo desta ontologia é produzir uma representação formal e explícita do processo administrativo de registro da recusa escolar tal como estruturado pelo MEXT, com base nos documentos institucionais vigentes. (Os documentos base estao disponiveis neste repositório)
Operacionalmente, a ontologia deve: (i) formalizar os conceitos, critérios e relações que constituem a classificação administrativa de recusa escolar; (ii) representar o fluxo de registro da ausência escolar, da unidade de ensino até a consolidação nos levantamentos nacionais; (iii) modelar os instrumentos de suporte previstos pelo COCOLOプラン e sua articulação com o processo administrativo de acompanhamento do estudante.

---
### 3. Linguagens

A ontologia será desenvolvida em duas camadas distintas e complementares.
Na camada conceitual será utilizada a linguagem OntoUML. Essa camada priorizará a representação precisa dos tipos ontológicos envolvidos, como papéis, eventos, relações e qualidades. Será elaborada com a  ferramentas de modelagem Visual Paradigm compatível com OntoUML a partir de um plug-in público.
Na camada de implementação formal, a ontologia será expressa em Web Ontology Language (OWL), viabilizando raciocínio automatizado, integração com outros artefatos semânticos e publicação em conformidade com os padrões da Web Semântica.
---

### 4. Usuários

A ontologia é destinada a três perfis de usuários:
Pesquisadores acadêmicos das áreas de educação comparada, sociologia da educação e psiquiatria infantojuvenil, com interesse na caracterização formal do processo administrativo de registro da recusa escolar no Japão.
Gestores e técnicos de políticas educacionais com interesse no modelo institucional japonês de classificação e acompanhamento do recusa escolar, para fins de estudo e referência.
Especialistas em ontologias e engenharia do conhecimento que utilizarão o artefato como referência para desenvolvimento, alinhamento ou extensão de ontologias no domínio educacional.

---

### 5. Casos de Uso

CU01 — Consulta aos critérios de classificação de recusa escolar. Um pesquisador de educação necessita compreender quais critérios formais o MEXT adota para classificar um estudante com recusa escolar. A ontologia deve permitir a recuperação estruturada desses critérios, incluindo limiares quantitativos, exclusões categóricas e a tipologia dos motivos de ausência reconhecidos.
CU02 — Rastreamento do fluxo administrativo de registro. Um especialista em engenharia do conhecimento precisa mapear o caminho percorrido pela informação de ausência. A ontologia deve representar os agentes, os eventos e os instrumentos documentais envolvidos em cada etapa desse fluxo.
CU03 — Identificação e modelagem dos instrumentos de suporte do COCOLOプラン. Um pesquisador de políticas públicas necessita identificar quais instrumentos administrativos e de suporte foram instituídos pelo COCOLOプラン para estudantes com recusa escolar, como a Ficha de Suporte Individual (支援シート) e os Centros de Apoio Educacional (教育支援センター) e de que forma esses instrumentos se articulam com o processo de registro e acompanhamento do estudante.
CU04 — Pesquisa Comparativa de Modelos de Ausência Escolar. Um pesquisador interessado em educação comparada busca analisar como o modelo administrativo japonês do recusa escolar se relaciona ou se diferencia de outros sistemas internacionais de gestão de abandono ou recusa escolar. A ontologia deve atuar como um referencial semântico que permita identificar pontos de convergência e divergência entre o sistema do MEXT e frameworks educacionais de outros países, facilitando a transposição e o mapeamento de conceitos para estudos globais.

---

### 6. Requisitos Funcionais — Questões de Competência

CQ1: Quais critérios formais são necessários para classificar um estudante como recusa escolar?
CQ2: Quais motivos de ausência excluem a classificação de recusa escolar?
CQ3: Quais agentes administrativos registram as ausências escolares?
CQ4: Quais instrumentos documentais formalizam a transferência de informação?
CQ5: Quais processos administrativos contabilizam a frequência em estruturas externas?
CQ6: Quais eventos marcam as transições de estado?

---

### 7. Requisitos Não-Funcionais — Princípios FAIR

Findable: Todas as classes, propriedades e instâncias da ontologia receberão identificadores únicos e persistentes (URIs), acompanhados de metadados descritivos que incluam título, domínio, versão, data de criação. A ontologia será registrada em repositórios de ontologias reconhecidos, como o BioPortal ou o LOV.
Accessible: A ontologia será disponibilizada em formato OWL 2, acessível via protocolo HTTP/HTTPS padrão, sem restrição de autenticação para leitura.
Interoperable: A modelagem conceitual será por meio da OntoUML, garantindo compatibilidade com outros artefatos desenvolvidos sob o mesmo fundamento ontológico. Na camada OWL, serão utilizadas propriedades de alinhamento para articulação com vocabulários educacionais externos relevantes.
Reusable: A ontologia será publicada sob licença aberta, e sua estrutura modular permitirá que componentes específicos sejam reutilizados de forma independente.

---

### Glossary

| Termo na Ontologia (Classe)                                  | Termo Original (Japonês)  | Leitura (Romaji)                                         | Descrição / Contexto no MEXT                                                                                     |
| :----------------------------------------------------------- | :------------------------ | :------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------- |
| **Agentes e Atores (Agents & Roles)**                        |                           |                                                          |                                                                                                                  |
| `Student` / Estudante                                        | 児童生徒                      | *Jido Seito*                                             | Termo oficial para crianças e estudantes matriculados no sistema educacional.                                    |
| `FutokoStudent` / Estudante com Recusa Escolar               | 不登校児童生徒                   | *Futoko Jido Seito*                                      | Estudante ausente por 30 dias ou mais devido a fatores psicossociais, excluindo doenças ou razões financeiras.   |
| `Parent` / Responsável                                       | 保護者                       | *Hogosha*                                                | Pais ou responsáveis legais, cuja cooperação com a escola é exigida para a validação de presenças.               |
| `Teacher` / Professor Regente                                | 学級担任 / 教師                 | *Gakkyu Tannin / Kyoshi*                                 | O professor responsável pela turma, encarregado de monitorar os alunos e manter contato regular.                 |
| `Principal` / Diretor Escolar                                | 校長                        | *Kocho*                                                  | Autoridade máxima da escola que detém o poder de julgar e validar legalmente as faltas como presenças.           |
| `SchoolCounselor` / Conselheiro Escolar                      | スクールカウンセラー                | *School Counselor (SC)*                                  | Especialista em psicologia alocado nas escolas para oferecer apoio emocional aos alunos.                         |
| `SchoolSocialWorker` / Assistente Social Escolar             | スクールソーシャルワーカー             | *School Social Worker (SSW)*                             | Especialista em bem-estar e assistência social que conecta a família a serviços de apoio.                        |
| `TeamSchool` / Equipe Escolar                                | チーム学校                     | *Team Gakko*                                             | Abordagem colaborativa onde professores e especialistas (SC, SSW) atuam em conjunto para apoiar o aluno.         |
| `BoardOfEducation` / Comitê de Educação                      | 教育委員会                     | *Kyoiku Iinkai*                                          | Órgão governamental local (municipal/provincial) que gerencia centros de apoio e define diretrizes regionais.    |
| `MEXT` / Ministério da Educação                              | 文部科学省                     | *Monbukagakusho*                                         | O Ministério da Educação, Cultura, Esportes, Ciência e Tecnologia, autor do Plano COCOLO.                        |
| **Locais e Estruturas (Learning Environments)**              |                           |                                                          |                                                                                                                  |
| `RegularSchool` / Escola Regular                             | 在籍校                       | *Zaisekiko*                                              | A escola onde o aluno está oficialmente matriculado e para a qual os relatórios são enviados.                    |
| `InSchoolSupportRoom` / Centro de Apoio Interno              | 校内教育支援センター / スペシャルサポートルーム | *Konai Kyoiku Shien Center / Special Support Room*       | Sala vazia ou espaço seguro na própria escola para alunos que não conseguem entrar na sala de aula.              |
| `EducationSupportCenter` / Centro de Apoio Educacional       | 教育支援センター                  | *Kyoiku Shien Center*                                    | Instalação pública externa gerida pelo Comitê de Educação que oferece estudo e consultas.                        |
| `FreeSchool` / Escola Livre Privada                          | フリースクール / 民間施設            | *Free School / Minkan Shisetsu*                          | Instalações e organizações não-governamentais que acolhem alunos em situação de *Futoko*.                        |
| `HomeICTLearning` / Estudo em Casa via TIC                   | 自宅におけるICT等を活用した学習活動       | *Jitaku ni okeru ICT to o katsuyo shita gakushu katsudo* | Uso de terminais digitais, e-learning ou aulas online para estudar de casa.                                      |
| **Documentos e Instrumentos (Documents & Artifacts)**        |                           |                                                          |                                                                                                                  |
| `SupportSheet` / Ficha de Apoio ao Aluno                     | 児童生徒理解・支援シート              | *Jido Seito Rikai Shien Sheet*                           | Documento formal que registra o histórico, o plano de intervenção e os itens de repasse do aluno.                |
| `ShidoYoroku` / Histórico Escolar Oficial                    | 指導要録                      | *Shido Yoroku*                                           | O registro oficial do aluno onde as presenças validadas e avaliações são legalmente computadas.                  |
| `StudyPlan` / Plano de Estudos                               | 学習計画 / 学習プログラム            | *Gakushu Keikaku / Gakushu Program*                      | Planejamento alinhado ao currículo escolar regular que o aluno deve seguir nos centros de apoio ou em casa.      |
| `ActivityReport` / Relatório de Atividades                   | 活動報告 / 報告書                | *Katsudo Hokoku / Hokokusho*                             | Relatório enviado pelas instalações ou tutores à escola contendo dias de uso, conteúdo e reflexões.              |
| **Eventos e Conceitos Administrativos (Events & Processes)** |                           |                                                          |                                                                                                                  |
| `DigitalCheckup` / Observação de Saúde Mental                | 心の健康観察                    | *Kokoro no Kenko Kansatsu*                               | Uso diário de terminais digitais (1 para 1) para captar pequenos sinais de alerta (SOS) precocemente.            |
| `MultidisciplinaryConsultation` / Reunião de Caso            | スクリーニング会議 / ケース会議         | *Screening Kaigi / Case Kaigi*                           | Reunião da Equipe Escolar para analisar os alertas e definir a intervenção ideal.                                |
| `AttendanceValidation` / Validação de Presença               | 出席扱い                      | *Shusseki Atsukai*                                       | Processo legal onde a ausência do aluno em instalações alternativas ou TIC é oficialmente contada como presença. |
| `MedicalIllness` / Doença Médica (Exclusão)                  | 病気 / 身体的要因                | *Byoki / Shintaiteki Yoin*                               | Fatores médicos que excluem formalmente um aluno da definição administrativa de Futoko psicossocial.             |
| `EconomicReason` / Razão Econômica (Exclusão)                | 経済的理由 / 経済的要因             | *Keizaiteki Riyu / Keizaiteki Yoin*                      | Dificuldades financeiras que também excluem o aluno da classificação de Futoko psicossocial.                     |
