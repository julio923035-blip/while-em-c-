#  Repetidor de Números em C

##  Sobre o projeto

Este projeto foi desenvolvido em **linguagem C** com o objetivo de praticar o uso do laço de repetição `while`.

O programa solicita ao usuário um número e a quantidade de vezes que ele deseja repetir esse número. Em seguida, utiliza um contador dentro do `while` para realizar as repetições.

##  Objetivo

Praticar os seguintes conceitos da linguagem C:

- Declaração de variáveis;
- Entrada de dados com `scanf`;
- Saída de dados com `printf`;
- Laço de repetição `while`;
- Uso de contador;
- Operadores relacionais e incremento.
  
##  Testes realizados

Foram considerados os três cenários de teste propostos no desafio:

### Teste 1: Validação de entradas inválidas

O programa deve verificar se os valores informados pelo usuário são válidos antes de realizar os cálculos.

**Resultado esperado:**  
Entradas inválidas devem ser identificadas pelo programa e o usuário deve ser orientado a informar um valor válido.

> **Observação:** Esta validação ainda não está implementada na versão atual do código.

---

### Teste 2: Temperaturas acima do limite, porém não consecutivas

Neste teste, foram consideradas temperaturas acima do limite, mas intercaladas com temperaturas dentro do limite.

**Resultado esperado:**  
O programa deve identificar as temperaturas acima do limite, mas não deve encerrar automaticamente, pois elas não ocorreram por três vezes consecutivas.

> **Observação:** Esta funcionalidade ainda não está implementada na versão atual do código.

---

### Teste 3: Três temperaturas consecutivas acima do limite

Neste cenário, são informadas três temperaturas consecutivas acima do limite estabelecido.

**Resultado esperado:**  
Ao identificar três temperaturas consecutivas acima do limite, o programa deve encerrar automaticamente e informar o usuário.

> **Observação:** Esta funcionalidade ainda não está implementada na versão atual do código.

---

### 📋 Resultado dos testes

A versão atual do programa tem como objetivo praticar o uso do laço `while` através da repetição de um número informado pelo usuário.

Para atender completamente aos testes exigidos pelo desafio, será necessário adicionar ao programa:

- Entrada e validação das temperaturas;
- Definição de um limite de temperatura;
- Identificação de temperaturas acima do limite;
- Controle de temperaturas consecutivas;
- Encerramento automático após três temperaturas consecutivas acima do limite.
