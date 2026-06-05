# 📊 OmniDRE - Automação Comercial & Inteligência Financeira

Este é um projeto de software livre (código aberto) desenvolvido em **Python** e **Django**. O objetivo é criar um ecossistema de automação comercial totalmente integrado, onde as rotinas de vendas e estoque alimentam o fluxo de caixa para gerar automaticamente uma **DRE (Demonstração do Resultado do Exercício)** e fornecer análises financeiras inteligentes para micro e pequenas empresas.

---

## 🚀 Status do Projeto & Colaboração
Eu conheço profundamente as regras de negócios de finanças e DRE, mas estou iniciando minha jornada na programação. O projeto está no **estágio zero**!

Procuro desenvolvedores, estudantes e entusiastas que queiram colaborar construindo o sistema do zero, evoluindo a arquitetura e aplicando boas práticas em Django. Todas as tarefas iniciais estão mapeadas na aba de **Issues** do repositório.

---

## 🎛️ Arquitetura do Painel Central (Dashboard)
A tela inicial do software funcionará como o ponto central de navegação da empresa, dividida nos seguintes grandes macro-módulos interligados:

*   📦 **ESTOQUE:** Cadastro de produtos, controle de entradas/saídas, relatórios e inventário.
*   🛒 **VENDAS:** Frente de caixa (PDV), envio de pedidos e baixa automática de estoque.
*   👥 **CADASTROS:** Gerenciamento de Clientes, Fornecedores e Usuários do sistema.
*   💰 **FINANCEIRO:** Controle de fluxo de caixa (contas a pagar/receber) e geração automatizada da DRE.

---

## 🧱 Escopo do MVP (Acompanhe pelas Issues)

Para o desenvolvimento do MVP, dividimos o sistema em tarefas modulares. Você pode clicar nos links abaixo para ver os detalhes e assumir o desenvolvimento de uma funcionalidade:

- [ ] **Módulo de Autenticação:** Login, logout e níveis de acesso nativos. (Ver Issue #1)
- [ ] **Módulo de Clientes:** Cadastro básico com validações de campos e CEP. (Ver Issue #2)
- [ ] **Módulo de Produtos/Serviços:** Estrutura e controle de estoque integrado. (Ver Issue #3)
- [ ] **Módulo de Vendas:** Frente de Caixa (PDV) com baixa automática de estoque. (Ver Issue #4)
- [ ] **Módulo de Fornecedores:** Cadastro estruturado com automação de CEP e CNPJ. (Ver Issue #5)
- [ ] **Módulo de Contas a Pagar:** Fluxo integrado desde a nota de entrada até a quitação. (Ver Issue #6)
- [ ] **Módulo de Contas a Receber:** Gestão de faturamento a prazo integrado ao cliente. (Ver Issue #7)
- [ ] **Módulo de Controle de Caixa:** Extrato dinâmico baseado em Plano de Contas nativo. (Ver Issue #8)
- [ ] **Módulo DRE (Cérebro do APP):** Motor de cálculo para gerar o relatório consolidado por período com visões gerenciais. (Ver Issue #9)

---

## 🛠️ Tecnologias Propostas
*   **Backend:** Python 3.x / Framework Django
*   **Banco de Dados:** SQLite (para desenvolvimento) / PostgreSQL (produção)
*   **Frontend Inicial:** Templates Django + Tailwind CSS (ou Bootstrap)

---

## 🤝 Como Contribuir
1. Faça um **Fork** do projeto.
2. Acesse a aba de **Issues**, escolha uma das tarefas abertas e comente que deseja trabalhar nela.
3. Crie uma **Branch** para sua modificação (`git checkout -b feature/nome-da-feature`).
4. Abra um **Pull Request** detalhando suas alterações e citando o número da Issue resolvida (Ex: `Fixes #1`).
