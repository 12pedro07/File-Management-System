# File-Management-System

# Trabalho de CC6270 - Sistemas Operacionais

Sumário:
========

- [Grupo](#grupo)
- [Desenvolvimento](#desenvolvimento)
- [Entrega 1](#entrega-1)
- [Entrega 1](#entrega-1)

# Grupo

|  Nome  |  R.A.  |
|  :---: |  :---: |
| Ibrahim Jamil Orra | 22.118.183-7 |
| Matheus Elias Cruz | 22.118.167-0 | 
| Pedro Henrique Silva Domingues  |  22.218.019-2  |
| Renan Martins | 22.118.025-0 |

# Desenvolvimento

- [x] Entrega 1
- [x] Entrega 2
- [ ] Entrega 3
- [ ] Entrega 4
- [ ] Entrega 5

# Entrega 1


# Entrega 2

* _Processo_:

Um processo pode ser qualquer programa em execução. Uma entidade ativa que carrega atributos como memoria, estado do hardware e um id chamado de PID.
Processos possuem estados, os quais são:

__NEW__ - Está em estado de criação;

__READY__ - Está aguardando para ser direcionado a uma unidade de processamento;

__RUNNING__ - Suas instruções estão sendo executadas;

__WAITING__ - Em aguardo por um evento, como por exemplo uma entrada/saída de dados;

__TERMINATED__ - Sua execução foi finalizada;

* _Thread_:

threads são fluxos que ocorrem em paralelo dentro de um mesmo processo, cada uma possuindo seu próprio pc (Program Counter) para gerenciar quais instruções devem ser executadas a seguir. Assim como memoria para armazenamento de variáveis e uma pilha de execução para o histórico de execução.

* _Escalonamento de processo_:

Escalonamento de processos é a um susbsistema do sistema operacional, o qual decida qual processo poderá fazer o uso da cpu em um dado momento. Os algoritmos aplicados a este são responsáveis por todo o gerenciamento desta logistica.

----

Alguns exemplos de algoritmos de gerenciamento de processos são: Algoritmo do barbeiro e Jantar dos filósofos.

- algoritmo do barbeiro
	- Imagine uma barbearia (memória ram)
	- A barbearia recebe clientes (processos)
	- Se não há clientes, o barbeiro adormece 
	- Se a cadeira do barbeiro estiver livre o cliente vai ser atendido
	- O cliente espera pelo barbeiro se houver uma de espera vazia
	- Se não tive onde sentar, o cliente vai embora.

- algoritmo jantar dos filosofos
	- Uma mesa com cinco filósofos
	- Cada filosófo precisa de dois hashis para comer
	- Eles vão precisar compartilhar os hashis
	- Vão precisar considerar os hashis livres para poderem usar


No nosso projeto aplicaremos estes conhecimentos da seguinte forma:
1. Todo código que estiver rodando será um processo, independente de sua funcionalidade.
2. Threads serão utilizadas para gerenciar tarefas em plano de fundo enquanto o usuário permanece podendo utilizar a interface.
3. Não faremos uso direto de Escalonamento de processo, uma vez que o sistema operacional cumprirá todas as necessidades sob este aspecto.
