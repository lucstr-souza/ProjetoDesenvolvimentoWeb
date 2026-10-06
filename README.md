# 📚 Estante

> **Aplicação Web para Organização e Acompanhamento de Leituras**

![Status](https://img.shields.io/badge/status-em_desenvolvimento-yellow)
![Versão](https://img.shields.io/badge/versão-0.1.0-blue)
![Licença](https://img.shields.io/badge/licença-acadêmica-lightgrey)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![Django](https://img.shields.io/badge/Django-Web_Framework-green)

**Instituição:** [UniCEUB]
**Curso:** [Ciência da Computação]
**Disciplina:** [Desenvolvimento Web]
**Turma / Semestre:** 2026.2
**Professor(a):** [Felippe Pires]
**Status do projeto:** Em desenvolvimento - Fase 1

---

## Sumário

* [1. Descrição do projeto](#1-descrição-do-projeto)
* [2. Funcionalidades](#2-funcionalidades)
* [3. Demonstração](#3-demonstração)
* [4. Tecnologias utilizadas](#4-tecnologias-utilizadas)
* [5. Arquitetura](#5-arquitetura)
* [6. Organização dos diretórios](#6-organização-dos-diretórios)
* [7. Participantes](#7-participantes)
* [8. Como executar](#8-como-executar)
* [9. Configuração](#9-configuração)
* [10. Testes](#10-testes)
* [11. Uso de inteligência artificial](#11-uso-de-inteligência-artificial)
* [12. Contribuição e fluxo de trabalho](#12-contribuição-e-fluxo-de-trabalho)
* [13. Histórico de versões](#13-histórico-de-versões)
* [14. Limitações e próximos passos](#14-limitações-e-próximos-passos)
* [15. Licença, referências e contato](#15-licença-referências-e-contato)

---

## 1. Descrição do projeto

O **Estante** é uma aplicação web destinada à organização de bibliotecas pessoais e ao acompanhamento do hábito de leitura. O projeto tem como objetivo centralizar informações sobre os livros de cada usuário, permitindo o gerenciamento da biblioteca e o registro do progresso das leituras em um único ambiente.

A aplicação busca solucionar dificuldades relacionadas à organização dos livros, ao acompanhamento das obras já concluídas e à identificação daquelas que ainda estão pendentes ou em andamento. Além disso, permitirá registrar sessões de leitura, atribuir notas aos livros, definir metas anuais e consultar indicadores sobre o próprio desempenho.

Para facilitar o cadastro das obras, o Estante contará com integração à **Open Library**, serviço externo que possibilita pesquisar e obter informações bibliográficas para auxiliar o preenchimento dos dados dos livros.

O projeto será desenvolvido utilizando Python e Django, com banco de dados relacional e uma API REST própria. A solução também contempla autenticação, controle de acesso, relatórios e medidas de segurança para proteger as informações dos usuários.

### Objetivos

**Objetivo geral:** desenvolver uma aplicação web que permita organizar uma biblioteca pessoal e acompanhar o hábito de leitura por meio do gerenciamento de livros, registros, metas e indicadores.

**Objetivos específicos:**

* Permitir o cadastro e a autenticação de usuários.
* Garantir o isolamento dos dados entre diferentes contas.
* Possibilitar o cadastro manual e a consulta de livros na Open Library.
* Permitir a edição, consulta e exclusão de livros.
* Registrar o status, as notas e o progresso das leituras.
* Registrar sessões de leitura, páginas lidas e tempo dedicado, quando informado.
* Permitir a definição e o acompanhamento de metas anuais.
* Disponibilizar relatórios e indicadores sobre as atividades de leitura.
* Permitir a exportação de relatórios em CSV e a impressão.
* Disponibilizar uma API REST documentada.
* Aplicar práticas de segurança durante o desenvolvimento e a publicação.

### Problema atendido

A utilização de planilhas, anotações e ferramentas diferentes pode dificultar a centralização das informações de uma biblioteca pessoal. O Estante propõe uma solução integrada para organizar livros, registrar o histórico de leitura e acompanhar metas individuais.

### Público-alvo

* Estudantes que desejam organizar suas leituras.
* Leitores que desejam manter uma biblioteca pessoal organizada.
* Leitores frequentes interessados em acompanhar metas anuais e indicadores.
* Desenvolvedores e aplicações que tenham interesse em consumir os recursos disponibilizados pela API REST, respeitando as regras de acesso.

---

## 2. Funcionalidades

As funcionalidades abaixo representam o escopo previsto para o projeto. O status deverá ser atualizado conforme o desenvolvimento e a realização dos testes.

| Funcionalidade              | Descrição                                                     | Status    |
| --------------------------- | ------------------------------------------------------------- | --------- |
| Cadastro de usuários        | Criação de contas individuais                                 | Planejada |
| Autenticação                | Entrada e encerramento de sessão                              | Planejada |
| Gerenciamento de livros     | Cadastro, consulta, edição e exclusão                         | Planejada |
| Integração com Open Library | Pesquisa e obtenção de dados bibliográficos                   | Planejada |
| Pesquisa e filtros          | Busca por título, autor, gênero, status e nota                | Planejada |
| Status de leitura           | Organização por Quero ler, Lendo, Lido e Abandonado           | Planejada |
| Avaliação de livros         | Registro de notas para as obras                               | Planejada |
| Sessões de leitura          | Registro de páginas e tempo de leitura                        | Planejada |
| Progresso da leitura        | Acompanhamento das leituras em andamento                      | Planejada |
| Meta anual                  | Definição e acompanhamento de metas                           | Planejada |
| Relatórios                  | Indicadores consolidados da biblioteca e das leituras         | Planejada |
| Exportação CSV              | Exportação dos dados dos relatórios                           | Planejada |
| Impressão                   | Versão dos relatórios adequada para impressão                 | Planejada |
| API REST                    | Disponibilização dos recursos da aplicação                    | Planejada |
| Segurança                   | Autenticação, autorização e proteção de informações sensíveis | Planejada |

### Requisitos não funcionais

* **Segurança:** proteger as informações dos usuários, controlar o acesso aos recursos e impedir a exposição de credenciais.
* **Integridade:** manter os registros associados corretamente às respectivas contas.
* **Usabilidade:** organizar as funcionalidades de forma clara e facilitar o gerenciamento das leituras.
* **Responsividade:** permitir a utilização da aplicação em diferentes tamanhos de tela.
* **Confiabilidade:** tratar erros de validação e possíveis falhas de comunicação com a Open Library.
* **Manutenibilidade:** manter o código-fonte e a documentação organizados.
* **Disponibilidade:** disponibilizar a aplicação na internet após a conclusão da etapa de implantação.

---

## 3. Demonstração

As capturas de tela e os registros de funcionamento serão adicionados conforme as funcionalidades forem implementadas.

### Telas previstas

| Tela               | Descrição                                                  |
| ------------------ | ---------------------------------------------------------- |
| Autenticação       | Entrada do usuário na aplicação                            |
| Biblioteca pessoal | Visualização dos livros cadastrados                        |
| Cadastro de livros | Registro manual ou preenchimento com dados da Open Library |
| Detalhes do livro  | Consulta das informações e do progresso de leitura         |
| Sessões de leitura | Registro e consulta do histórico                           |
| Metas anuais       | Acompanhamento da meta definida                            |
| Relatórios         | Visualização de indicadores e exportação dos dados         |

**Aplicação publicada:** a definir após a implantação.

**Documentação da API:** a definir após a implementação e publicação da documentação.

---

## 4. Tecnologias utilizadas

As tecnologias previstas para o desenvolvimento são:

| Camada             | Tecnologia       | Finalidade                                      |
| ------------------ | ---------------- | ----------------------------------------------- |
| Linguagem          | Python           | Desenvolvimento do backend                      |
| Framework web      | Django           | Estrutura e regras da aplicação                 |
| Banco de dados     | Banco relacional | Armazenamento dos usuários, livros e registros  |
| API                | REST             | Disponibilização de recursos da aplicação       |
| Integração externa | Open Library     | Pesquisa de informações bibliográficas          |
| Controle de versão | Git              | Gerenciamento do histórico do código            |
| Repositório        | GitHub           | Hospedagem do código e colaboração              |
| Documentação       | Markdown e PDF   | Registro dos artefatos do projeto               |
| Segurança          | SAST e DAST      | Análises de segurança previstas para a Fase 2   |
| Comunicação segura | HTTPS            | Proteção da comunicação na publicação da Fase 2 |

As versões específicas das tecnologias deverão ser registradas conforme o ambiente de desenvolvimento e os arquivos de dependências do projeto.

---

## 5. Arquitetura

O Estante será organizado em torno de uma aplicação web desenvolvida em Django, responsável por processar as solicitações, aplicar as regras de negócio e acessar o banco de dados relacional.

A API REST disponibilizará os recursos definidos para o sistema. A integração com a Open Library será utilizada no fluxo de pesquisa e obtenção de informações bibliográficas para auxiliar o cadastro de livros.

### Fluxo geral da aplicação

```text
             USUÁRIO
                |
                v
       APLICAÇÃO WEB ESTANTE
                |
                v
       BACKEND EM DJANGO
                |
        +-------+--------+
        |                |
        v                v
 BANCO DE DADOS     API REST PRÓPRIA
                         |
                         v
                 CONSUMIDORES DA API

Integração bibliográfica:
Estante → Open Library → Dados dos livros → Revisão → Cadastro
```

### Componentes principais

* **Aplicação web:** interface utilizada pelo leitor.
* **Backend:** processamento das solicitações e aplicação das regras de negócio.
* **Banco de dados:** armazenamento dos usuários, livros, sessões e metas.
* **API REST:** disponibilização dos recursos da aplicação.
* **Open Library:** serviço externo para consulta de informações bibliográficas.

### Endpoints da API

Os endpoints definitivos serão documentados após a definição do contrato da API e sua implementação.

| Método HTTP | Recurso            | Finalidade                                                    |
| ----------- | ------------------ | ------------------------------------------------------------- |
| A definir   | Usuários           | Recursos relacionados às contas, conforme as regras de acesso |
| A definir   | Livros             | Cadastro, consulta, edição e exclusão                         |
| A definir   | Sessões de leitura | Registro e consulta das sessões                               |
| A definir   | Metas              | Gerenciamento das metas anuais                                |
| A definir   | Relatórios         | Consulta dos indicadores e dados consolidados                 |

**Documentação completa da API:** será disponibilizada após a implementação, com rotas, métodos HTTP, parâmetros, respostas e códigos de status.

---

## 6. Organização dos diretórios

O repositório será organizado para separar o código-fonte, a documentação, os diagramas e as evidências de segurança.

```text
estante/
├── README.md
├── .gitignore
├── .env.example
├── requirements.txt
├── manage.py
├── docs/
│   ├── README.md
│   ├── visao-do-projeto.md
│   ├── arquitetura/
│   ├── modelagem/
│   ├── diagramas/
│   ├── api/
│   └── seguranca/
├── images/
├── estante/
│   ├── settings.py
│   ├── urls.py
│   └── ...
├── [aplicativos Django]/
├── tests/
└── .github/
    └── workflows/
```

*Estrutura de referência: os diretórios e arquivos deverão corresponder à organização efetivamente adotada pelo grupo.*

| Diretório ou arquivo | Finalidade                                                      |
| -------------------- | --------------------------------------------------------------- |
| `README.md`          | Página inicial do projeto e instruções gerais                   |
| `.gitignore`         | Arquivos que não devem ser versionados                          |
| `.env.example`       | Modelo das variáveis de ambiente, sem segredos                  |
| `requirements.txt`   | Dependências Python do projeto                                  |
| `manage.py`          | Ferramenta de administração do Django                           |
| `docs/`              | Documentação técnica e acadêmica                                |
| `docs/diagramas/`    | Diagramas do projeto                                            |
| `docs/seguranca/`    | Evidências, resultados e registros de segurança                 |
| `docs/api/`          | Contrato e documentação da API                                  |
| `images/`            | Capturas de tela e imagens de apresentação                      |
| `tests/`             | Testes automatizados                                            |
| `.github/workflows/` | Configurações de automação do GitHub Actions, quando utilizadas |

---

## 7. Participantes

O projeto será desenvolvido colaborativamente. Os nomes, as responsabilidades e as matrículas devem ser preenchidos pelos integrantes.

| Nome                   | Matrícula   | Responsabilidade              |
| ---------------------- | ----------- | ----------------------------- |
| [Isabella Silva e Sena] | [Matrícula] | [Responsabilidade no projeto] |
| [Luísa Castro Souza] | [Matrícula] | [Responsabilidade no projeto] |
| [Maria Eduarda Almeida Campelo] | [Matrícula] | [Responsabilidade no projeto] |

**Professor(a) responsável:** [Felippe Pires]

Todos os integrantes deverão possuir acesso ao repositório como colaboradores, contribuindo por meio de branches, commits e revisões das alterações.

---

## 8. Como executar

As instruções abaixo representam um procedimento inicial para um projeto Django. Os comandos deverão ser ajustados se a estrutura definitiva, as dependências ou a configuração do banco de dados forem diferentes.

### Pré-requisitos

* Git instalado.
* Python compatível com a versão definida no projeto.
* `pip` para instalação das dependências.
* Ambiente virtual Python recomendado.
* Banco de dados configurado conforme as definições do projeto.

### Instalação e execução local

**1. Clonar o repositório**

```bash
git clone URL_DO_REPOSITORIO
cd NOME_DO_REPOSITORIO
```

Substitua `URL_DO_REPOSITORIO` e `NOME_DO_REPOSITORIO` pelos dados reais do repositório criado a partir do template oficial.

**2. Criar um ambiente virtual**

No Windows:

```bash
python -m venv .venv
.venv\Scripts\activate
```

No Linux ou macOS:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

**3. Instalar as dependências**

```bash
pip install -r requirements.txt
```

**4. Configurar as variáveis de ambiente**

Crie um arquivo `.env` local com base no `.env.example`, preenchendo os valores necessários conforme a configuração implementada.

**5. Aplicar as migrações do banco de dados**

```bash
python manage.py migrate
```

**6. Executar a aplicação**

```bash
python manage.py runserver
```

**Acesso local:** http://127.0.0.1:8000/

A execução depende da existência do `manage.py`, das dependências e das configurações correspondentes. Caso a estrutura definitiva seja diferente, estas instruções deverão ser atualizadas.

### Implantação

* **Ambiente de hospedagem:** a definir.
* **URL da aplicação:** a definir após a publicação.
* **HTTPS:** previsto para a Fase 2.
* **Documentação da API publicada:** a definir.

---

## 9. Configuração

As variáveis de ambiente devem ser utilizadas para configurar os parâmetros necessários à execução da aplicação. Os nomes abaixo são referências iniciais e deverão ser alinhados às configurações efetivamente implementadas.

| Variável        | Obrigatória                            | Descrição                                       |
| --------------- | -------------------------------------- | ----------------------------------------------- |
| `SECRET_KEY`    | Sim, em configuração Django apropriada | Chave secreta utilizada pelo Django             |
| `DEBUG`         | Sim, conforme configuração             | Ativa ou desativa o modo de depuração           |
| `DATABASE_URL`  | Depende da configuração                | URL de conexão com o banco, caso seja utilizada |
| `ALLOWED_HOSTS` | Conforme o ambiente                    | Hosts autorizados pela configuração Django      |

A integração com a Open Library deverá utilizar o mecanismo de comunicação definido na implementação. Não se deve presumir a existência de uma chave de API se ela não for necessária.

### Cuidados com informações sensíveis

* Não publicar senhas, tokens ou chaves privadas.
* Não enviar o arquivo `.env` para o repositório.
* Manter o `.env.example` sem credenciais reais.
* Configurar valores sensíveis no ambiente de execução.
* Revisar os arquivos antes de realizar commits.
* Registrar evidências e resultados de segurança em `docs/seguranca/`, sem expor dados sensíveis.

---

## 10. Testes

Os testes deverão verificar o comportamento das funcionalidades, a integridade dos registros e o controle de acesso entre diferentes usuários.

### Categorias de testes previstas

| Tipo                       | Objetivo                                                                    |
| -------------------------- | --------------------------------------------------------------------------- |
| Unitários                  | Verificar regras de negócio e validações isoladas                           |
| Integração                 | Verificar a comunicação entre aplicação, banco de dados e serviços externos |
| API                        | Validar endpoints, parâmetros, respostas e códigos HTTP                     |
| Autenticação e autorização | Verificar o acesso permitido e negado aos recursos                          |
| Funcionais                 | Verificar os principais fluxos de gerenciamento de livros e leituras        |
| Relatórios                 | Conferir os cálculos dos indicadores e das metas                            |
| Segurança                  | Identificar vulnerabilidades e falhas de configuração                       |

Após a configuração do ambiente de testes, o comando utilizado deverá ser registrado nesta seção. Caso seja adotado o mecanismo de testes padrão do Django, poderá ser utilizado:

```bash
python manage.py test
```

**Ferramenta de testes:** a definir conforme a implementação.

**Cobertura de testes:** a medir após a implementação dos testes automatizados.

Os resultados efetivos deverão ser registrados com base na execução real dos testes, sem declarar funcionalidades ou verificações como concluídas antes da validação.

---

## 11. Uso de inteligência artificial

O uso de ferramentas de inteligência artificial no projeto deverá respeitar as orientações da disciplina e ser declarado de forma transparente.

### Declaração de uso

* **Houve uso de inteligência artificial?** [Preencher conforme o uso real].
* **Ferramentas utilizadas:** [Informar as ferramentas utilizadas ou declarar que nenhuma foi utilizada].
* **Finalidade:** [Descrever as atividades em que houve auxílio].
* **Atividades realizadas pelos integrantes:** [Descrever o trabalho efetivamente realizado pelo grupo].
* **Validação:** os integrantes deverão revisar e validar os materiais e o código antes de incorporá-los ao projeto.

A imagem da política de uso de IA indicada pelo template oficial poderá ser incluída em `images/`, conforme as orientações da disciplina.

---

## 12. Contribuição e fluxo de trabalho

O desenvolvimento será realizado por meio do Git e do GitHub, permitindo que os três integrantes contribuam de forma organizada e que as alterações sejam revisadas antes da integração.

### Repositório

O repositório deverá ser criado a partir do template oficial:

https://github.com/Felippe-Pires/template_projects

Após a criação, o grupo deverá configurar os integrantes como colaboradores e manter o histórico de desenvolvimento disponível para avaliação.

### Branches

Sugestão de organização:

* `main` — versão estável do projeto.
* `develop` — integração das funcionalidades, se adotada pelo grupo.
* `feat/nome-da-funcionalidade` — desenvolvimento de funcionalidades.
* `fix/nome-da-correcao` — correções.
* `docs/nome-da-documentacao` — alterações exclusivamente documentais.

### Padrão de commits

As mensagens devem ser curtas e descrever a alteração realizada.

Exemplos:

```text
feat: adiciona cadastro de livros
feat: integra pesquisa com Open Library
fix: corrige validação do status de leitura
docs: atualiza documentação da API
test: adiciona testes de gerenciamento de livros
```

### Processo de contribuição

1. Atualizar a branch de referência.
2. Criar uma branch para a alteração.
3. Implementar a funcionalidade ou documentação.
4. Executar os testes pertinentes.
5. Realizar o commit das alterações.
6. Abrir um Pull Request para revisão.
7. Corrigir eventuais problemas identificados.
8. Integrar as alterações após a revisão.

**Repositório do projeto:** [Inserir link do GitHub].

---

## 13. Histórico de versões

O histórico deverá registrar as principais entregas e alterações do projeto.

| Versão  | Data       | Descrição                                           |
| ------- | ---------- | --------------------------------------------------- |
| `0.1.0` | 2026-10-06 | Estrutura inicial da documentação do projeto        |
| `0.2.0` | A definir  | Atualização conforme os artefatos e a implementação |
| `1.0.0` | A definir  | Versão final após conclusão e validação             |

As versões e datas deverão ser atualizadas conforme as entregas efetivamente realizadas.

---

## 14. Limitações e próximos passos

### Limitações previstas

* A aplicação depende de conexão com a internet para consultar a Open Library.
* A disponibilidade e a completude dos dados bibliográficos dependem do serviço externo.
* O cadastro manual deverá permanecer disponível como alternativa em caso de indisponibilidade da integração.
* Os relatórios dependerão da consistência dos registros realizados pelos usuários.
* A aplicação ainda deverá passar pelas etapas de implementação, testes e publicação.

### Roadmap

* [ ] Finalizar os artefatos de análise e modelagem.
* [ ] Definir e implementar o modelo de dados.
* [ ] Implementar cadastro e autenticação de usuários.
* [ ] Implementar o gerenciamento da biblioteca pessoal.
* [ ] Integrar a pesquisa de livros com a Open Library.
* [ ] Implementar sessões e acompanhamento das leituras.
* [ ] Implementar metas anuais e relatórios.
* [ ] Desenvolver e documentar a API REST.
* [ ] Criar e executar os testes automatizados.
* [ ] Organizar as evidências de segurança.
* [ ] Realizar as análises SAST e DAST previstas para a Fase 2.
* [ ] Publicar a aplicação utilizando HTTPS na Fase 2.
* [ ] Atualizar a documentação para refletir a implementação final.

---

## 15. Licença, referências e contato

**Licença:** condições de uso a definir pelo grupo e pela disciplina.

O projeto possui finalidade acadêmica e educacional. A reutilização do código deverá respeitar a licença que vier a ser adotada e as orientações institucionais.

### Documentação complementar

Os documentos do projeto deverão ser organizados na pasta `docs/`.

* **Documento de visão:** `docs/visao-do-projeto.md` — descrição do problema, objetivos, escopo, requisitos e critérios de sucesso.
* **Diagramas:** `docs/diagramas/` — diagramas de arquitetura, casos de uso, classes e banco de dados, conforme produzidos.
* **Documentação da API:** `docs/api/` — contrato, endpoints e exemplos de requisições e respostas.
* **Segurança:** `docs/seguranca/` — evidências e resultados das verificações realizadas.
* **Índice da documentação:** `docs/README.md`.

Os links deverão ser ajustados para corresponder aos nomes e caminhos definitivos dos arquivos no repositório.

### Referências

* **Template oficial do repositório:** https://github.com/Felippe-Pires/template_projects
* **Django:** https://docs.djangoproject.com/
* **Python:** https://docs.python.org/3/
* **Open Library:** https://openlibrary.org/developers/api
* **GitHub Docs:** https://docs.github.com/

### Contato

**Repositório:** [Inserir link do repositório do Estante].

**Contato do grupo:** [Inserir e-mail institucional ou canal de contato].

**Agradecimentos:** aos docentes e materiais acadêmicos que orientam o desenvolvimento do projeto.

---

**Estante — organize seus livros, acompanhe suas leituras e transforme suas metas em progresso.**
