# Pensamento de Software:
>  Um Sistema de Agendamento, Gerenciamento e Monitoramento de Software.

## Descrição
O nosso Projeto automatiza o funcionamento de atualizações, monitoramento de memória RAM e o bloqueio de uso de Aplicações com um Menu Interativo.

1. **Agendamentos de Atualizações**: configura a data e horário via "crontab" agendando a atualização dos 10 Softwares mais utilizados pelo usuário, na data determinada..

2. **Atualização de Aplicações:** Através do comando "sa", identifica quais os programas mais utilizados pelo usuário, executando um "apt install" neles.

3. **Bloqueio de Uso por Tempo Determinado:** permite bloquear o uso de um programa específico em um horário definido pelo usuário, encerrando o processo automaticamente caso ele seja executado no período em que foi bloqueado.

4. **Monitoramento de Memória RAM:** monitora o uso de memória Ram do Sistema como um todo e de cada aplicação, caso a memória exceda o limite de 80% de uso total ou 20% do uso individual gera alertas no terminal, log e utilizando o notify-send.

## Objetivo


## Instruções de Uso

### Como inicializar pela primeira vez:

1. Baixe o projeto-linux.zip
2. Extraia o projeto-linux.zip
3. No terminal de comando
    1. entre na pasta projeto-linux
    2. No terminal, escreva o comando:
    3. chmod +x main.sh
    4. e inicialize com:
        1. sudo ./main.sh


## Exemplos de Uso
