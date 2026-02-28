
# FIRST SECTION: CHATGPT

# ✅ COMPLETE STEP-BY-STEP GUIDE

## How to Prompt an AI Agent to Fully Create Your Software Using Spec-Driven Development

This methodology has **two major blocks**:

1. 🧠 Product Definition (3 Phases → 5 Documents)
2. 🏛 Governance & Non-Negotiable Rules (Constitution)

You must follow the correct order.

---

# 🔵 PART 1 — PRODUCT SPECIFICATION FLOW

This follows the structure defined in .

---

# STEP 1 — START WITH A RAW IDEA

### Your First Prompt to the Agent

You must provide:

* The problem
* Who has the problem
* A rough idea of the solution (optional)
* Context (why now?)

### Example Prompt Structure

```
I want to build a [type of product].

The problem is:
[describe the pain clearly]

The target user is:
[who exactly]

Today they solve this by:
[current solution]

I believe this is bad because:
[why it's inefficient or painful]
```

⚠️ Do NOT jump to features yet.

The agent will enter:

## 📍 PHASE 1: DISCOVERY

---

# STEP 2 — DISCOVERY (You Must Answer Deeply)

The agent will ask 3–4 questions at a time about:

### A. The Problem

You must clarify:

* Is the pain frequent or occasional?
* Is it urgent?
* Is it expensive?
* Is it emotional or operational?

### B. The User

You must define:

* Exact profile (job, age, company size if B2B)
* Job-to-be-done
* Desired transformation
* Why they would adopt/pay

### C. The Business

You must clarify:

* Product vs feature vs internal tool
* Monetization model
* Differentiator
* Timeline expectations

You must answer precisely and honestly.

When the agent says:

> “Ok, I understand. I’ll move to validation.”

You move to Phase 2.

---

# STEP 3 — VALIDATION

Now the agent challenges your idea.

You must be ready to define:

### 1️⃣ Realistic MVP Scope

You must answer:

* What absolutely MUST exist?
* What can wait?
* What is nice-to-have?

### 2️⃣ Hypotheses

Define assumptions like:

* Users will sign up without friction
* Users will pay $X
* Users care about feature Y

### 3️⃣ Success Criteria

Define measurable metrics:

* 100 users in 30 days
* 10% conversion
* 50 weekly active users

Without metrics → no validation.

When the agent says:

> “MVP defined. I’ll generate the documents.”

You move to Phase 3.

---

# STEP 4 — SPECIFICATION SUMMARY APPROVAL

Before documents are generated, the agent must provide:

* Summary of BRIEF
* Summary of PRD
* Summary of MVP scope
* Summary of landing structure
* Summary of design guidelines

You must:

* Confirm alignment
* Adjust anything unclear
* Approve explicitly

Only after approval:

Documents are generated.

---

# STEP 5 — DOCUMENTS YOU MUST REVIEW

The AI will generate:

### 1️⃣ BRIEF.md

You must verify:

* One-sentence problem
* Clear audience
* Clear advantage
* Defined metrics

### 2️⃣ PRD.md

You must check:

* All user stories realistic
* Functional requirements complete
* Non-functional requirements defined
* Supabase usage clear
* Acceptance criteria testable

### 3️⃣ MVP-SCOPE.md

Ensure:

* No feature creep
* Clear priorities (must/should/could)
* Explicit exclusions

### 4️⃣ LANDING-PAGE-SPEC.md

Ensure:

* Only structure (no copy)
* Clear section objective
* Clear CTA hierarchy

### 5️⃣ DESIGN-GUIDELINES.md

Ensure:

* Hex colors defined
* Typography defined
* Spacing system defined
* shadcn usage consistent

---

# 🟣 PART 2 — CONSTITUTION CREATION

Now comes the governance layer.

This is based on  and the Constitution command logic.

You now execute:

```
/speckit.constitution
```

But before that, you must provide ALL constitutional inputs.

---

# STEP 6 — DEFINE CORE PRINCIPLES (MANDATORY)

The template requires:

```
[PROJECT_NAME]
[PRINCIPLE_1_NAME]
[PRINCIPLE_1_DESCRIPTION]
...
[PRINCIPLE_5_NAME]
...
```

You must define:

### Principle Format

For each principle:

* Name (short, strong)
* Non-negotiable rule (MUST statements)
* Rationale

### Examples of What You Must Decide

* Is TDD mandatory?
* Is integration testing mandatory?
* Is semantic versioning required?
* Are breaking changes allowed?
* Is structured logging mandatory?
* Is observability required?
* Is simplicity prioritized over extensibility?
* Is CLI exposure required?
* Is library-first architecture required?

Be explicit.

Avoid vague wording like “should”.

---

# STEP 7 — DEFINE ADDITIONAL SECTIONS

Template includes:

```
## [SECTION_2_NAME]
[SECTION_2_CONTENT]

## [SECTION_3_NAME]
[SECTION_3_CONTENT]
```

You must define:

### Section 2 (Examples)

* Security Requirements
* Performance Standards
* Compliance (LGPD/GDPR)
* Deployment constraints
* Tech stack enforcement

### Section 3 (Examples)

* Code review rules
* CI/CD requirements
* Quality gates
* Definition of Done
* Testing thresholds
* Release approval process

---

# STEP 8 — DEFINE GOVERNANCE RULES

You must define:

* How the constitution is amended
* Who approves amendments
* Versioning rules (semantic versioning)
* Migration requirements
* Compliance enforcement
* How conflicts are resolved

Also define:

* RATIFICATION_DATE
* Version (start at 1.0.0 if first)
* LAST_AMENDED_DATE

---

# STEP 9 — VERSIONING LOGIC

The agent must decide version bump type:

* MAJOR → breaking governance change
* MINOR → new principle added
* PATCH → wording refinement

You must understand this before approving updates.

---

# STEP 10 — CONSISTENCY PROPAGATION

The constitution command requires:

* Updating plan templates
* Updating spec templates
* Updating task templates
* Updating command references
* Updating runtime documentation

You must confirm propagation occurred.

---

# 🔷 COMPLETE ORDER YOU MUST FOLLOW

Here is the definitive sequence:

1. Provide raw idea
2. Answer Discovery questions
3. Define MVP during Validation
4. Approve specification summary
5. Approve generated documents
6. Define constitutional principles
7. Define governance rules
8. Execute /speckit.constitution
9. Approve version bump
10. Confirm sync propagation

Only after that:

The AI can implement via:

```
speckit.specify
```

---

# 🎯 MASTER CHECKLIST (COPY & USE)

Before starting, prepare answers for:

### Product

* Problem
* User
* Current solution
* Pain cost
* Business model
* Differentiator
* Timeline

### MVP

* Core features
* Exclusions
* Hypotheses
* Success metrics

### Architecture Constraints

* Security needs
* Compliance
* Performance
* Scalability

### Constitution

* 5+ non-negotiable principles
* Development workflow rules
* Testing policy
* Versioning rules
* Governance process
* Amendment process

---

# 🚀 FINAL RESULT

If you follow this strictly:

The AI agent will be able to:

* Fully specify your product
* Define MVP precisely
* Generate implementation-ready documentation
* Define governance
* Enforce long-term architectural consistency
* Enable autonomous feature implementation safely

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

# SECOND SECTION

Esta é uma estratégia de implementação de software baseada em **Spec-Driven Development**. O objetivo é separar a **visão de produto** (o que e por que) da **governança técnica** (como e quais os princípios).

Abaixo, apresento o guia definitivo para você executar esse processo passo a passo, em Português.

---

# Guia de Implementação: Spec-Driven Development

Este guia descreve a ordem lógica de interação com os agentes de IA. Siga esta sequência para garantir que todos os documentos sejam gerados com precisão.

## 🛠 Pré-requisitos

O seu ambiente de desenvolvimento deve estar configurado para trabalhar com:

* **Stack:** Next.js + Supabase.
* **Design:** shadcn/ui (estilo limpo, moderno, light mode).
* **Arquitetura:** Client-side first, minimal server-side.

---

## 📍 Passo 1: Product Discovery (O "O Quê" e o "Porquê")

Nesta fase, você interage com o **Product Discovery Assistant**. Não mencione detalhes técnicos ainda; foque em entender o valor de negócio.

### Ação

Inicie uma nova sessão com o agente e envie a sua "ideia bruta".

**Prompt de Inicialização:**

> "Sou o [Seu Nome]. Tenho uma ideia de software: [DESCREVA A IDEIA BEM CRUA]. Quero passar pelo processo de Product Discovery para transformar isso em um MVP documentado."

### O que você deve fornecer (quando o agente perguntar):

Durante a Fase 1 e 2, o agente fará perguntas. Você deve ter clareza sobre:

1. **Problema:** Qual dor real você resolve? Como as pessoas resolvem isso hoje?
2. **Usuário:** Quem é o público-alvo exato?
3. **Negócio:** Qual é o diferencial? Por que usar o seu sistema?
4. **MVP:** Esteja pronto para aceitar críticas. Se o agente disser que algo é "viável demais" ou "muito complexo", defina junto com ele o que deve ser cortado.

**✅ Saída esperada:** Ao final da Fase 3, você terá os documentos: `BRIEF.md`, `PRD.md`, `MVP-SCOPE.md`, `LANDING-PAGE-SPEC.md`, `DESIGN-GUIDELINES.md`. **Salve estes arquivos.**

---

## 📍 Passo 2: A Constituição do Projeto (O "Como")

Após o produto estar validado, é hora de "congelar" as regras técnicas. Aqui você usa o **SpecKit Constitution**.

### Ação

Você precisa popular o arquivo `.specify/memory/constitution.md` usando o template fornecido.

**Informações que você deve preparar:**

1. **Princípios Core (3-5 princípios):** Defina regras que ninguém pode quebrar.
* *Exemplo:* "Test-First (TDD obrigatório)", "Observabilidade como prioridade", "Interface via CLI".


2. **Restrições Técnicas:** (Next.js, Supabase, shadcn/ui).
3. **Workflow:** Como serão os Code Reviews? Quais são os quality gates (ex: testes passando, linting)?
4. **Governança:** Como a constituição é alterada? Quem aprova?

**Prompt para o Agente de Constituição:**

> "Preciso criar a constituição inicial do meu projeto '[NOME_DO_PROJETO]'.
> Aqui estão meus princípios:
> 1. [PRINCIPIO_1]
> 2. [PRINCIPIO_2]
> 3. [PRINCIPIO_3]
> 
> 
> As restrições técnicas são: [STACK]. O workflow de desenvolvimento exige [REGRAS].
> Por favor, preencha o `constitution-template.md` com essas informações e gere o arquivo `constitution.md`."

