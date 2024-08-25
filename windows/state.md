# Janela State

## Descrição

Permite o monitoramento e controle do estado do processador.

## Estrutura

### Barra de controle
Localizada na parte superior da janela:

- **Reset:** reinicializa o estado do processador, restaurando todos os registradores e a memória para o estado inicial
- **Run:** inicia a execução do programa
- **Stop:** interrompe a execução do programa
- **Step in:** avança a execução para a próxima instrução (passo a passo)
- **Slider de Frequência:** controla a frequência do processador

### Registradores

A seção de `Registers` exibe os valores atuais dos registradores de uso geral do processador.

### Registradores Internos

A seção de `Internal Registers` mostra os registradores internos do processador:
 
- **IR (Instruction Register):** armazena a intrução para ser executada 
- **SP (Stack Pointer):** armazena o endereço do topo da stack na memória
- **FR (Flag Register):** armazena as flags geradas por operações lógicas e erros
- **PC (Program Counter):** armazena o endereço da próxima instrução a ser executada
- **KB (Keyboard):** mapeia o input do teclado
- **WC (Write Counter):** incrementado a cada operação de saída
