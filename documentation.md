## **Janela Documentation**

### Na parte superior da janela, você verá três colunas:

- **Mnemonic**: Representa o código em assembly da instrução ("representa a instrução em palavras").
- **Opcode**: Representa o código da instrução em binário (conteúdo da memória quando a instrução é chamada).
- **Pseudo-code**: Representa o que a instrução "faz".

### A tabela é dividida em blocos. O quê cada um significa?

- **Memory**: Agrupa todas as instruções que armazenam (*store*) ou retiram (*load*) conteúdo da memória.

- **Move**: Possui a instrução que move o conteúdo de um registrador para outro.

- **Arithmetic**: Agrupa todas as instruções que realizam operações aritméticas com o conteúdo dos registradores.

- **Logic**: Agrupa todas as instruções que realizam operações lógicas com o conteúdo dos registradores.

- **IO**: Possui a instrução *Inchar*, que lê um caractere, e a *Outchar*, que escreve um caractere na saída.

- **Jump**: Agrupa as instruções que desviam o fluxo de execução do programa para outra parte do código.

- **Call**: Agrupa todas as funções que são usadas para chamar sub-rotinas (funções).

- **Stack**: Possui a instrução *push*, que insere um dado na pilha (*stack*), e a *pop*, que retira um dado da pilha e o armazena.

- **Control**: Agrupa as instruções que limpam ou ajustam valores em registradores, flags ou posições de memória.