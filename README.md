# ESLint Config

**Pacote responsável por armazenar as configurações de Lint de projetos pessais.**

NPM: https://www.npmjs.com/package/@lucas.debeterco/eslint-config

No momento existem apenas configurações para linting em aplicações React.. Futuramente, mais configurações podem 
ser criadas e exportadas neste pacote.

## Instalação

Para instalar, basta executar:

```
npm i -D eslint @lucas.debeterco/eslint-config
```

Em seguida, crie o arquivo `.eslintrc.json` na raiz do projeto contendo o seguinte código:

```
{
  "extends": "@lucas.debeterco/eslint-config"
}
```