---

## 📍 Passo 3: Especificação Final (O "Build")

Agora que você tem o **PRD** (Produto) e a **Constitution** (Técnica), você pode gerar as tarefas de implementação.

### Ação

Utilize o agente `speckit.specify` para transformar a documentação em tarefas técnicas.

**Prompt de Handoff:**

> "Com base no `PRD.md` gerado no Discovery e na `constitution.md` ratificada, quero começar a especificação de construção. Implemente a especificação do recurso [NOME_DO_RECURSO]. Considere as restrições da constituição."

---

## 📋 Checklist de Informações para o Programador

Para que a IA tenha sucesso, **não tente adivinhar**. Tenha estas respostas prontas antes de começar cada fase:

| Fase | Informação Necessária | Por que é necessária? |
| --- | --- | --- |
| **Discovery** | Problema, Público, Solução, Diferencial | Define o escopo funcional do sistema. |
| **Validation** | Riscos, MVP vs Futuro, Métricas | Evita o desperdício de tempo em funcionalidades inúteis. |
| **Constitution** | Princípios, Regras de Review, Stack | Garante a qualidade técnica e sustentabilidade do código. |
| **Specification** | User Stories, Requisitos Funcionais | É o "mapa" que o agente de código seguirá para criar os arquivos. |

---

### Resumo da Ordem de Execução

1. **Inicie com o Product Discovery Assistant** (Itere até ter os 5 documentos gerados).
2. **Valide o MVP** com o Assistente de Discovery.
3. **Execute o comando de Constitution** para criar as regras técnicas definitivas no arquivo `.specify/memory/constitution.md`.
4. **Chame o `speckit.specify**` passando os documentos de Produto + os Princípios da Constituição para começar a gerar as especificações técnicas de código.

**Dica de ouro:** Nunca pule a fase de "Validação" do Product Discovery. É nela que você economiza semanas de trabalho de desenvolvimento ao perceber que uma funcionalidade não é necessária para o MVP.

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

# THIRD SECTION

## 🧭 Passo a passo detalhado

### **1. Ideia inicial (entrada crua)**
- Forneça uma frase ou parágrafo curto com a ideia do software.  
- Exemplo: *“Quero um app para organizar tarefas de equipe com foco em simplicidade.”*  

👉 Esse é o ponto de partida para o agente iniciar o fluxo.

---

### **2. Fase Discovery (entender problema, usuário e contexto)**
O agente vai te perguntar até 3 coisas por vez, mas você já pode adiantar:  
- **Problema/dor real** que o software resolve.  
- **Usuário alvo** (perfil exato).  
- **Como fazem isso hoje** e por que é ruim.  

👉 Quando isso estiver claro, o agente passa para a validação.

---

### **3. Fase Validação (definir MVP realista)**
Aqui você precisa detalhar:  
- **Riscos e pontos fracos** da ideia.  
- **O que é essencial (MVP)** vs. o que é “viagem”.  
- **Hipóteses que precisam ser testadas**.  
- **Critérios de sucesso** (como saber se deu certo).  

👉 Quando o MVP estiver fechado, o agente gera os documentos.

---

### **4. Fase Especificação (gerar documentação completa)**
Com base no MVP, o agente gera 5 documentos. Para isso, você deve fornecer:  

1. **Visão geral do produto**.  
2. **Personas e user stories**.  
3. **Requisitos funcionais e não-funcionais**.  
4. **Integrações necessárias (ex: Supabase)**.  
5. **Edge cases** e critérios de aceitação.  
6. **Landing page**: estrutura de seções e objetivos.  
7. **Design guidelines**: paleta, tipografia, estilo visual.  

👉 O agente então gera:  
- **BRIEF.md**  
- **PRD.md**  
- **MVP-SCOPE.md**  
- **LANDING-PAGE-SPEC.md**  
- **DESIGN-GUIDELINES.md**

---

### **5. Constitution (regras não negociáveis do projeto)**
Esse documento é criado a partir do `constitution-template.md` via comando `/speckit.constitution`.  
Você precisa fornecer:  
- **Nome do projeto**.  
- **Princípios centrais** (ex: Library-first, CLI interface, Test-first, etc.).  
- **Seções adicionais** (ex: segurança, performance, workflow).  
- **Governança** (como emendar, aprovar, revisar).  
- **Datas**: ratificação inicial e última emenda.  
- **Versão**: incrementada conforme mudanças (major/minor/patch).  

👉 Esse arquivo garante consistência e governança em todo o projeto.

---

## 📋 Ordem recomendada dos prompts

1. **Prompt 1:** Ideia inicial (uma frase).  
2. **Prompt 2:** Problema, usuário e contexto (Discovery).  
3. **Prompt 3:** Riscos, MVP, hipóteses e critérios de sucesso (Validação).  
4. **Prompt 4:** Detalhes para especificação (Visão geral, personas, requisitos, landing page, design).  
5. **Prompt 5:** Constitution (nome do projeto, princípios, seções adicionais, governança, datas e versão).  

---

## ✅ Checklist prático para preencher

1. Ideia inicial: __________  
2. Problema/dor: __________  
3. Usuário alvo: __________  
4. Como fazem hoje e por que é ruim: __________  
5. Riscos/pontos fracos: __________  
6. MVP (essencial): __________  
7. Hipóteses a validar: __________  
8. Critérios de sucesso: __________  
9. Visão geral do produto: __________  
10. Personas: __________  
11. User stories: __________  
12. Requisitos funcionais: __________  
13. Requisitos não-funcionais: __________  
14. Integrações Supabase: __________  
15. Edge cases: __________  
16. Critérios de aceitação: __________  
17. Landing page (seções e objetivos): __________  
18. Design guidelines (paleta, tipografia, estilo): __________  
19. Nome do projeto (constitution): __________  
20. Princípios centrais: __________  
21. Seções adicionais: __________  
22. Governança: __________  
23. Datas (ratificação / última emenda): __________  
24. Versão: __________  

---

## 🇧🇷 Tradução final em português

Esse guia mostra **tudo o que você precisa descrever e em qual ordem**, para que o agente de IA consiga especificar e detalhar o software de ponta a ponta.  

👉 Resumindo:  
1. Comece com a **ideia bruta**.  
2. Detalhe **problema, usuário e contexto**.  
3. Defina **MVP, riscos e sucesso**.  
4. Forneça insumos para a **especificação completa** (docs).  
5. Finalize com a **Constitution** (regras não negociáveis).  

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

# FOURTH SECTION

O fluxo completo é: **Ideia Bruta → Discovery → Validação → Especificação (5 documentos) → Constituição (regras) → Pronto para Implementação.**

---

## Guia Passo a Passo: Do Prompt Inicial à Especificação Completa

Aqui está o guia detalhado de tudo o que você precisa fornecer, na ordem correta, para que o agente de IA consiga especificar completamente o software.

### **Pré-requisito: Tenha sua Ideia Central em Mentes**

Antes de começar, você precisa ter clara a sua ideia inicial. Pode ser algo simples, como uma frase. Exemplos:
- *"Quero um app para organizar as finanças da casa, mas que seja super simples e automático."*
- *"Preciso de uma ferramenta interna para minha equipe de suporte gerenciar tickets."*
- *"Quero criar um SaaS que ajude freelancers a criar propostas comerciais bonitas e rápidas."*

---

### **PASSO 1: Inicie a Conversa com o Agente Discovery**

**O que fazer:**
Envie a mensagem inicial para o agente. Como o guia do agente (`PROJECT-INSTRUCTIONS.md`) já define uma mensagem inicial padrão, você pode simplesmente iniciar o chat com a sua ideia.

**Prompt sugerido para você enviar:**
> "Olá! Quero criar um software. Minha ideia é: **[INSIRA SUA IDEIA AQUI]**."

**Exemplo real:**
> "Olá! Quero criar um software. Minha ideia é: um aplicativo para ajudar pequenas empresas a gerenciar suas assinaturas (SaaS, softwares, etc.) e evitar gastos esquecidos."

---

### **PASSO 2: Responda às Perguntas da FASE 1 - DISCOVERY**

**O que vai acontecer:**
O agente (seguindo o `PROJECT-INSTRUCTIONS.md`) vai entrar na **FASE 1: DISCOVERY** e fará de 3 a 4 perguntas para entender o problema.

**O que você precisa fornecer (prepare as respostas para estas perguntas):**
- **O problema específico:** Qual é a dor exata? ("Pequenas empresas perdem dinheiro porque esquecem de cancelar assinaturas não usadas ou nem sabem quais têm.")
- **Como você sabe que o problema existe?** ("Já vi acontecer com amigos que têm negócios e com meu próprio contador.")
- **Como resolvem hoje?** ("Planilhas manuais, lembretes no celular, ou simplesmente não resolvem e aceitam o prejuízo.")
- **Custo de não resolver:** ("Perda financeira direta, falta de controle, estresse na hora de fechar as contas.")
- **Quem é o usuário exato?** ("O dono da pequena empresa, ou um assistente administrativo que cuida das contas.")
- **Qual o "job to be done"?** ("Quero ter uma visão única de todos os meus gastos recorrentes e ser avisado antes de uma cobrança indesejada.")
- **Modelo de negócio?** ("SaaS, com assinatura mensal. Talvez um modelo freemium bem limitado.")
- **Diferencial?** ("Foco extremo na simplicidade e em detectar assinaturas 'perdidas' ou não utilizadas, não apenas listá-las.")

Seja o mais honesto e direto possível. Se não souber algo, diga "não sei" ou "é uma suposição".

---

### **PASSO 3: Participe da FASE 2 - VALIDAÇÃO**

**O que vai acontecer:**
Quando o agente entender o problema, ele dirá *"Ok, entendi. Vou pra validação"* e iniciará a **FASE 2: VALIDAÇÃO**. Ele vai apontar riscos e sugerir cortes para definir o MVP.

**O que você precisa fazer:**
- **Ouça os riscos:** O agente pode dizer: *"Gerenciar assinaturas automaticamente é complexo. Como vai detectar uma assinatura não usada sem integração bancária?"*
- **Negocie o escopo:** Você precisará decidir o que é realmente essencial para a versão 1. O agente vai sugerir simplificações.
- **Defina o MVP:** Ao final, vocês terão uma lista do que **deve** entrar na primeira versão.
    - **Exemplo de MVP:** "Cadastro manual de assinaturas pelo usuário + Alertas baseados em data + Dashboard simples."
    - **Exemplo de (NÃO MVP/Futuro):** "Detecção automática via extrato bancário + Cancelamento automático + Relatórios avançados."
