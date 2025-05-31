# Documento de Visão e Escopo do Projeto: [Nome do Projeto]

**Versão:** 1.0
**Data:** 31 de maio de 2025

---

### 1. Visão Geral do Projeto
**(O que estamos a construir e porquê?)**

* **O Problema:** Estudantes universitários das áreas de exatas e humanas enfrentam dificuldades em organizar os seus estudos, testar os seus conhecimentos de forma eficaz e manter a motivação ao longo do semestre.
* **A Solução:** Desenvolver um software web que funcione como um assistente de estudo centralizado, oferecendo ferramentas de criação de quizzes, cronogramas e, futuramente, mapas mentais e gamificação para estimular o aprendizado contínuo.
* **Público-Alvo:** Principalmente estudantes universitários das disciplinas de Arquitetura de Computadores, Cidadania/Ética, Engenharia de Software, Cálculo (Limite e Derivada) e Requisitos de Software.

### 2. Objetivos
**(O que queremos alcançar?)**

* Aumentar a eficiência dos estudantes na preparação para avaliações.
* Melhorar a organização e o planeamento dos estudos.
* Aumentar o engajamento e a motivação dos estudantes com o conteúdo das disciplinas.
* Criar uma ferramenta flexível e fácil de usar.

### 3. Escopo do MVP (Mínimo Produto Viável)
**(O que a primeira versão vai fazer?)**

**Funcionalidades INCLUÍDAS:**

1.  **Gestão de Utilizadores:**
    * Registo de nova conta (nome, email, senha).
    * Login e Logout.
2.  **Geração de Quizzes:**
    * O utilizador pode criar um novo quiz para uma disciplina específica.
    * O utilizador pode adicionar perguntas de múltipla escolha ou verdadeiro/falso ao quiz.
    * O utilizador pode realizar um quiz criado, recebendo a pontuação no final.
3.  **Cronograma de Estudos:**
    * O utilizador pode adicionar tarefas de estudo (ex: "Ler capítulo 3 de Arquitetura de Computadores").
    * O utilizador pode definir uma data e hora para cada tarefa.
    * O utilizador pode marcar uma tarefa como "concluída".

**Funcionalidades EXCLUÍDAS (para futuras versões):**

* Geração automática de quizzes por IA.
* Criação de mapas mentais.
* Sistema de gamificação (pontos, medalhas, rankings).
* Integração com calendários externos.

### 4. Requisitos Não Funcionais
**(Como o sistema deve ser?)**

* **Usabilidade:** A interface deve ser intuitiva e limpa.
* **Desempenho:** As páginas devem carregar rapidamente.
* **Responsividade:** O site deve funcionar bem em desktops e telemóveis.
* **Segurança:** As senhas dos utilizadores devem ser armazenadas de forma segura (hash).

### 5. Stack Tecnológica Proposta
**(Quais ferramentas vamos usar?)**

* **Front-End:** React ou Vue.js
* **Back-End:** Node.js com Express.js
* **Banco de Dados:** MongoDB ou PostgreSQL

---
