# 🚀 Estágio Supervisionado UniFil - Guia Ágil para Alunos
Este repositório é um template no GitHub para que você possa criar seu próprio repositório de estágio supervisionado a partir dele. Para usá-lo:

- Clique no botão "Use this template" para gerar uma cópia personalizada.
- Renomeie e ajuste a estrutura conforme as necessidades do seu projeto.
- Atualize os documentos e a Wiki de acordo com as entregas do seu estágio.
- Utilize as TAGs para marcar cada entrega e compartilhe os links conforme as instruções.

As regras aqui são apenas diretrizes e não substituem as orientações do seu orientador e coordenador de estágio.

**Bem-vindo ao seu Estágio Supervisionado!**  
Aqui, você desenvolverá um projeto real usando metodologias ágeis, dividido em **4 unidades curriculares sequenciais**. Para simplicar, chamaremos a unidades curriculares de "unidades". Cada unidade é uma **"Jornada Ágil"** com sprints flexíveis, mas entregas obrigatórias. Seu orientador atuará como *Agile Master* (PO + Scrum Master), e **todo progresso deve ser registrado no GitHub e validado via Google Classroom**. 🛠️  

---

## ⚠️ Regras Cruciais (Não Pule Essa Parte!)
1. **Unidades 1 e 3**: Avaliadas **diretamente pelo orientador** (nota final).  
2. **Unidades 2 e 4**: Avaliadas por **banca examinadora**. Para apresentar, você precisará de um **atestado de aptidão do orientador**.  
3. **TAGs são obrigatórias**: Cada entrega deve ter uma TAG no GitHub com link postado no Google Classroom.  
4. **Documentação progressiva**: Até a Unidade 2, você deve ter **toda a documentação básica pronta**, exceto diagramas de novos casos de uso desenvolvidos posteriormente.  

---

## 📌 Visão Geral do Estágio
| Unidade | Avaliação | Pré-Requisitos para Banca | Artefatos-Chave |
|---------|-----------|----------------------------|------------------|
| 1️⃣ **Análise** | Nota do Orientador | - | CRUD, Documento de Visão, Workflow As-Is/To-Be e etc... |
| 2️⃣ **Projeto** | Banca | Atestado do Orientador + 1 Caso de Uso Funcional + **Todos os Diagramas** | Especificação de Caso de Uso, Diagramas de Sequência e etc... |
| 3️⃣ **Implementação I** | Nota do Orientador | - | 50-80% dos Casos de Uso |
| 4️⃣ **Implementação II** | Banca Final | Atestado do Orientador + Sistema 100% Funcional | Relatório Final, todos os artefatos e todos os diagramas  |

---

## 🛠️ Configuração do Repositório
No Google Classroom de Estágio, terá entregas programadas e para cada uma delas você deve entregar o link de uma TAG.

### Como Funcionam as TAGs no Git?
As **TAGs** são "pontos de entrega" congelados no seu repositório. Servem para:  
- Registrar versões estáveis do projeto.  
- Facilitar a avaliação (seu orientador/banca verá exatamente o que você entregou).  

**Passo a Passo para Criar uma TAG**:  
1. Finalize uma entrega (ex: CRUD da Unidade 1).  
2. Execute no terminal:  
   ```bash
   git tag -a "Entrega Diagrama X" -m "CRUD de usuários implementado"
   git push origin --tags
   ```  
3. **Nomeie as TAGs claramente**:  
   - As TAGS deverão ter o mesmo nome EXATO da atividade postada no Classroom.
4. **Vincule ao Google Classroom**:  
   - Link da TAG: `https://github.com/Estagio-UniFil/[REPO]/tree/[NOME_DA_TAG]`.  

❗ **Importante**:  
- TAGs incompletas ou sem link no Classroom = **entrega não validada**.
- Ajustas posteriores á geração da TAG entregue não serão avaliadas.

---

## 🧩 Processo de Avaliação por Unidade

O estágio é dividido em **4 unidades**, cada uma com objetivos e entregas específicas. Para garantir o sucesso, você deve se organizar em **sprints** (ciclos de trabalho) e planejar um **cronograma detalhado**. Lembre-se: **flexibilidade é permitida, mas comunicação é obrigatória**. Qualquer mudança no planejamento deve ser **comunicada imediatamente ao orientador**, que atuará como seu guia e avaliador.