- **Defina o Critério de Sucesso:** Como saber se o MVP deu certo? ("Usuário consegue cadastrar 5 assinaturas em menos de 2 minutos" ou "Redução de 30% nos gastos com assinaturas esquecidas para usuários ativos").

**O agente só passará para a próxima fase quando você concordar com o MVP definido.**

---

### **PASSO 4: Revise o Resumo e Autorize a Geração dos Documentos**

**O que vai acontecer:**
O agente dirá *"MVP definido. Vou gerar os documentos."* e entrará na **FASE 3: ESPECIFICAÇÃO**. Primeiro, ele vai gerar um **resumo** do que vai colocar em cada um dos 5 documentos e perguntará se você concorda ou quer ajustar algo.

**O que você precisa fazer:**
- Leia o resumo com atenção.
- Se algo estiver errado ou faltando, peça ajustes agora. Ex: *"No PRD, não se esqueça de incluir a integração com o Supabase para autenticação."*
- Quando estiver satisfeito, autorize a geração. Ex: *"Pode gerar os documentos completos."*

---

### **PASSO 5: Receba os 5 Documentos Gerados**

**O que vai acontecer:**
Após sua autorização, o agente gerará os 5 documentos completos e prontos para uso: `BRIEF.md`, `PRD.md`, `MVP-SCOPE.md`, `LANDING-PAGE-SPEC.md`, `DESIGN-GUIDELINES.md`.

**O que você precisa fazer:**
- Salve todos os documentos. Eles agora são a base para a próxima etapa (a constituição) e para o desenvolvimento.
- Você pode, opcionalmente, ler cada um e sugerir pequenas correções se necessário.

---

### **PASSO 6: Inicie o Comando `/speckit.constitution`**

**O que vai acontecer:**
Agora que você tem a especificação completa, é hora de criar as regras não negociáveis do projeto. Você usará o comando `/speckit.constitution`. O agente (agora atuando como o comando do GitHub Spec-kit) vai precisar de informações para preencher o `constitution-template.md`.

**O que você precisa fornecer (neste prompt):**
Você deve chamar o comando e, se possível, já fornecer algumas informações. O comando pode ser usado interativamente. Um prompt de exemplo seria:

> `/speckit.constitution Precisamos criar a constituição para o projeto 'Assinatura Gestor'. Com base nos documentos gerados (PRD, etc.), preencha o template. O nome do projeto é 'Assinatura Gestor'. As regras devem refletir nosso foco em simplicidade, segurança (por lidar com dados financeiros) e a stack Next.js/Supabase. A data de ratificação é hoje, 2026-02-28.`

---

### **PASSO 7: Responda às Perguntas do `/speckit.constitution` (se houver)**

**O que vai acontecer:**
O agente (`speckit.constitution`) vai analisar o template, seu repositório e os documentos gerados. Ele pode fazer perguntas para esclarecer os placeholders do template, especialmente os **5 princípios** e as **seções adicionais**.

**O que você precisa fornecer (prepare-se para responder sobre):**

- **PRINCÍPIOS:** O template tem placeholders para 5 princípios. Você precisará defini-los com a ajuda do agente, baseado no `PRD.md` e `MVP-SCOPE.md`. Exemplos:
    1.  **Princípio 1: "Segurança por Padrão"** (Descrição: "Toda transação e dado do usuário devem ser tratados com criptografia em repouso e trânsito. Autenticação obrigatória via Supabase Auth.")
    2.  **Princípio 2: "Simplicidade Radical"** (Descrição: "A interface deve ser limpa, com o mínimo de passos para qualquer ação. Qualquer fluxo com mais de 3 cliques deve ser justificado.")
    3.  **Princípio 3: "Testes Críticos Obrigatórios"** (Descrição: "Toda regra de negócio relacionada a cálculo de gastos e alertas deve ter testes automatizados. TDD é recomendado, mas não obrigatório.")
    4.  **Princípio 4: "Mobile-First"** (Descrição: "Como muitos donos de pequenas empresas usam o celular, toda interface deve ser desenvolvida e testada primeiro em mobile (responsividade).")
    5.  **Princípio 5: "Rastreabilidade"** (Descrição: "Toda ação que modifica uma assinatura (criar, editar, cancelar) deve ser logada para auditoria futura, mesmo que em um log simples no banco de dados.")

- **SEÇÃO 2:** Pode ser algo como "Restrições de Stack" ou "Performance". Ex: "Stack fixa: Next.js, Supabase, shadcn/ui. A página principal deve carregar em menos de 2 segundos."
- **SEÇÃO 3:** Pode ser "Fluxo de Desenvolvimento" ou "Qualidade". Ex: "Toda PR deve ser revisada por pelo menos uma pessoa. O build deve passar em todos os testes antes do merge."
- **REGRAS DE GOVERNANÇA:** Como serão feitas as emendas na constituição. Ex: "Qualquer mudança nos princípios exige discussão em equipe e atualização deste documento. A versão deve seguir SemVer."

O agente usará suas respostas para preencher o template.

---

### **PASSO 8: Revise o Rascunho da Constituição e o "Sync Impact Report"**

**O que vai acontecer:**
O agente processará as informações e gerará um rascunho da `constitution.md` preenchida. Ele também gerará um **"Sync Impact Report"** (como um comentário HTML no topo do arquivo) mostrando o que mudou e quais outros templates podem precisar de atualização.

**O que você precisa fazer:**
- **Valide a Constituição:** Leia o documento `constitution.md` gerado. Confira se todos os placeholders foram preenchidos corretamente e se os princípios fazem sentido.
- **Verifique o Relatório de Impacto:** O agente pode listar arquivos como `.specify/templates/spec-template.md` que precisam ser revisados para garantir que estão alinhados com a nova constituição. Você pode precisar ajustá-los manualmente ou pedir para o agente ajudar.

---

### **PASSO 9: Finalize e Commit**

**O que vai acontecer:**
O agente salvará a `constitution.md` no local correto (`.specify/memory/constitution.md`) e fornecerá um resumo final com a nova versão e uma sugestão de mensagem de commit.

**O que você precisa fazer:**
- Faça o commit das mudanças no seu repositório, usando a mensagem sugerida ou uma personalizada.
- **Parabéns!** Agora você tem a especificação completa (5 documentos) e a constituição do projeto. O software está pronto para ser implementado por um agente de desenvolvimento seguindo essas regras.

---

---

## Resumo dos Prompts (O que você digita)

Para facilitar, aqui está a sequência de prompts que você usará:

1.  **Prompt 1 (Ideia):** `"Olá! Quero criar um software. Minha ideia é: [SUA IDEIA]."`
2.  **Prompt 2 (Respostas Discovery):** Responda às perguntas do agente.
3.  **Prompt 3 (Negociação MVP):** Concorde ou negocie o escopo do MVP.
4.  **Prompt 4 (Autorização):** `"Pode gerar os documentos completos."` (após revisar o resumo)
5.  **Prompt 5 (Constituição):** `"/speckit.constitution Vamos criar a constituição baseada nos documentos. O projeto se chama '[NOME DO PROJETO]'."`
6.  **Prompt 6 (Respostas Constituição):** Responda às perguntas sobre os princípios e regras.

Seguindo este guia, você terá um caminho claro e estruturado para transformar qualquer ideia em uma especificação completa e pronta para ser implementada por IA.

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

# FIFTH SECTION

# 📘 Guia Completo: Especificação de Software com IA (Spec-Driven Development)

> **Objetivo:** Este guia fornece um passo a passo detalhado para que você, programador, forneça todas as informações necessárias ao agente de IA, permitindo que ele especifique e detalhe completamente seu software — desde a ideia bruta até a documentação pronta para implementação.

---

## 🗂️ Visão Geral do Fluxo

```
[PREPARAÇÃO] → [CONSTITUIÇÃO] → [DISCOVERY] → [VALIDAÇÃO] → [ESPECIFICAÇÃO] → [HANDOFF]
```

**Dois pilares paralelos:**
1. **Constituição do Projeto** → Regras não negociáveis, princípios e governança (seu input direto)
2. **Descoberta do Produto** → Problema, usuários e contexto (diálogo iterativo com o agente)

**Stack técnica fixa (já definida no contexto do agente):**
- **Framework:** Next.js + Supabase
- **Arquitetura:** Client-side first, mínimo de server-side
- **UI:** shadcn/ui
- **Visual:** Clean, moderno, light mode (referências: Linear, Resend, Vercel)

---

## 📋 FASE 0: Preparação (Antes de Iniciar)

Tenha pronto os seguintes itens para agilizar o processo:

| Item | O que preparar | Exemplo |
|------|---------------|---------|
| **Nome do Projeto** | Nome claro e descritivo | `Aprovay - Aprovação de Despesas para Condomínios` |
| **Princípio #1 (Segurança - PRIORITÁRIO)** | Nome + descrição testável | `Autenticação Obrigatória: TODO acesso a dados financeiros exige MFA e sessão criptografada.` |
| **Princípios #2-5** | Outros princípios não negociáveis | `Performance: Carregamento inicial <2s em 3G; Privacidade: Dados sensíveis nunca em logs; etc.` |
| **Seções Adicionais** | Tópicos específicos do domínio | `Conformidade LGPD: Dados de moradores seguem retenção mínima de 2 anos.` |
| **Regras de Governança** | Como mudanças são aprovadas | `Alterações em princípios exigem revisão por 2 stakeholders e bump de versão MAJOR.` |
| **Ideia Bruta** | 1-3 frases descrevendo o conceito | "App para síndicos aprovarem despesas pelo celular, com notificação em tempo real e auditoria." |
| **Restrições Críticas** | Prazos, compliance, integrações | "Precisa integrar com banco X até Q3; deve estar em produção em 45 dias." |

---

## 🚀 FASE 1: Prompt Inicial (Kickoff)

**Copie e adapte este prompt para iniciar a conversa:**

```markdown
Sou seu Product Discovery Assistant.
Me manda sua ideia (bem crua mesmo).
Vou te fazer algumas perguntas rápidas, definir o MVP e gerar os documentos completos.
```

**Em seguida, envie sua ideia + elementos da constituição:**

