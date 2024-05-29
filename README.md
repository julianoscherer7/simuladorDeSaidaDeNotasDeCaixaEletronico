
# Simulador de Saída de Notas de Caixa Eletrônico
## Informações Básicas: 
#### Título: 
Simulador de Saída de Notas de Caixa Eletrônico
### Autor: 
Juliano Martins Scherer
### Data: 
28/05
### Versão: 
1.0
### Descrição: 
Este programa em C++ simula a saída de notas de um caixa eletrônico, permitindo o cadastro dos valores das notas e a simulação de saques, calculando a quantidade de notas necessárias para um valor especificado pelo usuário. A execução pode ser interrompida com o código 9999.

## Funcionalidades: 
### Cadastro de Notas:
O usuário registra os valores das notas que serão usadas.
### Simulação de Saque: 
O usuário insere um valor a ser sacado e o programa calcula a quantidade de cada nota necessária.
### Interrupção do Sistema: 
Inserir o valor 9999 interrompe o programa.
##Estrutura do Código: 
Função contaNotas: Calcula a quantidade de cada nota para o valor de saque.

### Parâmetros: 
qtdNotas, valNotas, saque.
### Função cadastraNotas: 
Permite ao usuário registrar os valores das notas.

### Parâmetros: 
valNotas.
### Função simulaSaida: 
Exibe a quantidade de cada nota calculada.

### Parâmetros: 
qtdNotas, valNotas.
###Função main: 
Controla o fluxo do programa, chama as funções, e gerencia a memória.

## Exemplo de Uso: 
- O usuário cadastra os valores das notas.
- O usuário insere o valor a ser sacado.
- O programa exibe a quantidade de cada nota necessária.
- O usuário pode continuar inserindo valores ou interromper o sistema com o código 9999.
## Licença: 
Este projeto é licenciado sob a licença MIT
