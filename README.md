# 🏨 RobotBooker140 — Automação de Testes de API

## 📌 Sobre o projeto

O RobotBooker140 é um projeto de automação de testes de API desenvolvido com Robot Framework e RequestsLibrary, utilizando a API Restful Booker como ambiente de testes.

O projeto tem como objetivo validar operações de uma API REST, automatizando requisições HTTP e verificando códigos de status, respostas e dados retornados pela aplicação.

A automação também permite praticar a organização de testes, a reutilização de recursos e o gerenciamento de dados de teste.

## 🎯 Objetivos

- Automatizar testes funcionais de API REST.
- Validar requisições e respostas HTTP.
- Verificar códigos de status e dados retornados.
- Praticar operações de autenticação e gerenciamento de reservas.
- Organizar testes e keywords reutilizáveis.
- Utilizar dados externos para apoiar a execução dos cenários.

## 🛠️ Tecnologias utilizadas

- **Python** — ambiente de execução.
- **Robot Framework** — framework de automação.
- **RequestsLibrary** — biblioteca para requisições HTTP.
- **API Restful Booker** — aplicação utilizada nos testes.
- **JSON** — formato de dados para requisições e respostas.
- **Git e GitHub** — versionamento do projeto.

## 🧪 Cenários de teste

| Funcionalidade | Objetivo |
|---|---|
| Autenticação | Validar a geração de token de acesso. |
| Criação de reservas | Verificar o envio de dados para criar uma reserva. |
| Consulta de reservas | Validar a recuperação de informações. |
| Atualização de reservas | Verificar alterações nos dados de uma reserva. |
| Exclusão de reservas | Validar a remoção de registros, se implementada. |
| Status HTTP | Conferir os códigos de resposta esperados. |
| Validação de dados | Verificar os dados retornados pela API. |

*Os cenários devem ser ajustados conforme os testes efetivamente implementados no repositório.*

## ⚙️ Pré-requisitos

- Python instalado.
- Acesso à internet.
- Robot Framework.
- RequestsLibrary.

## 🚀 Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/Swellhenrique/RobotBooker140.git
```

### 2. Acesse a pasta do projeto

```bash
cd RobotBooker140
```

### 3. Crie um ambiente virtual

```bash
python -m venv venv
```

### 4. Ative o ambiente virtual

No Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Instale as dependências

```bash
pip install robotframework robotframework-requests
```

Se o projeto possuir um arquivo `requirements.txt`, utilize:

```bash
pip install -r requirements.txt
```

### 6. Execute os testes

```bash
robot -d results .
```

O comando executa os testes Robot Framework encontrados no diretório informado e direciona os relatórios para a pasta `results`.

O caminho pode precisar ser ajustado de acordo com a organização dos arquivos `.robot` do projeto.

## 📊 Relatórios de execução

Após executar os testes, o Robot Framework gera relatórios que ajudam a analisar os resultados:

- **report.html** — resumo da execução.
- **log.html** — detalhes das etapas, requisições e eventuais falhas.
- **output.xml** — resultados estruturados dos testes.

## 📚 Aprendizados

O desenvolvimento deste projeto contribui para o aprimoramento de conhecimentos em:

- Testes automatizados de APIs REST.
- Autenticação por token.
- Métodos HTTP e códigos de status.
- Validação de respostas JSON.
- Reutilização de keywords e arquivos de recursos.
- Organização e manutenção de testes automatizados.
- Análise de falhas e relatórios de execução.

## 👨‍💻 Autor

**Swell Henrique**

Estudante de Análise e Desenvolvimento de Sistemas, com foco em Quality Assurance (QA), testes de software e automação.

- **GitHub:** https://github.com/Swellhenrique

---

⭐ Projeto desenvolvido para aplicar conceitos de automação de testes de API e fortalecer meu portfólio na área de QA.