```markdown
### 🎯 Minha Ideia
[Descreva sua ideia em 1-3 frases. Seja direto.]

### 📜 Constituição do Projeto (Input Direto)

**Nome do Projeto:** [PROJECT_NAME]

**Princípios Fundamentais:**
1. [PRINCIPLE_1_NAME - SEGURANÇA]: [Descrição testável e não negociável]
2. [PRINCIPLE_2_NAME]: [Descrição]
3. [PRINCIPLE_3_NAME]: [Descrição]
4. [PRINCIPLE_4_NAME]: [Descrição]
5. [PRINCIPLE_5_NAME]: [Descrição]

**Seções Adicionais:**
- [SECTION_2_NAME]: [SECTION_2_CONTENT]
- [SECTION_3_NAME]: [SECTION_3_CONTENT]

**Governança:**
[GOVERNANCE_RULES - ex: "Mudanças em princípios exigem revisão formal e versionamento semântico"]

**Metadados:**
- Versão Inicial: 1.0.0
- Data de Ratificação: [YYYY-MM-DD ou TODO]

### ⚙️ Restrições Técnicas/Comerciais
[Liste prazos, integrações obrigatórias, compliance, etc.]
```

> ✅ **Dica:** Como você priorizou **segurança**, certifique-se de que o Princípio #1 seja explícito, testável e com linguagem imperativa ("MUST", "NUNCA", "SEMPRE").

---

## 🏛️ FASE 2: Definição da Constituição (Seu Input Direto)

O agente irá processar sua constituição inicial. Esteja preparado para:

### 2.1 Refinar Princípios (se solicitado)
Se o agente pedir esclarecimentos, use este formato:

```markdown
### 🔧 Ajuste no Princípio #[N]

**Antes:** [texto original]
**Depois:** [texto revisado - mais testável/claro]
**Justificativa:** [por que a mudança é necessária]
```

### 2.2 Validar Versionamento Semântico
O agente aplicará estas regras automaticamente, mas você pode sugerir:

| Tipo de Mudança | Impacto na Versão | Exemplo |
|----------------|-------------------|---------|
| Remover/redefinir princípio | MAJOR (1.0.0 → 2.0.0) | Remover exigência de MFA |
| Adicionar princípio/seção | MINOR (1.0.0 → 1.1.0) | Adicionar princípio de observabilidade |
| Ajuste de redação/typo | PATCH (1.0.0 → 1.0.1) | Corrigir "autenticação" para "autenticação multifator" |

### 2.3 Confirmar Propagação de Mudanças
O agente verificará consistência com outros templates. Se você souber de dependências, informe:

```markdown
### 🔗 Dependências Conhecidas
- O princípio de segurança impacta: auth flow, logs, integrações com APIs externas
- Seções que precisam de atualização: `.specify/templates/spec-template.md` (requisitos de segurança)
```

---

## 🔍 FASE 3: Discovery (Diálogo Iterativo)

O agente fará perguntas em blocos de **até 3 por vez**. Responda de forma objetiva:

### 3.1 Sobre o Problema
```markdown
### ❓ Respostas - Discovery (Problema)

1. **Qual dor isso resolve?** 
   [Resposta concreta: ex: "Síndicos perdem 3h/semana coordenando aprovações por WhatsApp"]

2. **Como você sabe que o problema existe?**
   [Fonte: experiência própria, entrevistas, dados]

3. **Como resolvem hoje e por que é ruim?**
   [Processo atual + limitações]
```

### 3.2 Sobre os Usuários
```markdown
### 👥 Respostas - Discovery (Usuários)

1. **Quem é o usuário exato?**
   [Persona específica: ex: "Síndico profissional que gerencia 5+ condomínios"]

2. **Qual o "job to be done" principal?**
   [Ação + benefício: ex: "Aprovar uma despesa em <30 segundos, com confiança"]

3. **Por que usariam/pagariam por isso?**
   [Valor percebido: economia de tempo, redução de erros, compliance]
```

### 3.3 Sobre o Negócio
```markdown
### 💼 Respostas - Discovery (Negócio)

1. **É produto, feature ou ferramenta interna?**
   [Contexto estratégico]

2. **Existe modelo de monetização?**
   [Assinatura, freemium, B2B, etc.]

3. **Qual o diferencial vs. soluções existentes?**
   [Vantagem competitiva clara]

4. **Qual a urgência/prazo?**
   [Timeline crítica, se houver]
```

> ✅ **Regra:** Não pule para soluções técnicas. Deixe o agente inferir a implementação dentro do stack fixo.

---

## ✅ FASE 4: Validação (Definir MVP)

Após o discovery, o agente apresentará riscos e proposta de escopo. Sua resposta deve:

### 4.1 Concordar/Refutar Riscos
```markdown
### ⚠️ Feedback sobre Riscos Identificados

- **Risco X:** [Concordo / Discordo porque...]
- **Risco Y:** [Sugestão de mitigação: ...]
```

### 4.2 Priorizar Escopo (Must/Should/Could)
```markdown
### 🎯 Priorização do MVP

**MUST (essencial para lançar):**
- [Feature 1] - [Justificativa]
- [Feature 2] - [Justificativa]

**SHOULD (importante, mas pode esperar):**
- [Feature 3]

**COULD (nice-to-have):**
- [Feature 4]

**FORA DO MVP (futuro):**
- [Feature 5] - [Motivo para excluir agora]
```

### 4.3 Definir Critérios de Sucesso
```markdown
### 📏 Critérios de Sucesso do MVP

- **Métrica principal:** [ex: "80% das aprovações feitas em <1 minuto"]
- **Hipótese a validar:** [ex: "Síndicos preferem app mobile a desktop para aprovações rápidas"]
- **Condição de "pronto":** [ex: "50 usuários ativos na primeira semana"]
```

---

## 📄 FASE 5: Especificação (Geração dos Documentos)

Antes de gerar, o agente enviará um resumo. Sua aprovação deve ser:

### 5.1 Aprovar ou Ajustar o Resumo
```markdown
### ✅ Aprovação para Geração de Documentos

**Concordo com o resumo.** Pode prosseguir com a geração dos 5 documentos.

[OU]

**Ajustes solicitados:**
- BRIEF.md: Incluir [detalhe específico]
- PRD.md: Reforçar requisito de segurança em [feature X]
- [etc.]
```

### 5.2 Revisar Documentos Gerados
Os 5 documentos serão entregues em blocos separados. Para cada um:

```markdown
### 🔍 Feedback - [NOME_DO_DOCUMENTO]

**Aprovado** ✅

[OU]

**Solicito ajuste:**
- [Ponto específico] → [Sugestão de alteração]
```

> ⚠️ **Importante:** Não aprove documentos com ambiguidades. Seja específico nos ajustes.

---

## 🔄 FASE 6: Handoff para Implementação

Após aprovar todos os documentos, acione o agente de especificação técnica:

```markdown
### 🚀 Handoff para speckit.specify

Implement the feature specification based on the updated constitution. I want to build...

[Descreva brevemente o objetivo final, ex: "um sistema de aprovação de despesas para condomínios com foco em segurança e mobile-first"]

Contexto:
- Constituição: `.specify/memory/constitution.md` (versão [X.Y.Z])
- Documentos aprovados: BRIEF.md, PRD.md, MVP-SCOPE.md, LANDING-PAGE-SPEC.md, DESIGN-GUIDELINES.md
- Stack: Next.js + Supabase + shadcn/ui

Por favor, gere a especificação técnica detalhada para implementação.
```

---

## 📎 Apêndice: Templates de Prompt Prontos

### A1. Template de Princípio com Foco em Segurança
```markdown
**[PRINCIPLE_1_NAME - Segurança de Dados]**
TODO acesso a informações financeiras ou pessoais de moradores DEVE exigir:
- Autenticação multifator (MFA) ativa
- Sessão criptografada com timeout de 15 minutos de inatividade
- Log de auditoria imutável para todas as operações de escrita
Justificativa: Conformidade com LGPD e prevenção de acessos não autorizados em dispositivos compartilhados.
```

### A2. Template de Resposta Rápida para Discovery
```markdown
### Respostas - Discovery

1. **Dor principal:** [Texto]
2. **Usuário exato:** [Texto]  
3. **Solução atual + problema:** [Texto]
```

### A3. Template de Governança
```markdown
### Regras de Governança

- **Alteração de princípios:** Exige aprovação de [N] stakeholders + documentação de impacto + bump de versão MAJOR/MINOR conforme semver.
- **Revisão periódica:** Constituição revisada a cada [X] meses ou após [Y] mudanças significativas no escopo.
- **Conformidade:** Todas as features devem passar por "Constitution Check" antes da implementação.
```

---

## ✅ Checklist Final: O Que Você Precisa Fornecer

| Fase | Item | Status |
|------|------|--------|
| **Preparação** | Nome do projeto | ☐ |
| | Princípio #1 (Segurança) - testável | ☐ |
| | Princípios #2-5 - claros e não negociáveis | ☐ |
| | Seções adicionais (se aplicável) | ☐ |
| | Regras de governança | ☐ |
| | Ideia bruta (1-3 frases) | ☐ |
| | Restrições críticas (prazos, compliance) | ☐ |
| **Discovery** | Respostas sobre problema, usuário, negócio | ☐ |
| **Validação** | Priorização MUST/SHOULD/COULD | ☐ |
| | Critérios de sucesso do MVP | ☐ |
| **Especificação** | Aprovação/ajustes nos 5 documentos | ☐ |
| **Handoff** | Prompt final para speckit.specify | ☐ |

---

## 🎯 Resumo Executivo (Para Copiar e Colar)

```markdown
# Minha Especificação Inicial

## 🎯 Ideia
[1-3 frases]

## 📜 Constituição
**Projeto:** [Nome]
**Princípio #1 (Segurança):** [Texto testável]
**Princípios #2-5:** [Lista]
**Seções Extras:** [Se houver]
**Governança:** [Regras]
**Versão:** 1.0.0 | **Data:** [YYYY-MM-DD]

## ⚙️ Restrições
- [Restrição 1]
- [Restrição 2]

## 🚀 Próximo Passo
Estou pronto para a Fase 1: Discovery. Pode começar com as primeiras perguntas.
```

---

> 💡 **Dica Final:** Mantenha um arquivo local `project-brief.md` com todas as suas respostas e decisões. Isso facilita iterações futuras e garante consistência caso precise reiniciar a conversa com o agente.

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

# SIXTH SECTION

# Guia Completo de Especificação de Software para IA

## Objetivo
Fornecer um roteiro detalhado para que um programador possa interagir com um agente de IA (Assistente de Descoberta de Produto), fornecendo todas as informações necessárias para que a IA gere uma especificação de software completa e pronta para implementação.

