# fakename

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
// Exemplo de saída: "João Goiaba" (o resultado varia a cada chamada)
```

### Detalhes Técnicos
- A função não aceita parâmetros
- A função sempre retorna uma string
- A combinação de nomes é aleatória, com 16 possibilidades diferentes (4 nomes × 4 sobrenomes)
- Suporte completo a caracteres UTF-8 (acentuação e caracteres especiais)

### Observações
Este módulo foi desenvolvido para garantir compatibilidade com codificação UTF-8, permitindo o uso adequado de caracteres acentuados presentes nos nomes em português.

## Autor

- Gabriela Queiroga Cocuzza da Silva RM: 560035
- Julia Sayuri Yokoo RM: 560541
- Maria Eduarda Ferrés RM: 560418