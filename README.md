# 📚 Repositório de Estudos: Carreiras Bancárias (BB, CAIXA & BNB)
> **Projeto de Preparação do Zero Absoluto em Concursos Públicos Bancários**  
> *Caderno Temático Mapeado via NotebookLM / Gemini Notebook*

---

## 🎯 1. Contexto e Objetivos

### **Contexto do Projeto**
Este repositório reúne o mapeamento completo, resumos estruturados, plano de estudo focado e engenharia de prompts desenvolvida para a preparação de alto rendimento para concursos de carreiras bancárias — com foco nos editais do **Banco do Brasil (BB)**, **Caixa Econômica Federal (CEF)** e **Banco do Nordeste (BNB)**, organizados predominantemente pela **Fundação Cesgranrio**.

### **Ponto de Partida e Desafios**
- **Perfil do Estudante:** Retorno aos estudos após mais de **10 anos longe da escola**, começando do **zero absoluto**.
- **Maior Obstáculo:** Dificuldade acentuada em **Matemática (Básica e Financeira)** e ansiedade frente a fórmulas abstratas.
- **Disponibilidade:** Rotina fixa de **14 horas semanais (2 horas por dia, 7 dias por semana)**.

### **Objetivos Principais**
1. **Superar a Defasagem em Matemática:** Construir uma base sólida através de uma progressão pedagógica acumulativa ("Escada do Aprendizado"), sem decorreba e com foco na compreensão intuitiva.
2. **Dominar o Tronco Específico Bancário:** Compreender a estrutura do Sistema Financeiro Nacional (SFN), Vendas e Negociação, Informática e Português.
3. **Consolidar um Sistema de Revisão Ativa:** Implementar rotinas diárias de 15 minutos de exercícios e simulados periódicos estilo Cesgranrio.

---

## 📚 2. Curadoria de Fontes (Caderno Temático)

Foram selecionadas e analisadas **5 fontes estratégicas em texto e PDF** integradas ao ecossistema de estudo:

1. 📄 **Análise Estratégica de Conteúdos Programáticos e Mapeamento Integrado para Concursos Bancários e Fiscais (BB, CAIXA, BNB, SEFAZ-CE)**  
   *Descrição:* Mapeamento de relevância de tópicos, peso de disciplinas e interseção entre os editais bancários.
2. 🔗 **Concurso Banco do Brasil - Escriturário: Agente Comercial (Pré-edital) | Gran Cursos Online**  
   *Descrição:* Estrutura detalhada do edital, distribuição de questões por matéria e atribuições do cargo.
3. 🔗 **Apostila CAIXA 2026 - Técnico Bancário Novo**  
   *Descrição:* Conteúdo programático voltado para a Caixa Econômica Federal, incluindo programas sociais, habitação e matemática financeira.
4. 🔗 **Concurso BNB: Edital Publicado e Oportunidades - Apostila Opção**  
   *Descrição:* Detalhamento das rotinas do Banco do Nordeste, legislações específicas (FNE) e estrutura da prova sem redação.
5. 📄 **FNE – Fundo Constitucional de Financiamento do Nordeste (Relatório de Gestão - BNB)**  
   *Descrição:* Documentação oficial sobre a operação do FNE, microcrédito (*Crediamigo* / *Agroamigo*) e desenvolvimento regional.

---

## 🛠️ 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Para extrair o máximo valor da Inteligência Artificial como mentora pedagógica, foram testadas diferentes abordagens de prompts. Abaixo está o registro das perguntas estratégicas, refinamentos e lições aprendidas durante o processo.

### **Prompts Testados e Evolução da Interação**

#### 🔹 **Prompt 1: Definição de Papel e Cronograma Inicial**
> *"Atue como um mentor de concursos públicos especialista nas carreiras bancárias (BNB, Caixa e BB). Estou começando do zero absoluto e tenho muita dificuldade em Matemática. Disponho de 2 horas por dia, 7 dias por semana (14h semanais). Crie um plano de estudos estruturado..."*
* **Resultado Obtido:** A IA entregou um ciclo semanal equilibrado em formato de tabela, limitando a matemática a 1h diária e combinando com disciplinas complementares.
* **Aprendizado/Limitação:** A tabela inicial trouxe a sequência de tópicos, mas ainda faltava o aprofundamento na explicação passo a passo da matemática para quem está há 10 anos sem estudar.