## Metodologia
O processo é dividido em duas grandes partes:
1.  **Fundação do Projeto (A Constituição):** Estabelece as regras e princípios não negociáveis do projeto. Isso deve ser feito primeiro.
2.  **Descoberta e Especificação do Produto:** Uma conversa iterativa em 3 fases para transformar uma ideia bruta em documentação detalhada.

---

## Parte 1: Fundação do Projeto - Criando a Constituição

**Por que este passo é importante?** A Constituição é a "lei máxima" do seu software. Ela define os princípios arquitetônicos, regras de desenvolvimento e padrões que guiarão todas as decisões futuras. Fazer isso primeiro evita retrabalho e garante a consistência.

### Passo 0: Iniciar a Criação da Constituição

Forneça ao agente de IA um prompt inicial para começar a criar a constituição do seu projeto.

**Prompt a ser fornecido:**
```
Vamos criar a constituição para o meu projeto. O nome do projeto é "[NOME_DO_PROJETO]". Precisamos definir os princípios fundamentais, as seções adicionais e as regras de governança. Por favor, me guie nesse processo usando o template de constituição.
```

### Informações Detalhadas a Serem Fornecidas (Respondendo às perguntas da IA):

A IA fará perguntas com base no `constitution-template.md`. Esteja preparado para fornecer os seguintes detalhes:

1.  **Identidade do Projeto:**
    *   **`[PROJECT_NAME]`**: O nome oficial do seu projeto. (Ex: "Gestor de Tarefas Ágil")
    *   **`[CONSTITUTION_VERSION]`**: A versão inicial (geralmente "1.0.0").
    *   **`[RATIFICATION_DATE]`**: A data de criação da constituição (formato AAAA-MM-DD).

2.  **Princípios Fundamentais (Geralmente 5):**
    *   Para cada princípio, você precisará de:
        *   **`[PRINCIPLE_X_NAME]`**: Um nome curto e descritivo. (Ex: "Desenvolvimento Orientado a Testes", "Interface de Linha de Comando", "Primeiro o Cliente").
        *   **`[PRINCIPLE_X_DESCRIPTION]`**: Uma descrição clara das regras não negociáveis e a razão delas.
            *   **Exemplo para "Desenvolvimento Orientado a Testes":** "TODO novo código DEVE ser precedido por um teste que falha. A implementação só é considerada concluída quando o teste passa. Nenhuma exceção. Isso garante qualidade e facilita a refatoração futura."

3.  **Seções Adicionais (Opcional, mas recomendado):**
    *   **`[SECTION_2_NAME]`**: Título da seção (Ex: "Requisitos de Segurança", "Padrões de Performance").
    *   **`[SECTION_2_CONTENT]`**: Detalhes específicos. (Ex: "Todas as senhas devem ser hasheadas usando bcrypt. A API deve responder em menos de 200ms para 95% das requisições.")
    *   **`[SECTION_3_NAME]`**: Título de outra seção (Ex: "Fluxo de Desenvolvimento", "Processo de Revisão").
    *   **`[SECTION_3_CONTENT]`**: Detalhes do processo. (Ex: "Todo Pull Request requer aprovação de pelo menos um outro desenvolvedor. O CI/DEVE passar antes do merge.")

4.  **Regras de Governança:**
    *   **`[GOVERNANCE_RULES]`**: Como a constituição é mantida. (Ex: "Emendas à constituição requerem uma proposta formal e aprovação unânime da equipe. A conformidade com a constituição será verificada em cada revisão de código.")

---

## Parte 2: Descoberta e Especificação do Produto

**Por que este passo é importante?** Esta é a fase onde sua ideia é transformada em um plano concreto. A IA irá desafiar suas suposições, refinar o escopo e gerar a documentação que um desenvolvedor (humano ou IA) usaria para construir o software.

### Passo 1: FASE 1 - DESCOBERTA (Entendendo o Problema)

O objetivo aqui é um entendimento profundo. A IA fará perguntas para entender a dor, o usuário e o contexto.

**Prompt inicial para esta fase:**
```
Tenho uma ideia para um software. É um [descrição bem crua e simples da ideia]. Quero começar o processo de descoberta de produto.
```

**Informações a serem preparadas (para responder às perguntas da IA):**

*   **O Problema:**
    *   Qual dor específica isso resolve na prática? (Seja específico: "Perder 2 horas por semana organizando tarefas manualmente em planilhas.")
    *   Como você sabe que esse problema existe? (Experiência própria, pesquisa, conversas com clientes?)
    *   Como as pessoas resolvem isso hoje e por que é ruim? (Ex: "Usam Excel, que não tem notificações e é difícil de compartilhar em tempo real.")
*   **O Usuário:**
    *   Quem é o usuário exato? (Ex: "Gerentes de projeto de pequenas equipes de tecnologia (5-15 pessoas).")
    *   Qual é a principal "tarefa a ser executada" (job-to-be-done) dele? (Ex: "Manter todos os membros da equipe alinhados com as prioridades da sprint.")
    *   Qual seria o resultado ideal para eles? (Ex: "Ver o andamento do projeto em um dashboard e saber exatamente o que fazer a seguir sem perguntar.")
*   **O Negócio (se aplicável):**
    *   Isso é um produto, uma funcionalidade ou uma ferramenta interna?
    *   Há um plano de monetização? (Ex: "Assinatura mensal (SaaS)", "Gratuito com recursos premium pagos.")
    *   Qual é o diferencial em relação a soluções existentes? (Ex: "Integração nativa com GitHub e foco total em desenvolvedores, ao contrário do Jira que é genérico.")

### Passo 2: FASE 2 - VALIDAÇÃO (Definindo o MVP)

Após entender o problema, a IA irá desafiar sua ideia e ajudar a definir um Escopo Mínimo Viável (MVP).

**Informações a serem preparadas (para responder às perguntas da IA):**

*   **Riscos e Pontos Fracos:**
    *   Quais riscos você vê? (Ex: "O mercado já está saturado com ferramentas de gestão de tarefas.")
    *   O escopo parece realista para um MVP? (Seja honesto. A IA vai cortar o que for desnecessário.)
*   **Definição do MVP:**
    *   O que **PRECISA** estar no MVP? (Ex: "Criar tarefas, atribuir a um usuário, marcar como concluída.")
    *   o que **NÃO** estará no MVP? (Ex: "Relatórios complexos, integração com Slack, notificações por e-mail.")
    *   Quais são as principais hipóteses que precisamos validar? (Ex: "Hipótese: Desenvolvedores pagarão por uma ferramenta que se integra perfeitamente ao seu fluxo do GitHub.")
*   **Critérios de Sucesso:**
    *   Como saberemos que o MVP foi um sucesso? (Ex: "100 usuários ativos semanais após o primeiro mês." ou "Taxa de conversão de trial para pago de 10%.")

### Passo 3: FASE 3 - ESPECIFICAÇÃO (Gerando os Documentos)

Com o MVP definido, a IA irá gerar toda a documentação. Antes de gerar, ela apresentará um resumo para sua aprovação.

**Prompt para aprovação:**
```
O resumo está perfeito. Pode gerar todos os documentos.
```
Ou, se precisar ajustar:
```
Gostaria de ajustar um ponto no resumo. Na seção de [nome da seção], vamos mudar [o que mudar] para [novo valor]. Depois disso, pode gerar os documentos.
```

**Após a aprovação, a IA gerará os 5 documentos.** Esteja ciente do que cada um contém para revisar:

1.  **BRIEF.md:** Resumo executivo. Verifique se o problema, solução e público estão claros e corretos.
2.  **PRD.md (Documento de Requisitos de Produto):** O mais detalhado. Verifique as histórias de usuário, requisitos funcionais (o que o sistema faz) e não funcionais (performance, segurança).
3.  **MVP-SCOPE.md:** Verifique se o que está "dentro" e "fora" do MVP faz sentido.
4.  **LANDING-PAGE-SPEC.md:** Verifique a estrutura da página de venda. (Lembre-se: este doc não tem o texto, apenas a estrutura).
5.  **DESIGN-GUIDELINES.md:** Verifique as diretrizes visuais (cores, fontes, espaçamento) para garantir que alinham com sua visão.

---

## Passo Final: Entrega para Implementação

Com todos os documentos gerados e revisados, você tem uma especificação completa.

**Prompt final para a IA (ou para um desenvolvedor humano):**
```
Agora, com base em todos os documentos de especificação gerados (Brief, PRD, MVP-Scope, Landing-Page-Spec e Design-Guidelines), por favor, implemente o software inteiro, começando pelo escopo do MVP definido. Siga a constituição do projeto e as diretrizes de design.
```

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

# SEVENTH SECTION

### Guia Passo a Passo para Fornecer Informações ao Agente de IA e Especificar o Software

Este guia detalhado explica como interagir com o Agente de Descoberta de Produto (Product Discovery Assistant) e o comando speckit.constitution para fornecer todas as especificações, detalhes e informações necessárias para que o agente de IA crie o software inteiro de forma iterativa e incremental. O processo segue a metodologia spec-driven, onde você começa com uma ideia bruta e responde a perguntas do agente até que ele gere documentos prontos para implementação. Em seguida, usa esses documentos para criar a constituição do projeto, que define regras não negociáveis.

O guia é dividido em etapas sequenciais. Cada etapa inclui:
- **Descrição da etapa**: O que acontece e por quê.
- **Prompt que você deve fornecer**: O texto exato ou exemplo de mensagem que você envia ao agente de IA.
- **Informações detalhadas que você deve fornecer**: Tudo o que precisa descrever, baseado nos arquivos analisados (PROJECT-INSTRUCTIONS.md, constitution-template.md e guias internos).
- **O que esperar do agente**: Resposta típica do agente.
- **Dicas**: Para evitar erros comuns.

**Observações gerais**:
- O processo é iterativo: responda apenas ao que o agente pergunta por vez (máximo 3-4 respostas por mensagem para não sobrecarregar).
- Assuma o stack fixo: Next.js + Supabase, client-side first, shadcn/ui, visual clean/moderno/light mode.
- Se o agente desafiar sua ideia, responda com justificativas ou ajustes.
- Após gerar documentos, use-os para preencher a constituição.
- Ordem é crucial: não pule fases, ou o agente o trará de volta.
- O agente não gera documentos sem clareza (95% de confiança).

