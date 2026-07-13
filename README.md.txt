# 📚 Donnexa

> **Toda leitura deixa uma marca.**

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-8B5E3C)
![Versão](https://img.shields.io/badge/Versão-1.0-blue)
![Projeto](https://img.shields.io/badge/Projeto-Pessoal-success)
![Licença](https://img.shields.io/badge/Licença-MIT-green)

---

# 📖 Sobre o Projeto

O **Donnexa** é um projeto pessoal desenvolvido como parte da minha jornada de aprendizado em Tecnologia da Informação.

O objetivo é evoluir gradualmente uma simples planilha de controle de livros para uma plataforma completa de gerenciamento de biblioteca pessoal, acompanhamento de leituras e análise de hábitos de leitura.

Além de organizar minha biblioteca, o projeto serve como laboratório para o estudo de:

- Excel
- Power BI
- SQL Server
- Python
- Git/GitHub
- APIs
- Desenvolvimento Web
- Desenvolvimento Mobile

Cada etapa do desenvolvimento acompanha minha evolução como estudante de Análise e Desenvolvimento de Sistemas.

---

# 🎯 Missão

Transformar a organização de leituras em uma experiência simples, inteligente e agradável, permitindo que leitores acompanhem sua evolução ao longo dos anos.

---

# 🌎 Visão

Desenvolver uma plataforma moderna para leitores, unindo organização, análise de dados e comunidade em um único ambiente.

---

# ❤️ Valores

- Organização
- Simplicidade
- Evolução contínua
- Compartilhamento de conhecimento
- Experiência do usuário
- Qualidade dos dados
- Acessibilidade

---

# 👤 Público-alvo

Leitores que desejam:

- Organizar sua biblioteca
- Registrar leituras
- Acompanhar metas anuais
- Visualizar estatísticas
- Descobrir novos livros
- Compartilhar experiências de leitura

---

# 🎨 Identidade Visual

## Personalidade

- Intelectual
- Moderna
- Organizada
- Acolhedora

## Paleta de cores

| Cor | Hex |
|------|------|
| Fundo Principal | `#F8F5F2` |
| Marrom Escuro | `#402309` |
| Bordô | `#541111` |
| Vermelho Escuro | `#3C0404` |
| Verde Escuro | `#032A04` |
| Verde Principal | `#1A5108` |

---

# 📁 Estrutura do Projeto

```text
Donnexa/

│
├── excel/
│   └── biblioteca.xlsx
│
├── powerbi/
│   └── Donnexa.pbix
│
├── sql/
│
├── python/
│
├── api/
│
├── web/
│
├── app/
│
├── docs/
│
├── assets/
│
└── README.md
```

---

# 🗃️ Arquitetura de Dados

## 📚 tb_livros

Cadastro permanente dos livros.

Cada registro representa um único livro.

### Campos

- ID_Livro
- ISBN
- Titulo
- Subtitulo
- Volume
- Serie
- Autor
- Editora
- Numero_Paginas
- Genero
- Idioma
- URL_Capa
- Data_Cadastro
- Data_Atualizacao

---

## 📖 tb_leituras

Histórico completo das leituras.

Cada registro representa uma leitura.

Permite registrar:

- Primeira leitura
- Releituras
- Metas anuais
- Notas individuais
- Datas de leitura

### Campos

- ID_Leitura
- ID_Livro
- Tipo_Leitura
- Status_Leitura
- Data_Inicio
- Data_Conclusao
- Ano_Meta
- Nota_Pessoal
- Observacoes

---

## 📚 tb_biblioteca

Representa minha coleção pessoal.

### Campos

- ID_Livro
- Possui
- Lista_Desejos
- Origem
- Data_Aquisicao
- Formato

---

# 📊 Roadmap

## ✅ Sprint 1 — Fundação

### Concluído

- Estrutura do projeto
- Organização das pastas
- README inicial
- Nome oficial do projeto
- Missão
- Visão
- Valores
- Público-alvo
- Personalidade
- Identidade visual
- Paleta de cores
- Guia de estilo inicial

---

## ✅ Sprint 2 — Base de Dados (Excel)

### Concluído

- Criação da tabela `tb_livros`
- Conversão para tabela estruturada
- Cadastro dos livros
- Inclusão de ISBN
- Inclusão de URL das capas
- Inclusão de datas
- Inclusão de Ano_Meta
- Refatoração da modelagem
- Criação da `tb_leituras`
- Criação da `tb_biblioteca`

---

## 🚧 Sprint 3 — Business Intelligence

### Concluído

- Configuração do Power BI
- Criação do projeto `.pbix`
- Conexão com Excel
- Importação das tabelas
- Exploração da interface
- Criação da tabela Calendário
- Primeiras colunas em DAX
- Revisão completa da arquitetura dos dados

### Em andamento

- Relacionamentos
- Modelo estrela
- Medidas em DAX
- KPIs
- Dashboard v1

---

## 🔜 Próximas Sprints

### Sprint 4

SQL Server

### Sprint 5

Git e GitHub

### Sprint 6

Python

### Sprint 7

Automações

### Sprint 8

API REST

### Sprint 9

Website

### Sprint 10

Aplicativo Mobile

---

# 🚀 Tecnologias

## Utilizadas atualmente

- Microsoft Excel
- Power BI Desktop

## Futuras

- SQL Server
- Git
- GitHub
- Python
- FastAPI
- HTML
- CSS
- JavaScript
- React
- React Native

---

# 💡 Filosofia do Projeto

> Primeiro fazer funcionar.

> Depois fazer bonito.

> Depois fazer automático.

---

# 📈 Evolução

```text
Excel
      │
      ▼
Power BI
      │
      ▼
SQL Server
      │
      ▼
Python
      │
      ▼
API
      │
      ▼
Website
      │
      ▼
Aplicativo
```

---

# 🚧 Status Atual

## Sprint

**Sprint 3 — Business Intelligence**

### Última entrega

- Arquitetura da base de dados refatorada
- Separação em três tabelas
- Criação da tabela Calendário
- Primeiras colunas DAX

### Próxima missão

Criar os relacionamentos entre as tabelas e iniciar o desenvolvimento do Dashboard v1.

---

# 👨‍💻 Sobre este projeto

Este projeto está sendo desenvolvido de forma incremental como parte do meu processo de aprendizagem em tecnologia.

Cada sprint representa uma nova habilidade adquirida e uma evolução real do sistema.

O objetivo não é apenas criar uma aplicação funcional, mas também documentar toda a jornada de desenvolvimento.

---


## 📚 Slogan

> **Toda leitura deixa uma marca.**

---

## 👩‍💻 Desenvolvido por

**Médonne Penteado**

Graduanda em Análise e Desenvolvimento de Sistemas.




