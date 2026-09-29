# 🧭 App Northwind — Automação de Testes E2E

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Playwright](https://img.shields.io/badge/Playwright-45ba4b?logo=playwright&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-f7df1e?logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-versionamento-f05032?logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2088ff?logo=githubactions&logoColor=white)

Projeto de estudo profissional dedicado à automação de testes **End-to-End (E2E)** em uma aplicação real, utilizando **Playwright** e **JavaScript puro**.

O objetivo é desenvolver uma suíte de testes confiável, organizada e fácil de manter, aplicando boas práticas de qualidade de software, versionamento de código e integração contínua.

> [!IMPORTANT]
> Este README é um **documento vivo**. Ele será atualizado continuamente conforme novos cenários, recursos e aprendizados forem incorporados ao projeto.

## 🎯 Objetivos

- Automatizar fluxos críticos da aplicação Northwind.
- Praticar a criação de testes E2E claros e reutilizáveis.
- Organizar o projeto de forma escalável.
- Versionar o código com Git e GitHub via SSH.
- Executar os testes automaticamente com GitHub Actions.
- Produzir evidências e relatórios de execução.

## 🛠️ Tecnologias

| Ferramenta | Finalidade |
| :--- | :--- |
| **Playwright** | Criação e execução dos testes automatizados E2E. |
| **JavaScript** | Implementação dos cenários, utilitários e configurações. |
| **Node.js** | Ambiente de execução do projeto e gerenciamento de dependências. |
| **Git** | Controle de versão local. |
| **GitHub** | Hospedagem do repositório e colaboração via SSH. |
| **GitHub Actions** | Execução automatizada dos testes no pipeline de CI/CD. |

## ✅ Progresso do projeto

- [ ] Ambiente configurado
- [ ] Git inicializado
- [ ] Repositório remoto conectado via SSH
- [ ] Playwright instalado
- [ ] Primeiro teste E2E criado
- [ ] Estrutura do projeto organizada
- [ ] Relatórios de teste configurados
- [ ] Pipeline de CI/CD configurado no GitHub Actions

## 📋 Pré-requisitos

Antes de começar, instale:

- [Node.js](https://nodejs.org/) em uma versão LTS recente;
- [Git](https://git-scm.com/);
- uma conta no [GitHub](https://github.com/) com acesso por SSH configurado.

Para conferir as versões instaladas:

```bash
node --version
npm --version
git --version
```

## 🚀 Instalação

### 1. Clone o repositório via SSH

```bash
git clone git@github.com:SEU_USUARIO/app-northwind.git
cd app-northwind
```

> [!NOTE]
> Substitua `SEU_USUARIO` pelo nome da sua conta no GitHub.

### 2. Instale as dependências

```bash
npm install
```

### 3. Instale os navegadores do Playwright

```bash
npx playwright install
```

### 4. Execute os testes

```bash
npx playwright test
```

Para acompanhar a execução com a interface visual do Playwright:

```bash
npx playwright test --ui
```

Para abrir o relatório HTML da última execução:

```bash
npx playwright show-report
```

## 📁 Estrutura de pastas

```tree
app-northwind/
├── .github/
│   └── workflows/
│       └── playwright.yml
├── tests/
│   ├── e2e/
│   ├── fixtures/
│   └── pages/
├── utils/
├── .gitignore
├── package.json
├── package-lock.json
├── playwright.config.js
└── README.md
```

### Responsabilidades principais

- `tests/e2e/`: cenários de teste E2E.
- `tests/fixtures/`: dados e configurações compartilhados entre os testes.
- `tests/pages/`: Page Objects e abstrações das páginas da aplicação.
- `utils/`: funções auxiliares reutilizáveis.
- `.github/workflows/`: definições dos pipelines do GitHub Actions.
- `playwright.config.js`: configuração central do Playwright.

## 🧪 Comandos úteis

```bash
# Executa toda a suíte de testes
npx playwright test

# Executa os testes em modo visual
npx playwright test --headed

# Executa um arquivo específico
npx playwright test tests/e2e/exemplo.spec.js

# Executa os testes em modo de depuração
npx playwright test --debug

# Abre o relatório HTML
npx playwright show-report
```

## 🤝 Evolução contínua

Este projeto faz parte de uma jornada prática de desenvolvimento profissional em **QA Automation**. Cada novo teste representa uma oportunidade de melhorar a cobertura, a confiabilidade e a clareza da suíte.

À medida que o projeto evoluir, este documento será atualizado com novos cenários, decisões técnicas, comandos e aprendizados.

---

Feito com dedicação, curiosidade e foco em qualidade. 🚀
