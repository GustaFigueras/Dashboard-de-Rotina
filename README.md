## ✨ Dashboard de Rotina Semanal - Sua Central de Comando

[![Status do Projeto](https://img.shields.io/badge/Status-Completo-brightgreen)](https://github.com/SEU_USUARIO/dashboard-de-rotina)
[![Tecnologias](https://img.shields.io/badge/Tecnologias-HTML%20%7C%20Tailwind%20%7C%20JS%20(Vanilla)-blue)](https://github.com/SEU_USUARIO/dashboard-de-rotina)
[![Licença](https://img.shields.io/badge/Licença-MIT-blue)](https://github.com/SEU_USUARIO/dashboard-de-rotina/blob/main/LICENSE)

Uma aplicação **Front-end puro** (HTML, CSS e JavaScript) desenvolvida para transformar o caos da vida diária em **consistência e clareza**. O projeto oferece um **Dashboard de Rotina Semanal** moderno, interativo e *mobile-first*, focado em **produtividade, saúde e autoconsciência**. O acompanhamento detalhado da rotina é feito através de uma *timeline* dinâmica, com persistência de dados via `localStorage`.

### 🖼️ Preview (Visão Geral)



---

### 💡 Destaques e Funcionalidades Chave

O Dashboard de Rotina é projetado para ser mais do que um simples checklist, incentivando a reflexão e o rastreamento inteligente.

#### 📅 1. Planejamento de Rotina Avançado
* **Linha do Tempo Dinâmica:** Estrutura a rotina de cada dia (Segunda a Domingo) em blocos de tempo visuais, facilitando a navegação e o acompanhamento.
* **Checklists Detalhados:** Cada bloco de tempo (`Ritual Matinal`, `Estudo Focado`, etc.) é um acordeão expansível com um *checklist* de micro-tarefas.
* **Frases Motivacionais:** Cada bloco de tempo possui uma **citação motivacional** relevante para o propósito daquele período.
* **Navegação Semanal:** Abas intuitivas permitem a troca rápida entre os dias da semana.

#### ✅ 2. Sistema de Rastreamento e Auto-Reflexão
* **Barra de Progresso Semanal:** Indicador visual que rastreia a porcentagem de dias concluídos na semana, incentivando a consistência.
* **Conclusão Inteligente:** Ao finalizar um dia, o sistema:
    1.  Calcula a **Taxa de Conclusão** das tarefas.
    2.  Se o dia estiver incompleto, solicita uma **Justificativa** (armazenada no relatório), promovendo a autocrítica.
* **Persistência de Dados:** Todos os estados dos *checklists*, conclusão dos dias e justificativas são salvos no **`localStorage`** do navegador.

#### 📊 3. Relatórios e Análise de Desempenho
* **Relatório Diário Detalhado:** Acessível via ícone 📄 nas abas dos dias concluídos, exibindo quais tarefas foram completadas e o porquê (justificativa).
* **Relatório Semanal Consolidado:** Sumariza o desempenho semanal, mostrando a quantidade de dias concluídos e a taxa de acerto geral para um *feedback* claro.

#### 🔧 4. Ferramentas de Bem-Estar (Modais)
Um painel de utilitários rápidos para monitorar a saúde:
| Ferramenta | Descrição |
| :--- | :--- |
| **Cálculo de Hidratação Diária** | Estima a ingestão de água recomendada com base no peso e nível de atividade física (Sedentário, Leve, Moderado, Intenso). |
| **Cálculo de IMC** | Avalia o Índice de Massa Corporal e fornece a classificação (Peso Normal, Sobrepeso, etc.). |

---

### 💻 Tecnologias Utilizadas

Este projeto foi construído puramente com tecnologias *front-end* e um design moderno.

| Categoria | Tecnologia | Justificativa de Uso |
| :--- | :--- | :--- |
| **Estrutura** | **HTML5** | Fornece a base semântica e o esqueleto da aplicação. |
| **Estilização** | **Tailwind CSS** | Framework *utility-first* para design responsivo, minimalista e com *dark mode* elegante. |
| **Interatividade** | **JavaScript (Vanilla)** | Motor do projeto, responsável por toda a lógica de estado, manipulação de DOM e cálculos. |
| **Armazenamento** | **`localStorage`** | Usado para persistir o progresso do usuário no navegador (dias concluídos e tarefas). |
| **Ícones** | **Phosphor Icons** | Biblioteca de ícones de alta qualidade para aprimorar a UX. |
| **Efeitos** | **Puro CSS** | Implementação de gradientes dinâmicos, efeitos *blur* e a **borda animada** no card do criador principal. |

---

### 🚀 Como Utilizar o Projeto

Como este é um projeto de uma única página (SPA) do lado do cliente, a execução é imediata.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SEU_USUARIO/dashboard-de-rotina.git](https://github.com/SEU_USUARIO/dashboard-de-rotina.git)
    ```
2.  **Acesse o diretório:**
    ```bash
    cd dashboard-de-rotina
    ```
3.  **Abra no Navegador:**
    Simplesmente clique duas vezes no arquivo **`index.html`** ou use o comando:
    ```bash
    start index.html # Windows
    open index.html  # macOS
    ```

---

### 🤝 Equipe de Colaboradores (O Time por Trás da Visão)

O desenvolvimento e a concepção deste projeto foram um esforço colaborativo. Agradecemos a todos os envolvidos por trazerem essa visão à vida!

| Nome | Função | Contribuição Principal |
| :--- | :--- | :--- |
| **Gustavo Figueiredo** | **Diretor & Arquiteto Chefe** | Visão inicial, liderança do desenvolvimento técnico e lógica central do *dashboard*. |
| **Pedro Daniel** | **Diretor de Arte** | Responsável pela identidade visual, UX/UI e a aplicação do estilo moderno com Tailwind. |
| Kauê Pinheiro | Consultor de Estratégia | Definição do fluxo de usuário, arquitetura de dados e principais recursos do projeto. |
| Marley Bezerra | Analista de Crítica | Fornecimento de *feedbacks* cruciais para refinamento e melhoria da usabilidade. |
| José Hailton | Curador de Ideias | Contribuição com sugestões de funcionalidades e novos conceitos de organização. |
| Thiago De Oliveira | Pesquisador de Conceitos | Pesquisa inicial sobre rotinas de alta performance e produtividade. |

<div style="text-align: center; margin-top: 20px;">
    <p>Os cards dos criadores na página incluem detalhes e um destaque visual com borda animada no arquiteto-chefe:</p>
    
</div>

---

### 🚀 Publicação e Deploy (GitHub Pages)

Para hospedar o projeto online gratuitamente e compartilhá-lo:

1.  Vá para o seu repositório no GitHub.
2.  Clique em **Settings** (Configurações).
3.  Vá para a seção **Pages**.
4.  Em "Source" (Origem), selecione a branch **`main`** e o diretório **`/(root)`**.
5.  Clique em **Save**. O seu projeto estará online no link fornecido pelo GitHub (ex: `https://SEU_USUARIO.github.io/dashboard-de-rotina/`).

---

**© 2025 Todos os direitos reservados.**