#### 🔹 **Prompt 2: Mudança de Tom para Didática do Zero Absoluto**
> *"Gostaria de algo mais didático e explicativo, principalmente com matemática..."*
* **Resultado Obtido:** A IA reformulou a abordagem criando a **"Escada do Aprendizado" em 6 Degraus**, demonstrando a dependência estrita entre frações, proporção, porcentagem, juros simples, juros compostos e amortização.

#### 🔹 **Prompt 3: Desconstrução da Lógica da Fator (O "Pulo do Gato")**
> *"Preciso que você faça sempre bem explicativo como se eu estivesse vendo isso pela primeira vez, pois já saí da escola há mais de 10 anos... [Exemplo do Fator de Aumento 1 = 100%]"*
* **Resultado Obtido:** A IA validou e expandiu a intuição do número `1` como âncora de `100%`, explicando os fatores de aumento `(1 + i)` e de desconto `(1 - i)` e derivando a fórmula de alterações sucessivas: `Valor Final = Valor Inicial × (Fator 1) × (Fator 2)`.

#### 🔹 **Prompt 4: Teste Prático e Mini-Simulado**
> *"Crie um mini-simulado com 5 questões inéditas no estilo Cesgranrio sobre o Sistema Financeiro Nacional..."*
* **Resultado Obtido:** Simulado em formato de múltipla escolha (A a E) com gabarito comentado passo a passo, permitindo avaliar o rendimento imediato (60% de acertos no primeiro teste).

---

### 🧱 **Troubleshooting e "Cicatrizes" do Processo**

| Dificuldade Encontrada | Causa Raiz | Solução / Ajuste no Prompt |
| :--- | :--- | :--- |
| **Bloqueio com Fórmulas Abstratas** | Anos afastado da linguagem matemática acadêmica. | Solicitar à IA que **elimine termos técnicos sem explicação prévia** e substitua por **analogias do dia a dia** (ex: pizza para frações, balança para proporção, aluguel para juros). |
| **Confusão em Porcentagens Sucessivas** | Tendência a somar/subtrair percentuais diretamente (+20% - 20% = 0%). | Exigir a demonstração do **caminho longo (duas contas)** lado a lado com o **caminho rápido (fatores)** para visualizar a mudança da base de cálculo. |
| **Saturação Mental em Exatas** | Tentar estudar várias horas seguidas da mesma matéria difícil. | Travar o tempo máximo de matemática em **1 hora por sessão**, antecedida por 15 minutos de **revisão ativa com 3 a 5 exercícios simples**. |

---

## 📖 4. Miniguia de Estudo (Entrega Final)

### **A. Resumos Estruturados do Assunto**

#### 📐 **1. Matemática em Degraus (Do Zero ao Avançado)**
* **Degrau 1 (Base):** Operações com Decimais e Frações. *(Toda fração é uma divisão: $2/5 = 0,40 = 40\%$)*.
* **Degrau 2 (Proporção):** Regra de Três Simples e Composta. *(Relações diretas vs. inversas)*.
* **Degrau 3 (Porcentagem & Fatores):**
  * Aumento de $x\% \rightarrow$ Multiplica por $(1 + i)$.
  * Desconto de $x\% \rightarrow$ Multiplica por $(1 - i)$.
  * Alterações Sucessivas: $\text{Valor Final} = \text{Valor Inicial} \times (F1) \times (F2)$.
* **Degrau 4 (Juros Simples):** Incidem apenas sobre o capital inicial ($J = C \cdot i \cdot t$).
* **Degrau 5 (Juros Compostos):** Juros sobre juros ($M = C \cdot (1 + i)^n$).
* **Degrau 6 (Sistemas de Amortização):**
  * **SAC:** Amortização constante, juros e parcelas decrescentes.
  * **Tabela Price:** Prestação fixa do início ao fim do contrato.

#### 🏛️ **2. Conhecimentos Bancários & Sistema Financeiro Nacional (SFN)**
* **Órgãos Normativos (Regras):** Conselho Monetário Nacional (CMN) — órgão máximo deliberativo.
* **Entidades Supervisoras (Fiscalização):**
  * **BACEN:** Executa a política monetária, controla a inflação (Selic), emite moeda e fiscaliza bancos.
  * **CVM:** Fiscaliza o mercado de valores mobiliários (ações e debêntures).