### Como Funciona o Planejamento?
1. **Defina suas Sprints**:  
   Cada sprint deve ter um objetivo claro (ex: desenvolver um CRUD, documentar um caso de uso).  
   - Sugestão: Sprints de **1 ou 2 semanas** são ideais para manter o foco e a produtividade.  
   - Use ferramentas como o **GitHub Projects (RECOMENDADO)** ou um quadro Kanban físico para visualizar as tarefas.  

2. **Crie um Cronograma**:  
   - Estime o tempo necessário para cada tarefa.  
   - Reserve um tempo para **revisões e ajustes** (imprevistos acontecem!).  
   - Compartilhe o cronograma com seu orientador no início de cada unidade.  

3. **Comunique Mudanças**:  
   - Se algo sair do planejado (ex: atrasos, dificuldades técnicas), **informe seu orientador imediatamente**.  
   - Juntos, vocês podem ajustar o cronograma e priorizar tarefas.  


### 🎯 Unidade 1: Análise (EST230168)
- **Avaliação**: Nota do orientador.  
- **Entregas**:  
  - CRUD funcional.
  - Plano de estágio.
  - Documentação básica: Visão, Pedido do Investidor, Workflow As-Is/To-Be.  

---

### 🎯 Unidade 2: Projeto (EST230169) → **Banca!**  
- **Pré-requisitos para Banca**:  
  - Atestado do orientador confirmando:  
    - Pelo menos 1 Caso de Uso **100% funcional**. ⚠️ ATENÇÃO É preferível não se limitar a um caso de uso para otimização de tempo.  
    - **Todos os diagramas** (Sequência, Estados, Classe) do caso de uso apresentado.  
  - Documentação completa (exceto novos casos de uso desenvolvidos depois).
  - Material para apresentação da banca.
  - Você deve conseguir um atestado de qualificação com seu orientador para realizar a banca.
- **O que a Banca Avalia**:  
  - Qualidade do código.  
  - Clareza dos diagramas.
  - Apresentação.
  - Caso de uso funcionando.
  - Organização da documentação.  

---

### 🎯 Unidade 3: Implementação I (EST230170)  
- **Avaliação**: Nota do orientador.  
- **Entregas**:  
  - 50-80% dos casos de uso implementados.  
  - **Novos diagramas** apenas para funcionalidades implementadas nesta unidade (ex: novo caso de uso → novo diagrama de sequência e especificação de caso de uso).  

---

### 🎯 Unidade 4: Implementação II (EST230171) → **Banca Final!**  
- **Pré-requisitos**:  
  - Atestado do orientador confirmando o sistema **100% funcional**.
  - Relatório final.
  - Todos os diagramas atualizados (incluindo novos casos de uso).
  - Material para apresentação da banca.
- **O que a Banca Avalia**:  
  - Funcionalidade total do sistema.
  - Apresentação
  - Qualidade do relatório final.  
  - Diagrama de implantação.  

---



## 📄 Documentação Progressiva (Atualize a Wiki!)

| Documento/Artefato               | Descrição |
|----------------------------------|-----------|
| **Documento de Visão**           | Descreve o propósito, objetivos, escopo e stakeholders do projeto. |
| **Documento do Pedido do Investidor** | Detalha as necessidades do cliente e os requisitos do projeto. |
| **Glossário**                    | Lista de termos técnicos e conceitos usados no projeto. |
| **Especificação de Caso de Uso** | Descreve os fluxos principais e alternativos de cada funcionalidade. |
| **Diagramas de Sequência**       | Mostra a interação entre os componentes do sistema para cada caso de uso. |
| **Diagramas de Estados**         | Representa os estados e transições de um objeto (se aplicável). |
| **Diagrama de Classes**          | Representa a estrutura do sistema, com classes, atributos e métodos. |
| **DER Lógico**                   | Modelo do banco de dados, com tabelas, chaves e relacionamentos. |
| **Telas**       | Protótipos das interfaces do sistema e refinamentos. |
| **Workflow As-Is e To-Be**       | Descreve o processo atual (As-Is) e o processo desejado (To-Be). |
| **Diagrama de Implantação**      | Mostra a infraestrutura necessária para o deploy do sistema. |

