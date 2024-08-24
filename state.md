## Janela de State

A interface permite um monitoramento detalhado do estado do processador durante a execução de programas, facilitando a depuração e a identificação de problemas. Com a capacidade de observar e controlar diretamente os registradores, os desenvolvedores podem depurar seus programas de maneira mais eficaz.

Na parte superior da janela, você encontrará a barra de controle com as seguintes opções:

- **Build:** Compila o arquivo selecionado (ex: `example.asm`) em código de máquina
- **Reset:** Reinicializa o estado do processador, restaurando todos os registradores e variáveis ao estado inicial.
- **Run:** Inicia a execução do programa.
- **Stop:** Interrompe a execução do programa em qualquer ponto.
- **Step in:** Executa o código passo a passo
- **Slider de Frequência:** Controla a velocidade de execução, simulando as frequências do processador (ex: 1 MHz).


## Registradores

A seção de `Registers` exibe os valores atuais dos registradores do processador (inicialmente, todos definidos como `0000`):

- **R0 a R7:** São os registradores de uso geral, utilizados para armazenar dados durante a execução.


## Registradores Internos

Na seção de `Internal Registers`, são mostrados os registradores que o processador usa para gerenciar a execução do programa (inicialmente, todos definidos como `0000`):
 
- **IR (Instruction Register):** Armazena a instrução atual que está sendo executada
- **SP (Stack Pointer):** Armazena o endereço do topo da stack na memória para armazenar as variáveis locais.
- **FR (Flag Register):** Armazena as flags de condição como carry e overflow
- **PC (Program Counter):** Contém o endereço da instrução a ser executada.
- **KB (Keyboard Buffer):** Buffer usado para armazenar dados de entrada do teclado.
- **WC (Word Count):** Conta o número de palavras envolvidas em uma operação.

