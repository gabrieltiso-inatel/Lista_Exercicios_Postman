## Como rodar

Para rodar o projeto, primeiro clone o repositório e acesse a pasta em sua máquina.
Depois disso basta executar:

```
npm install
```

Para gerar o relatório de testes:

```
node_modules/.bin/newman run <NOME_DA_SUA_COLLECTION>.json -r htmlextra
```
