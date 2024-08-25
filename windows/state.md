# Janela State

## Descrição

A janela permite um monitoramento detalhado do estado do processador durante a execução de programas, facilitando a depuração e a identificação de problemas. Com a capacidade de observar e controlar diretamente os registradores, os desenvolvedores podem depurar seus programas de maneira mais eficaz.

## Estrutura

### Barra de controle
Na parte superior da janela, você encontrará a barra de controle com as seguintes opções:

- **Reset:** reinicializa o estado do processador, restaurando todos os registradores e a memória para o estado inicial
- **Run:** inicia a execução do programa
- **Stop:** interrompe a execução do programa
- **Step in:** avança a execução para a próxima instrução (passo a passo)
- **Slider de Frequência:** controla a frequência do processador

### Registradores

A seção de `Registers` exibe os valores atuais dos registradores de uso geral do processador.

### Registradores Internos

Na seção de `Internal Registers`, são mostrados os registradores internos do processador:
 
- **IR (Instruction Register):** armazena a intrução para ser executada 
- **SP (Stack Pointer):** armazena o endereço do topo da stack na memória
- **FR (Flag Register):** armazena as flags geradas por operações lógicas e erros
- **PC (Program Counter):** contém o endereço da próxima instrução a ser executada
- **KB (Keyboard):** mapeia o input do teclado
- **WC (Write Counter):** incrementado a cada operação de saída