#### Etapa 1: Iniciar a Conversa com a Ideia Bruta (Início da Fase 1: Discovery)
**Descrição da etapa**: Apresente sua ideia inicial para acionar o agente. Isso inicia a Fase 1, onde o foco é entender o problema, usuários e contexto sem sugerir soluções. O agente fará até 3-4 perguntas por vez sobre problema, usuários e negócio.

**Prompt que você deve fornecer**:
"Olá! Minha ideia é [descreva a ideia bruta de forma concisa, ex.: 'Um app web para freelancers gerenciarem tarefas e faturas integradas, com lembretes automáticos']."

**Informações detalhadas que você deve fornecer**:
- Ideia bruta: Descreva o conceito principal em 1-2 frases, sem detalhes técnicos ou soluções. Inclua o nome do projeto se já tiver ([PROJECT_NAME], ex.: "FreelanceTracker").
- Motivação inicial: Por que você acha que isso é necessário (ex.: baseado em experiência pessoal ou pesquisa).

**O que esperar do agente**:
- Resposta no formato: "## 📍 PHASE 1: DISCOVERY" seguido de 3-4 perguntas, como "Qual problema específico isso resolve?" ou "Quem é o usuário exato?".

**Dicas**: Mantenha curto (menos de 200 palavras). Não mencione soluções ou MVP ainda.

#### Etapa 2: Responder às Perguntas da Fase 1 (Iterações da Discovery)
**Descrição da etapa**: Responda iterativamente às perguntas do agente até ele confirmar clareza. Isso coleta dados sobre problema, usuários e negócio. Pode levar 2-5 trocas de mensagens. O agente desafiará se algo for confuso.

**Prompt que você deve fornecer** (exemplo para uma iteração):
"Respostas às suas perguntas:
1. O problema específico é [descreva: ex. 'Freelancers perdem prazos de faturas porque usam ferramentas separadas para tarefas e finanças, causando atrasos em pagamentos'].
2. Como sei que existe: [ex. 'Baseado em pesquisa com 50 freelancers no Reddit e minha experiência pessoal'].
3. Como resolvem hoje: [ex. 'Usam planilhas Excel e apps como Trello, mas é manual e propenso a erros'].
4. Custo de não resolver: [ex. 'Perda de 10-20% de receita por atrasos, mais frustração diária']."

**Informações detalhadas que você deve fornecer** (baseado nas perguntas típicas das guias):
- **Sobre o Problema**: Problema em uma frase; evidências (ex.: pesquisa, dados); soluções atuais e por que são ruins; custo (tempo/dinheiro/frustração).
- **Sobre os Usuários**: Usuários exatos (ex.: "Freelancers de design gráfico, 25-40 anos, autônomos"); job to be done (ex.: "Gerenciar fluxo de trabalho diário sem ferramentas complexas"); resultado ideal (ex.: "Economizar 2 horas/dia"); por que usariam/pagariam (ex.: "Por integração simples e lembretes").
- **Sobre o Negócio**: Tipo (produto/feature/ferramenta interna); monetização (ex.: freemium, assinatura $5/mês); diferencial (ex.: "Integração nativa com Supabase para realtime updates, diferente de concorrentes como Asana"); urgência/timeline (ex.: "Lançar MVP em 3 meses").

**O que esperar do agente**:
- Mais perguntas se necessário, ou: "Ok, I understand. I’ll move to validation." (confirmação para Fase 2).

**Dicas**: Responda apenas às perguntas feitas. Seja honesto; se não souber, diga "Não tenho dados, mas assumo baseado em [fonte]". Repita até a confirmação.

#### Etapa 3: Engajar na Fase 2 (Validation)
**Descrição da etapa**: O agente propõe desafios, riscos e escopo MVP. Você confirma, ajusta ou fornece mais detalhes. Foco em viabilidade, simplificações e hipóteses.

**Prompt que você deve fornecer** (exemplo após proposta do agente):
"Concordo com os riscos identificados. Para o MVP: [ajuste ex.: 'Adicione integração básica com email para lembretes, mas remova analytics avançado']. Hipóteses: [ex.: 'Usuários pagarão se economizarem tempo']. Sucesso: [ex.: '100 usuários em 1 mês']."

**Informações detalhadas que você deve fornecer**:
- **Riscos e Pontos Fracos**: Responda a desafios (ex.: "Risco de privacidade: Mitigado com Supabase Auth"). Sugira pivots se o agente criticar (ex.: "Se a ideia for fraca, pivote para foco só em faturas").
- **Escopo MVP**: O que MUST/should/could (ex.: "MUST: Criação de tarefas/faturas; SHOULD: Compartilhamento; COULD: Integração com calendário"). O que fica fora (ex.: "AI predictions para v2").
- **Hipóteses**: Assunções a validar (ex.: "Usuários preferem interface simples sobre features complexas").
- **Critérios de Sucesso**: Métricas (ex.: "Retenção de 20% após 30 dias; receita inicial $500/mês").

**O que esperar do agente**:
- Resposta no formato: "## 📍 PHASE 2: VALIDATION" com propostas. Ao final: "MVP defined. I’ll generate the documents." (transição para Fase 3).

**Dicas**: Justifique ajustes. Seja realista; o agente é crítico.

#### Etapa 4: Revisar e Aprovar na Fase 3 (Specification - Sumário)
**Descrição da etapa**: O agente envia um sumário do que gerará nos 5 documentos. Você revisa e aprova ou ajusta.

**Prompt que você deve fornecer** (exemplo):
"Sumário parece bom, mas ajuste: [ex.: 'No PRD, adicione persona para gerentes de equipe']. Pode prosseguir."

**Informações detalhadas que você deve fornecer**:
- Ajustes por documento: Para BRIEF (problema/solução/público/vantagem/modelo/métricas); PRD (visão geral/personas/stories/requisitos funcionais/não-funcionais/integrações/edge cases/critérios); MVP-SCOPE (in/out/justificativa/hipóteses/métricas); LANDING (seções/objetivos/layout/elementos/CTAs - sem texto); DESIGN (paleta/typografia/espaçamento/radius/sombras/referências/guia shadcn/ui).

**O que esperar do agente**:
- "## 📍 PHASE 3: SPECIFICATION" com sumário, seguido de "May I proceed?".

**Dicas**: Seja específico nos ajustes para evitar iterações extras.

#### Etapa 5: Receber os Documentos Gerados (Specification - Geração)
**Descrição da etapa**: Após aprovação, o agente gera os 5 documentos. Copie-os para uso posterior.

**Prompt que você deve fornecer**: Nenhum necessário; apenas confirme na etapa anterior.

**Informações detalhadas que você deve fornecer**: Nenhuma nova; revise os documentos gerados para consistência.

**O que esperar do agente**:
- "## 📄 DOCUMENTS GENERATED" com cada documento em blocos Markdown, prontos para copiar (ex.: BRIEF.md com problema em 1 frase, etc.).

**Dicas**: Verifique alinhamento com stack fixo (Supabase integrações no PRD).

#### Etapa 6: Criar/Atualizar a Constituição do Projeto (Usando speckit.constitution)
**Descrição da etapa**: Use os documentos gerados para preencher a constituição (baseada no template). Invoque o comando com argumentos derivados dos docs. Isso define princípios não negociáveis, governação e sincroniza artefatos.

**Prompt que você deve fornecer** (exemplo como user input para o agente speckit):
"/speckit.constitution $ARGUMENTS: [ex.: 'PROJECT_NAME: FreelanceTracker; PRINCIPLE_1_NAME: Test-First; PRINCIPLE_1_DESCRIPTION: TDD obrigatório para todas features; Adicione 5 princípios baseados no PRD: [liste derivado dos docs, ex. Security-First para Supabase Auth]. RATIFICATION_DATE: 2026-02-28; GOVERNANCE_RULES: PRs devem verificar compliance com MVP-SCOPE']."

**Informações detalhadas que você deve fornecer** (preencher placeholders do template):
- **PROJECT_NAME**: Nome do projeto (ex.: "FreelanceTracker Constitution").
- **Core Principles** (3-7 ou mais/menos se especificado): Nome e descrição para cada (ex.: PRINCIPLE_1_NAME: "Client-Side First"; DESCRIPTION: "Mínimo server-side, conforme arquitetura fixa"). Derive de docs (ex.: Test-First de riscos no MVP; Observability de integrações Supabase).
- **Sections Adicionais**: SECTION_2_NAME (ex.: "Security Requirements"); CONTENT (ex.: "Obrigatório Supabase Auth e criptografia").
- **Governance**: GOVERNANCE_RULES (ex.: "Amendments requerem aprovação; PRs verificam princípios; Use DESIGN-GUIDELINES para UI").
- **Versioning/Dates**: CONSTITUTION_VERSION (ex.: "1.0.0" inicial); RATIFICATION_DATE (ex.: data atual); LAST_AMENDED_DATE (atual se mudado).

**O que esperar do agente**:
- Atualiza .specify/memory/constitution.md; relatório de impacto; sumário com versão nova, arquivos pendentes e mensagem de commit.

**Dicas**: Se faltar info, use TODO. Incremente versão semanticamente. Sincronize com templates (ex.: atualize plan-template.md se princípios mudarem).

#### Etapa 7: Iterações Finais e Implementação
**Descrição da etapa**: Se necessário, volte a fases anteriores para refinar. Com constituição pronta, o agente pode prosseguir para handoffs (ex.: "Build Specification" via speckit.specify).

**Prompt que você deve fornecer** (exemplo):
"Com base na constituição atualizada, implemente a feature: [descreva, ex. 'I want to build the MVP tasks module']."

**Informações detalhadas que você deve fornecer**: Detalhes adicionais de implementação (ex.: edge cases do PRD).

**O que esperar do agente**: Geração de specs/plans/tasks alinhados à constituição.

**Dicas**: Monitore consistência; o processo termina quando o software estiver especificado para codificação por IA.

Este guia cobre todos os elementos mapeados dos arquivos, garantindo que o agente tenha clareza total para criar o software.

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

# EIGHTH SECTION

## **Step-by-Step Guide for Spec-Driven Development**

### **1. Discovery Phase**
**Objective**: Understand the problem, user, and context.

#### **Prompts to Answer:**
1. **Problem Statement**
   - What problem does this software solve in practice?
   - Why is this problem important?

2. **Target User**
   - Who is the exact user of this software?
   - What are their characteristics (e.g., age, profession, tech-savviness)?

3. **Current Solution**
   - How do users currently solve this problem?
   - Why is the current solution inadequate?

4. **Context**
   - Are there any constraints or specific contexts the software must operate in?

**Output**: Once clear, say: *"Ok, I understand. Let's move to validation."*

---