* **4 Mercados Financeiros:** Monetário (liquidez de curto prazo), Crédito (empréstimos/financiamentos), Capitais (ações/debentures) e Câmbio (moedas estrangeiras).

#### 💻 **3. Informática para Agente Comercial**
* **Foco Principal:** Usuário final e ferramentas corporativas.
* **Tópicos de Alto Peso:** Excel (fórmulas `SE`, `PROCV`, `PROCX`, tabelas dinâmicas), Segurança da Informação (malwares, *phishing*, criptografia, *backup*), Navegadores (Edge/Firefox) e Ambientes Windows 10/11 e Linux.

#### 🤝 **4. Vendas e Negociação**
* **Técnicas de Venda:** Venda Consultiva vs. Venda Cruzada (*Cross-selling*).
* **Negociação:** Distributiva (soma zero / ganha-perde) vs. Integrativa (ganha-ganha).
* **Legislação & CX:** Responsabilidade Objetiva do Banco no Código de Defesa do Consumidor (CDC) e princípios ESG.

---

### 📖 **B. Glossário de Conceitos-Chave**

* **Fator de Multiplicação:** Número decimal utilizado como atalho para aplicar aumentos $(1+i)$ ou descontos $(1-i)$ em uma única operação.
* **SFN (Sistema Financeiro Nacional):** Conjunto de instituições que intermedeia o fluxo de recursos entre poupadores e tomadores de empréstimo.
* **CMN (Conselho Monetário Nacional):** Órgão normativo supremo do sistema financeiro brasileiro; define diretrizes e metas de inflação.
* **BACEN (Banco Central do Brasil):** Autarquia responsável por executar as políticas do CMN, emitir moeda e supervisionar as instituições bancárias.
* **Tabela Price vs. SAC:** Modelos de amortização de empréstimos. A Price possui parcelas iguais; o SAC possui amortização constante e parcelas decrescentes.
* **Venda Cruzada (*Cross-selling*):** Técnica comercial bancária que consiste em oferecer produtos complementares (ex: seguro ou cartão) no momento do atendimento.
* **Responsabilidade Objetiva:** Princípio do CDC segundo o qual o banco responde pelos danos e fraudes causados aos clientes independentemente de comprovação de culpa da instituição.

---

### 🔄 **C. Prompts Reutilizáveis para Futuras Revisões**

Copie e cole estes prompts para dar continuidade aos seus estudos no NotebookLM / Gemini:

#### 📌 **Prompt 1: Exposição Conceitual do Zero Absoluto**
```text
Atue como meu mentor de concursos bancários. Explique o tópico [INSERIR TÓPICO, ex: Tabela Price vs SAC] como se eu estivesse vendo pela primeira vez e estivesse há mais de 10 anos sem estudar. Utilize analogias do cotidiano, desconstrua cada letra das fórmulas e mostre um exemplo prático resolvido passo a passo pelo caminho longo e pelo caminho curto.
```

#### 📌 **Prompt 2: Gerador de Questões Estilo Cesgranrio**
```text
Com base no meu material de estudo, elabore 5 questões inéditas de múltipla escolha (A a E) sobre [INSERIR MATÉRIA, ex: Segurança da Informação / Malwares] no estilo da Fundação Cesgranrio. Apresente primeiro apenas as questões. Após a minha resposta, forneça o gabarito detalhado com a justificativa de cada alternativa.
```

#### 📌 **Prompt 3: Folha de Revisão Ativa de 15 Minutos**
```text
Crie uma folha de exercícios de fixação rápida para os primeiros 15 minutos do meu bloco de estudo de [INSERIR MATÉRIA]. Inclua 3 a 5 exercícios diretos focado nas fórmulas/conceitos estudados ontem sobre [INSERIR TÓPICO ANTERIOR, ex: Juros Simples], para testar minha retenção sem consulta.
```

---

## 🛠️ Como Utilizar Este Repositório
1. Importe os arquivos da pasta `/fontes` para o seu **NotebookLM / Gemini Notebook**.
2. Utilize a estrutura da **Escada do Aprendizado** para guiar suas leituras diárias de 2 horas.
3. Utilize os **Prompts Reutilizáveis** da Seção 4 para gerar novos simulados e resumos conforme avançar no edital.
