# API de Chamados de Suporte

**Estudante:** Saulo Victo Soares
**Matrícula N°:** 2025013853

## Objetivo
Criar a estrutura inicial da API de chamados de suporte em Python utilizando Flask e gerenciamento de ambiente e dependências com `uv`.

## Instalação das Dependências
Para instalar as dependências exatas do projeto a partir do `uv.lock`, execute:

```bash
uv sync --locked
```

## Execução da Aplicação
Para iniciar o servidor localmente ou no GitHub Codespaces, execute:

```bash
uv run flask --app app run --host=0.0.0.0 --port=5000
```

## Acesso à Rota Inicial e Resposta Esperada
Com a aplicação em execução, acesse `http://localhost:5000/` pelo navegador ou faça uma requisição via terminal:

```bash
curl -i http://localhost:5000/
```

**Resposta esperada:**
* **Status HTTP:** `200 OK`
* **Cabeçalho:** `Content-Type: application/json`
* **Corpo (JSON):**
```json
{
  "mensagem": "API de chamados em funcionamento"
}
```