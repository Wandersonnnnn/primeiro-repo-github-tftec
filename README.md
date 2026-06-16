# primeiro-repo-github-tftec

Projeto simples em Node.js/Express criado para fins didáticos, com exemplos de padrões inseguros para demonstração em revisão de código e análise de segurança.

## Para que este projeto serve

- Demonstrar vulnerabilidades comuns em aplicações web.
- Facilitar testes com ferramentas como CodeQL.
- Servir como base de estudo sobre riscos de segurança (ex.: SQL Injection e XSS).

## Como utilizar

1. Instale as dependências:

```bash
npm install
```

2. Analise o arquivo `app.js` para ver os endpoints de demonstração:
   - `GET /user`: exemplo de montagem insegura de query (SQL Injection).
   - `GET /hello`: exemplo relacionado a entrada de usuário em resposta HTML.

3. Execute as análises de segurança no repositório (por exemplo, com CodeQL no GitHub) para observar os alertas esperados.

## Aviso

Este código é de demonstração e não deve ser usado em produção.