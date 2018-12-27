# Adonis API application

This is the boilerplate for creating an API server in AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Authentication
3. CORS
4. Lucid ORM
5. Migrations and seeds

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick --api-only
```

or manually clone the repo and then run `npm install`.


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```

### Rodar
```bash
adonis serve --dev
```

### Start database 'MySQL' - pacote
```bash
npm i mysql
```


### Controller
```bash
adonis make:controller Auth
```

### Model
- **-m e -c** Criam automaticamente o migration e o controller
```bash
adonis make:model Tweet -m -c
```

### Verificar rotas criadas
```bash
adonis route:list
```