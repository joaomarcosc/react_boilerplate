# Boilerplate para futuros projetos react

Projeto completamente configurado: Eslint, prettier, editorconfig...

## Execução e instalação:

**_Instalação de dependências_**

```
   yarn install
```

**_Rodar projeto_**

```
  yarn start
```

### Altere o nome do projeto no package.json

**_package.json_**

```json
{
  "name": "seu_projeto"
}
```

## Para configurar o alias à seu gosto basta seguir os passos à seguir:

**_tsconfig.extend.json_**

```json
{
  "compilerOptions": {
    "baseUrl": "./src",
    "paths": {
      "@Card": ["./components/Card/index.tsx"]
    }
  }
}
```

**_No seu componente_**

```javascript
import Card from '@Card';
```
