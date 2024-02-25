# 01: Module systems

## Exercícios Teóricos

<details>
<summary>Lista de exercícios teóricos</summary>

### 01: Explique as diferenças entre CommonJS e ES Modules em relação à forma como os módulos são importados e exportados no Node.js.
**Resposta:**

---

### 02: Qual é a diferença entre require() e import/export em termos de sintaxe e funcionalidade?
**Resposta:**

---

### 03: Por que o Node.js adotou o CommonJS como seu sistema de módulos padrão inicialmente? Quais são suas vantagens e limitações?
**Resposta:**

---

### 04: Qual é o objetivo do objeto module em Node.js? Como ele é usado em sistemas de módulos?
**Resposta:**

---

### 05: Quais são as vantagens de utilizar ES Modules em comparação com CommonJS? Discuta aspectos como suporte a importações assíncronas, carregamento condicional e suporte a tipos.
**Resposta:**

---

### 06: Como o Node.js resolve os caminhos dos módulos ao importá-los usando CommonJS? Explique o processo de resolução de caminhos.
**Resposta:**

---

### 07: Como o Node.js lida com a compatibilidade entre módulos CommonJS e ES Modules? Existem limitações ou problemas que podem surgir ao tentar interoperar entre os dois sistemas?
**Resposta:**

---

### 08: Quais são as diferenças chave entre a forma como os módulos são carregados em ambiente Node.js em comparação com o navegador?
**Resposta:**

---

### 09: Além de CommonJS e ES Modules, existem outros sistemas de módulos disponíveis para o Node.js? Discuta brevemente sobre eles e suas respectivas utilidades.
**Resposta:**
</details>

---

## Exercícios práticos

<details>
<summary>Lista de exercícios práticos</summary>

### 01: Crie um módulo usando o padrão CommonJS que exporte uma função para calcular a área de um círculo com base no raio fornecido. Em seguida, importe e use essa função em outro arquivo.
**Resposta:**

---

### 02: Refatore o exercício anterior para utilizar ES Modules em vez de CommonJS. Certifique-se de que o código continue funcionando corretamente após a alteração.
**Resposta:**

---

### 03: Escreva um módulo em ES Module que exporte uma classe chamada Calculator. Esta classe deve ter métodos para realizar operações matemáticas básicas como adição, subtração, multiplicação e divisão. Importe este módulo em outro arquivo e utilize a classe Calculator para realizar algumas operações.
**Resposta:**

---

### 04: Crie um projeto Node.js com pelo menos dois arquivos de módulo: um usando CommonJS e outro usando ES Modules. Importe uma função de um arquivo para o outro e vice-versa, demonstrando a interoperabilidade entre os dois sistemas de módulos.
**Resposta:**

---

### 05: Experimente importar um módulo ES em um arquivo CommonJS e vice-versa. Observe o que acontece e discuta os resultados. Como você pode lidar com essa situação?
**Resposta:**

---

### 06: Projete uma estratégia de migração de um projeto Node.js que utiliza CommonJS para ES Modules. Considere os desafios e precauções necessários durante o processo de migração.
**Resposta:**

</details>

---

## Projeto integrador
### Descrição:
Este projeto consiste em um simples conversor de temperatura em Node.js, que utiliza tanto CommonJS quanto ES Modules para demonstrar o uso de sistemas de módulos em ambientes Node.js.

### Funcionalidades:

- O usuário pode escolher converter uma temperatura de Celsius para Fahrenheit ou de Fahrenheit para Celsius.
- O programa solicita ao usuário que insira a temperatura a ser convertida.
Após a conversão, o programa exibe o resultado ao usuário.