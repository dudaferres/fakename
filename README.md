﻿# fakename

## Documentação do Serviço index.js

### Visão Geral
O arquivo `index.js` contém uma função que gera nomes aleatórios combinando um nome e um sobrenome de listas predefinidas.

### Funcionalidade
A função `fakename()` exportada pelo módulo seleciona aleatoriamente:
- Um nome da lista: 'Ana', 'Bia', 'João', 'Julio'
- Um sobrenome da lista: 'Alface', 'Melão', 'Goiaba', 'Cenoura'

E retorna uma string com o nome e sobrenome concatenados.

### Como Usar
```javascript
import fakename from './index.js';

// Gera e exibe um nome aleatório
console.log(fakename());
// Exemplo de saída: "Ana Melão" (o resultado varia a cada chamada)
```

### Detalhes Técnicos
- A função não aceita parâmetros
- A função sempre retorna uma string
- A combinação de nomes é aleatória, com 16 possibilidades diferentes (4 nomes × 4 sobrenomes)