### **2. Validation Phase**
**Objective**: Cut unnecessary features and define the Minimum Viable Product (MVP).

#### **Prompts to Answer:**
1. **Simplest Version**
   - What is the simplest version of this software that still solves the problem?

2. **Must-Have Features**
   - What features are absolutely necessary for the MVP?
   - What features can be removed without losing core value?

3. **Assumptions**
   - What assumptions are we making about the user or problem?
   - Are these assumptions valid?

**Output**: Once validated, say: *"The MVP is clear. Let's move to specification."*

---

### **3. Specification Phase**
**Objective**: Generate detailed documentation.

#### **Documents to Create:**
1. **BRIEF.md**
   - High-level overview of the project.
   - Problem, solution, and target user.

2. **PRD.md (Product Requirements Document)**
   - Detailed requirements, features, and user stories.
   - Technical and non-technical specifications.

3. **MVP-SCOPE.md**
   - Scope of the MVP.
   - Features included and excluded.

4. **LANDING-PAGE-SPEC.md**
   - Specifications for the landing page.
   - Design, content, and call-to-action.

5. **DESIGN-GUIDELINES.md**
   - UI/UX guidelines.
   - Visual style, components, and interaction patterns.

---

### **4. Software Constitution**
**Objective**: Define non-negotiable rules and principles.

#### **Prompts to Answer:**
1. **Core Principles**
   - Define 5 core principles (e.g., Test-First, CLI Interface, Observability, Versioning, Simplicity).
   - Example:
     - **I. Test-First**: TDD mandatory.
     - **II. CLI Interface**: Every library exposes functionality via CLI.

2. **Additional Sections**
   - Additional constraints (e.g., security, performance).
   - Development workflow and review process.

3. **Governance**
   - How will the constitution be enforced?
   - What is the process for amendments?

---

### **5. Order to Provide Information**
1. **Discovery Phase**: Start with the problem, user, and context.
2. **Validation Phase**: Define the MVP and cut unnecessary features.
3. **Specification Phase**: Generate the required documents.
4. **Software Constitution**: Fill in the core principles and governance rules.

---

### **6. Example Prompts for Each Phase**
#### **Discovery Phase Example:**
- *"What problem does this software solve?"*
- *"Who is the exact user?"*
- *"How do users solve this problem today?"*

#### **Validation Phase Example:**
- *"What is the simplest version of this software?"*
- *"What features are must-haves for the MVP?"*

#### **Specification Phase Example:**
- *"Let's create the BRIEF.md with a high-level overview."*
- *"What are the detailed requirements for the PRD.md?"*

#### **Software Constitution Example:**
- *"Define the 5 core principles for this project."*
- *"What are the governance rules for amendments?"*

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

# NINTH SECTION

# Guia Completo: Como Fornecer Especificações para um Agente de IA Criar seu Software

---

## Visão Geral do Processo

O fluxo completo segue esta sequência obrigatória:

**Ideia Bruta → Fase 1 (Discovery) → Fase 2 (Validação) → Fase 3 (Especificação) → Constitution → Desenvolvimento**

Você não pode pular etapas. O agente vai te trazer de volta se tentar.

---

## ETAPA 0 — Antes de Começar

Antes de abrir qualquer conversa com o agente, prepare mentalmente (não precisa escrever formalmente ainda) as respostas para estas perguntas básicas:

- Qual é o problema central que o software resolve?
- Quem vai usar o software (cargo, contexto, frequência)?
- Como esse problema é resolvido hoje (mesmo que de forma manual ou ruim)?
- O que o sucesso parece? Qual métrica ou comportamento comprova que funcionou?
- Existe alguma restrição absoluta (prazo, compliance, integrações obrigatórias)?
- É um produto, uma feature ou uma ferramenta interna?
- Existe monetização planejada?

---

## ETAPA 1 — Prompt Inicial (Ideia Bruta)

**O que fazer:** Envie sua ideia de forma crua, sem polir. O agente foi treinado para receber ideias incompletas.

**Formato sugerido do prompt:**

```
Minha ideia é: [descreva em 2 a 5 frases o que você quer construir]

Contexto adicional (se quiser): [qualquer informação que achar relevante]
```

**Exemplo real:**

```
Minha ideia é: Uma plataforma onde freelancers de design podem criar 
portfólios interativos e receber propostas de clientes diretamente.
Hoje eles usam Behance ou PDFs enviados por e-mail, o que é lento e 
sem rastreamento.
```

**Dica importante:** Não tente ser técnico aqui. Quanto mais natural e honesta for a descrição, melhor o agente consegue entender o problema real por trás da ideia.

---

## ETAPA 2 — Fase 1: Discovery (Responder as Perguntas)

O agente vai te fazer até 3-4 perguntas por vez. Você vai passar por rodadas de perguntas cobrindo três áreas. Responda com o máximo de detalhes possível em cada rodada.

### Rodada sobre o Problema

Perguntas prováveis que o agente vai fazer:

- Qual problema específico isso resolve?
- Como você sabe que esse problema existe?
- Como as pessoas resolvem isso hoje?
- Qual o custo (tempo/dinheiro/frustração) de não resolver?

**Como responder bem:**

```
O problema é: [descreva a dor de forma concreta, com exemplos reais se possível]

Eu sei que existe porque: [experiência pessoal / pesquisa / feedback de usuários]

Hoje as pessoas resolvem fazendo: [descreva o processo atual, mesmo que ruim]

O custo de não resolver é: [quantifique se possível — "leva 3h por semana", "perde 20% de clientes"]
```

### Rodada sobre os Usuários

Perguntas prováveis:

- Quem exatamente vai usar isso?
- Qual é o "job to be done" principal?
- Qual seria o resultado ideal para eles?
- Por que pagariam ou usariam?

**Como responder bem:**

```
O usuário principal é: [cargo, contexto, nível técnico, frequência de uso]

O que ele quer fazer (job to be done): [verbo + objeto, ex: "publicar trabalhos e receber contatos qualificados"]

O resultado ideal seria: [o que muda na vida dele depois de usar o produto]

Ele usaria/pagaria porque: [motivação real, não assumida]
```

### Rodada sobre o Negócio

Perguntas prováveis:

- É produto, feature ou ferramenta interna?
- Existe monetização planejada?
- Qual o diferencial em relação ao que existe?
- Qual a urgência e timeline?

**Como responder bem:**

```
É um: [produto público / feature de produto existente / ferramenta interna]

Monetização: [freemium / assinatura / por uso / sem monetização / ainda não definido]

Diferencial: [o que você faz que os concorrentes não fazem, ou fazem mal]

Timeline: [MVP em X semanas / sem prazo definido / urgente porque...]
```

**Sinal de que a Fase 1 terminou:** O agente vai dizer explicitamente "Ok, entendi. Vou para a validação."

---

## ETAPA 3 — Fase 2: Validação (Confirmar ou Ajustar o MVP)

O agente vai apresentar uma análise crítica da sua ideia. Você vai receber:

- Lista de **riscos identificados**
- Separação entre **o que é MVP** vs. **o que é exagero**
- **Hipóteses** que precisam ser validadas
- **Critérios de sucesso** sugeridos

### O que você precisa fazer nessa fase:

**1. Reagir aos riscos apontados:**

```
Sobre o risco de [X]: concordo / discordo porque [razão]

Sobre o risco de [Y]: isso já foi considerado, a solução é [...]
```

**2. Confirmar ou ajustar o escopo do MVP:**

```
Concordo que [feature X] fica fora do MVP.

Discordo: [feature Y] precisa estar no MVP porque [razão de negócio].

Adição: também precisa ter [feature Z] porque é bloqueante para o usuário.
```

**3. Validar as hipóteses listadas:**

```
A hipótese de que [X] é válida / inválida porque [evidência ou raciocínio].
```

**4. Confirmar ou ajustar os critérios de sucesso:**

```
O sucesso do MVP é: [métrica concreta — ex: "50 usuários ativos na primeira semana", 
"taxa de conversão acima de 5%", "tempo de onboarding abaixo de 10 minutos"]
```

**Sinal de que a Fase 2 terminou:** O agente vai dizer "MVP definido. Vou gerar os documentos."

---

## ETAPA 4 — Fase 3: Aprovação do Resumo Antes dos Documentos

Antes de gerar os 5 documentos, o agente vai apresentar um **resumo do que vai produzir**. Este é o momento mais importante para revisar antes de deixar o agente trabalhar.

### O que revisar no resumo:

**Para o BRIEF.md:**
- A frase do problema está correta e representa a dor real?
- O diferencial descrito é real e defensável?

**Para o PRD.md:**
- As personas refletem os usuários reais que você descreveu?
- As user stories cobrem os fluxos principais?
- Os requisitos não-funcionais incluem o que é crítico para você (performance, segurança, offline, etc.)?

**Para o MVP-SCOPE.md:**
- O que está como "must" é realmente o mínimo viável?
- O que está fora não vai inviabilizar o teste das hipóteses?

**Para o LANDING-PAGE-SPEC.md:**
- A estrutura de seções faz sentido para o seu público?
- A hierarquia de CTAs está alinhada com o objetivo de negócio?

**Para o DESIGN-GUIDELINES.md:**
- O estilo visual sugerido está alinhado com a identidade que você quer?
- As referências visuais apontadas são de fato o que você quer?

**Como responder:**

```
Aprovado com os seguintes ajustes:

1. No PRD: adicionar requisito de [X]
2. No MVP-SCOPE: mover [feature Y] de "should" para "must"  
3. No DESIGN: quero referência mais próxima de [site/produto Z]

O restante está correto. Pode gerar.
```

---

## ETAPA 5 — Receber e Revisar os 5 Documentos

Após a geração, revise cada documento com atenção específica:

### BRIEF.md — Checklist de revisão:
- [ ] Problema em uma frase: está claro para alguém que não conhece o contexto?
- [ ] Solução: está descrita sem jargão técnico?
- [ ] Público: está específico o suficiente (não "qualquer pessoa")?
- [ ] Métricas: são mensuráveis e têm prazo?

### PRD.md — Checklist de revisão:
- [ ] Personas: têm nome, contexto, objetivo e frustração atual?
- [ ] User stories: seguem o formato "Como [persona], quero [ação] para [benefício]"?
- [ ] Requisitos funcionais: cobrem todos os fluxos que você descreveu?
- [ ] Requisitos não-funcionais: incluem performance, segurança e acessibilidade?
- [ ] Integrações Supabase: auth, storage e realtime estão mapeados corretamente?
- [ ] Edge cases: os casos de erro e limite estão descritos?
- [ ] Critérios de aceitação: são testáveis (binários — passa ou não passa)?

