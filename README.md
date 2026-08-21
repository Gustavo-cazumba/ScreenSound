# 🎵 ScreenSound — Gerenciador de Músicas e Bandas

> Aplicação em C# / .NET desenvolvida durante a trilha de formação backend da Alura, simulando o ecossistema e gerenciamento de um serviço de streaming de música.

---

## 📌 Sobre o Projeto

O **ScreenSound** é um projeto prático e evolutivo construído passo a passo para consolidar o aprendizado em **C#** e ecossistema **.NET**. A aplicação evolui conforme o avanço nas etapas da trilha, partindo dos conceitos básicos de Orientação a Objetos até a persistência em Banco de Dados e criação de APIs RESTful.

---

## 🎓 Evolução do Projeto (Trilha Alura)

O repositório está organizado para refletir o avanço nas 3 etapas principais do curso:

- 🟢 **Fase 1: Fundamentos & Lógica**
  - Aplicação console simples.
  - Regras de negócio iniciais, cadastro de bandas e avaliação de notas em memória.
  
- 🟡 **Fase 2: Orientação a Objetos & Coleções**
  - Implementação de pilares de OO (Encapsulamento, Herança, Polimorfismo e Abstração).
  - Organização de Entidades (`Banda`, `Álbum`, `Música`, `Avaliação`).
  - Consumo de APIs externas e manipulação de arquivos JSON com C#.

- 🔵 **Fase 3: Persistência de Dados & API REST (ASP.NET)**
  - Integração com Banco de Dados Relacional (LINQ e Entity Framework Core).
  - Mapeamento e relacionamento entre tabelas.
  - Construção de endpoints com Web API REST para gerenciamento completo do catálogo.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** C#
- **Plataforma:** .NET
- **Persistência / Banco de Dados:** Entity Framework Core / LINQ / SQL
- **Ferramentas:** Visual Studio / VS Code / Git

---

## 🚀 Funcionalidades

- [x] Cadastrar bandas, álbuns e músicas.
- [x] Registrar e calcular média de avaliações das bandas e álbuns.
- [x] Exibir detalhes e discografia completa do artista.
- [x] Persistência de dados e relacionamento entre entidades (`1:N` / `N:N`).
- [ ] API Endpoints para consulta e cadastro via HTTP (*Fase 3*).

---

## 🗄️ Estrutura das Entidades

```text
[ Banda ] 1 --- N [ Álbum ] 1 --- N [ Música ]
    |                 |
    +---- N:1 ----+---+----> [ Avaliação ]]
```
---

---

## 📁 Como Executar o Projeto

### Pré-requisitos
- .NET SDK instalado (versão 8.0 ou superior recomendada).
- IDE de sua preferência (Visual Studio / VS Code).

### Passo a Passo

1. **Clone este repositório:**
`git clone https://github.com/SEU_USUARIO/ScreenSound.git`

2. **Acesse a pasta do projeto:**
`cd ScreenSound`

3. **Restaure as dependências e execute:**
`dotnet restore`
`dotnet run`

---

Feito com 💙 por [Gustavo](git@github.com:Gustavo-cazumba/ScreenSound.git) durante os estudos na **Alura**!
