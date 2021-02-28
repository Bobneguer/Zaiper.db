# Zaiper.db
Zaiper.db, uma db que usa sqlite para apoio de dados.


### NPM
- `npm install zaiper.db`

# Base
```js
 const db = require('zaiper.db');
```

### Exemplos:
```js
  const db = require('zaiper.db');
  
  db.set('items', 'espada'); // => seta items como espara
  console.log(db.get('items')); // => 'espada'
  
  db.add('items', 'machado'); // => adiciona o machado oas intems
  console.log(db.get('items')); // => { 'espada', 'machado' }
  
```

Mais exemplos e informações sobre o uso da db [aqui!](https://zaiper.glitch.me)