### MVP-SCOPE.md — Checklist de revisão:
- [ ] O que está em "must" pode ser entregue em 4-6 semanas?
- [ ] O que está fora não vai impedir o teste das hipóteses principais?
- [ ] As hipóteses são verificáveis com os recursos do MVP?

### LANDING-PAGE-SPEC.md — Checklist de revisão:
- [ ] Não tem copy (só estrutura)?
- [ ] A ordem das seções segue uma narrativa lógica?
- [ ] O CTA principal aparece acima da dobra?

### DESIGN-GUIDELINES.md — Checklist de revisão:
- [ ] A paleta tem contraste acessível (WCAG AA no mínimo)?
- [ ] A tipografia está alinhada com o estilo clean/moderno descrito?
- [ ] O guia de shadcn/ui especifica qual componente usar para cada padrão de UI?

---

## ETAPA 6 — Criação da Constituição do Projeto

Após os 5 documentos aprovados, você executa o comando `/speckit.constitution` e fornece as informações para preencher o `constitution-template.md`.

### O que você precisa fornecer:

**Nome do Projeto:**
```
PROJECT_NAME: [Nome exato do projeto, ex: "FreelioKit", "TaskBoard Pro"]
```

**Princípios Fundamentais** (o núcleo da constituição):

Para cada princípio, forneça nome e descrição com regras não-negociáveis:

```
PRINCIPLE_1_NAME: [ex: "Client-Side First"]
PRINCIPLE_1_DESCRIPTION: 
  - Toda lógica de negócio DEVE rodar no cliente sempre que possível
  - Server-side APENAS para: autenticação, webhooks, operações sensíveis
  - Nenhuma Server Action deve duplicar lógica já disponível no cliente

PRINCIPLE_2_NAME: [ex: "Test-First (NÃO-NEGOCIÁVEL)"]  
PRINCIPLE_2_DESCRIPTION:
  - TDD obrigatório: testes escritos → aprovados pelo usuário → falham → implementação
  - Nenhuma feature vai para produção sem cobertura de testes unitários e de integração
  - Ciclo Red-Green-Refactor estritamente seguido

PRINCIPLE_3_NAME: [ex: "Tipagem Estrita"]
PRINCIPLE_3_DESCRIPTION:
  - TypeScript strict mode em todo o projeto
  - Proibido uso de 'any'
  - Todos os contratos de API devem ter schemas Zod validando entrada e saída

[adicione quantos princípios precisar]
```

**Seções adicionais** (se aplicável):

```
SECTION_2_NAME: [ex: "Requisitos de Segurança"]
SECTION_2_CONTENT:
  - Row Level Security (RLS) obrigatório em todas as tabelas Supabase
  - Nenhum dado sensível no localStorage
  - Variáveis de ambiente nunca expostas no cliente

SECTION_3_NAME: [ex: "Workflow de Desenvolvimento"]
SECTION_3_CONTENT:
  - Toda PR deve referenciar uma issue
  - Code review obrigatório antes de merge na main
  - Deploy só ocorre após todos os testes passarem no CI
```

**Informações de Governança:**

```
GOVERNANCE_RULES:
  - A constituição supera todas as outras práticas e decisões técnicas
  - Emendas exigem: documentação da mudança + aprovação + plano de migração
  - Toda PR/revisão deve verificar conformidade com os princípios
  - Complexidade adicional deve ser justificada explicitamente

CONSTITUTION_VERSION: 1.0.0
RATIFICATION_DATE: [data de hoje em formato YYYY-MM-DD]
LAST_AMENDED_DATE: [data de hoje em formato YYYY-MM-DD]
```

---

## ETAPA 7 — Revisão Final da Constituição

Após o agente gerar a constituição, verifique:

- [ ] Nenhum token entre colchetes `[ASSIM]` foi deixado sem preenchimento
- [ ] Os princípios estão escritos com linguagem declarativa (MUST/DEVE, não "deveria")
- [ ] As datas estão no formato ISO (YYYY-MM-DD)
- [ ] A versão está no formato semântico (MAJOR.MINOR.PATCH)
- [ ] O Sync Impact Report foi gerado no topo do arquivo
- [ ] Os templates dependentes foram atualizados (plan-template, spec-template, tasks-template)

---

## Resumo Visual da Ordem de Informações

```
[ETAPA 0] Preparação mental
      ↓
[ETAPA 1] Prompt inicial com ideia bruta
      ↓
[ETAPA 2] Respostas às perguntas de Discovery
          └── Rodada: Problema
          └── Rodada: Usuários  
          └── Rodada: Negócio
      ↓
[ETAPA 3] Confirmação/ajuste do MVP na Validação
          └── Reação aos riscos
          └── Ajuste de escopo
          └── Validação de hipóteses
          └── Confirmação de critérios de sucesso
      ↓
[ETAPA 4] Aprovação do resumo dos documentos
      ↓
[ETAPA 5] Revisão dos 5 documentos gerados
          └── BRIEF.md
          └── PRD.md
          └── MVP-SCOPE.md
          └── LANDING-PAGE-SPEC.md
          └── DESIGN-GUIDELINES.md
      ↓
[ETAPA 6] Fornecimento dos dados para a Constituição
          └── Nome do projeto
          └── Princípios (N princípios com regras)
          └── Seções adicionais
          └── Governança + versão + datas
      ↓
[ETAPA 7] Revisão final da Constituição gerada
      ↓
[PRONTO] Agente pode começar o desenvolvimento
```

---

## Dicas Finais

**Seja específico nos princípios da constituição.** "Código de qualidade" não é um princípio — "Cobertura de testes unitários mínima de 80% em toda feature nova" é.

**Não pule a fase de validação.** É ela que impede que você construa a coisa certa do jeito errado ou a coisa errada do jeito certo.

**Os critérios de aceitação no PRD são o contrato do agente.** Quanto mais testáveis e binários forem, menos ambiguidade haverá na implementação.

**A constituição é viva.** Você pode emendá-la ao longo do projeto — mas cada emenda precisa seguir o processo de versionamento semântico e propagação para os templates dependentes.

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------

# TENTH SECTION

Here's a detailed step-by-step guide for gathering information to facilitate the AI agent's development of the software. This guide includes every necessary prompt the programmer should provide to ensure that the agent can specify and detail the software completely.

### Step-by-Step Guide

#### Step 1: Initial Idea Description
- **Prompt**: "Please describe your idea for the software in as much detail as possible. What is the core concept?"
  
#### Step 2: Discovery Phase
The focus here is to deeply understand the problem, users, and business context.

- **About the Problem**:
  1. **Prompt**: "What specific problem does this software solve?"
  2. **Prompt**: "How do you know this problem exists (personal experience, user feedback, research)?"
  3. **Prompt**: "How do people currently solve this problem, and what are the shortcomings of these solutions?"
  4. **Prompt**: "What is the cost (in terms of time, money, or frustration) of not solving this problem?"

- **About the Users**:
  1. **Prompt**: "Who exactly is the target user of this software?"
  2. **Prompt**: "What is the main 'job to be done' for the users?"
  3. **Prompt**: "What would the ideal outcome be for the users?"
  4. **Prompt**: "What motivates users to pay for or use this software?"

- **About the Business**:
  1. **Prompt**: "Is this a standalone product, a feature of a larger system, or an internal tool?"
  2. **Prompt**: "What monetization model, if any, do you plan to implement?"
  3. **Prompt**: "What differentiates your solution from the existing alternatives?"
  4. **Prompt**: "What is the urgency or timeline for this project?"

#### Step 3: Validation Phase
Here, the AI agent will challenge the idea and define the MVP (Minimum Viable Product).

- **Viability Assessment**:
  1. **Prompt**: "What risks or challenges do you foresee with this idea?"
  2. **Prompt**: "Is the scope achievable for an MVP? What might be too ambitious?"
  3. **Prompt**: "Can you suggest any simplifications that might make it more feasible?"
  4. **Prompt**: "If the original idea seems weak, would you consider pivoting? What alternatives can you think of?"

- **Defining MVP Scope**:
  1. **Prompt**: "What must be included in the MVP (core features)?"
  2. **Prompt**: "What will intentionally be left out of the MVP (future enhancements)?"
  3. **Prompt**: "What criteria will determine the success of the MVP?"
  4. **Prompt**: "What hypotheses need to be validated during the MVP development?"

#### Step 4: Specification Phase
The goal is to generate comprehensive documentation based on previously defined parameters.

- **Summary Request**:
  - **Prompt**: "Here’s a summary of what we will produce for documentation. Do you approve, or would you like to make adjustments?"

- **Documentation to Generate**: After confirmation, proceed with generating the following documents:
  1. **BRIEF.md**: 
     - Prompt information:
       - Problem statement (1 sentence)
       - Proposed solution
       - Target audience
       - Competitive advantage
       - Business model (if applicable)
       - Success metrics
  2. **PRD.md**:
     - Collect:
       - Product overview
       - Personas
       - User stories structured as "As [persona], I want [action] to [benefit]"
       - Functional and non-functional requirements
       - Necessary integrations (e.g., Supabase)
       - Edge cases
       - Acceptance criteria
  3. **MVP-SCOPE.md**:
     - List what is in and out of the MVP, along with justifications and metrics for success.
  4. **LANDING-PAGE-SPEC.md**:
     - Outline section structure, objectives of each section, suggested layouts, visual elements (no text required).
  5. **DESIGN-GUIDELINES.md**:
     - Specify visual elements like color palette (hex codes), typography, spacing, and references for design consistency.

#### Step 5: Constitution Creation
- After the specification is complete, you will focus on creating the constitution based on the gathered information.

1. **Collect Core Principles**:
   - **Prompt**: "Please list up to five core principles that will govern this project. For each principle, provide a name and a detailed description."
  
2. **Identify Sections**:
   - **Prompt**: "What additional constraints, security requirements, or performance standards should be included?"
   - **Prompt**: "What development workflow and review processes are necessary for this project?"

3. **Governance**:
   - **Prompt**: "What governance rules should be established (e.g. amendment procedures, compliance checks)?"

4. **Versioning and Dates**:
   - **Prompt**: "What is the initial ratification date of the constitution? What is the last amended date?"
   - **Prompt**: "What versioning strategy will you follow (e.g., MAJOR.MINOR.PATCH) for future updates?"

### Final Output
Once all the inputs have been collected, confirm with the user to finalize the documents and generate the complete software specification.

--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