### ❗ Importante: A Wiki é a Fonte Oficial
- **Toda documentação deve ser mantida na Wiki do GitHub**. Outras fontes (Google Drive, documentos locais, etc.) **não serão consideradas**.  
- **Atualize a Wiki continuamente**: Sempre que um documento ou artefato for criado ou modificado, ele deve ser imediatamente atualizado na Wiki.  
- **Organize o *Sidebar***: Use o arquivo `_sidebar.md` para criar um menu de navegação claro. Exemplo:  
  ```markdown
  - [Documento de Visão](/Visao)
  - [Casos de Uso](/CasosDeUso)
  - [Diagramas](/Diagramas)
  ```  

🌟 **Dica**: A Wiki é seu diário de bordo. Mantenha-a organizada e atualizada para garantir que todas as entregas sejam validadas corretamente! 🚀  




## ⚠️ Avisos Importantes

1. **Wiki é a Única Fonte Válida**:  
   - Toda documentação **deve estar na Wiki do GitHub**. Links externos, arquivos locais ou outras plataformas *não serão aceitos*.  
   - Mantenha o *sidebar* organizado e atualizado. Se não estiver visível, seu trabalho pode ser considerado incompleto.  

2. **TAGs são Obrigatórias**:  
   - Cada entrega exige uma **TAG no GitHub** com link postado no Google Classroom.  
   - Sem a TAG, a entrega *não existe oficialmente*.  

3. **Papel do Orientador**:  
   - Ele é seu **Agile Master** (PO + Scrum Master).  
   - Você *não pode* apresentar nas bancas (Unidades 2 e 4) sem um **atestado de aptidão** assinado por ele.
   - Faltar a orientações (25%) gera reprovação.

4. **Comunicação é Chave**:  
   - Mudanças no cronograma? Bloqueios técnicos? **Avise seu orientador imediatamente**.  
   - Falta de comunicação recorrente = **reprovação**.  

5. **Documentação Progressiva**:  
   - Até a Unidade 2, todos os documentos básicos (Visão, Workflow, Glossário) *devem estar completos*.  
   - Diagramas de novos casos de uso são adicionados apenas nas unidades em que forem desenvolvidos.  

6. **Repositório Privado**:  
   - Se não adicionar seu orientador como *maintainer*, seu projeto *não será avaliado*.  

---

## ❓ FAQ (Perguntas Frequentes)


### Q1: E se eu precisar alterar o escopo do projeto?  
**R**: Não há problemas, desde que comunique seu orientador e cumpra as entregas.   

### Q2: O que acontece se eu esquecer de criar uma TAG?  
**R**: A entrega será considerada **incompleta**. Entregas tardias poderá acarretar em perderdas pontos.  

### Q3: O que acontece se eu atualizar a Wiki fora do prazo?  
**R**: Atualizações tardias serão **desconsideradas**. A Wiki é avaliada *no momento da TAG*.  

### Q4: Como sei se estou apto para a banca (Unidades 2 e 4)?  
**R**: Seu orientador emitirá um **atestado de aptidão** após validar:  
- Unidade 2: Pelo menos 1 caso de uso funcional + diagramas e artefatos.  
- Unidade 4: Sistema 100% funcional + relatório final + diagramas e artefatos completos.

### Q5: E se eu tiver algum problema ou dúvidas?  
**R**: Converse com seu orientador, pois ele é aquele que te avaliará durante todo o processo e poderá te orientar.

### Q6: E se eu trocar de projeto ao avançar uma unidade curricular?  
**R**: Se você mudar de projeto entre uma unidade e outra, será necessário refazer todas as entregas das unidades anteriores, pois cada unidade é sequencial e depende do trabalho desenvolvido nas etapas prévias. Isso inclui documentação, diagramas e qualquer outro artefato já entregue. 

### Q8: Como fazer estágio no NPI? 
**R**: Marque um reunião com o Coordenador do NPI no e-mail joao.andrade@unifil.br

### Q7: Quero fazer estágio no NPI, as regras são as mesmas?  
**R**: Sim! porém podem ter regras adicionais.







---

🌟 **Dica Final**:  
Seu repositório é seu portfólio. Mantenha-o organizado, e você sairá não só aprovado, mas **preparado para o mercado**! 🚀  

---

