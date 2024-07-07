# CodeLabAPIUsuario

API de Usuario do CodLab

## Development Start

```bash
docker compose up --build
```

## Execução de testes

- Atenção: "attach" ao container para executar os testes.
- Caso não deseje obter os relatórios de cobertura, remova o sufixo `:cov` dos comandos abaixo.

### Unit

```bash
npm run test:cov
```

### E2E

```bash
npm run test:e2e:cov
```
