# Computador Simulado

Este repositório contém o projeto de um **computador simulado** implementado e simulado com o **LogisimEvolution**. Este projeto foi desafiador, pois engloba a simulação completa de uma arquitetura computacional, demonstrando a organização e o funcionamento de um sistema computacional desde o nível de componentes lógicos básicos até a integração completa dos módulos.

## Introdução

O objetivo do projeto é construir e simular a arquitetura de um computador completo. Essa simulação abrange diversos módulos, tais como:
- **Unidade Lógica e Aritmética (ULA):** Responsável por executar operações matemáticas e lógicas.
- **Unidade de Controle:** Coordena as operações de processamento e gerenciamento dos sinais do sistema.
- **Registradores e Banco de Registradores:** Armazenam dados temporários e instruções.
- **Barramento de Dados e Endereços:** Permite a comunicação entre os diferentes módulos do computador.
- **Memória RAM:** Responsável pelo armazenamento de instruções e dados.

Através da simulação, é possível visualizar como um computador processa informações, executa instruções e realiza operações de forma integrada.

## Objetivos do Projeto

- **Simular uma arquitetura completa:** Implementar uma estrutura que reproduza os principais componentes de um computador.
- **Integrar componentes lógicos:** Conectar módulos como a ULA, registradores, unidade de controle e memória para o funcionamento coeso do sistema.
- **Validar a organização e sincronização:** Analisar como os sinais e dados fluem entre os componentes, garantindo o funcionamento correto do circuito simulado.
- **Aprender e aplicar conceitos avançados de lógica digital:** Enfrentar desafios de projeto e sincronização presentes em arquiteturas computacionais.

## Ferramentas Utilizadas

- **LogisimEvolution:** Ferramenta utilizada para o design, simulação e validação dos circuitos digitais.
- **Lógica Digital:** Conhecimentos teóricos e práticos sobre portas lógicas, flip-flops, barramentos, entre outros.

## Como Executar o Projeto

Para visualizar e simular o computador:

1. **Baixe o arquivo `computador_simulado.circ`:**  
   Faça o download do arquivo contido neste repositório. Além disso, há um arquivo contendo o código hexadecimal desenvolvido por mim da sequência de Fibonacci que levou em consideração 
   a arquitetura do projeto. A simulação pode ser testada carregando o código para a memória RAM.

2. **Instale o LogisimEvolution:**  
   Se ainda não o possui, baixe a versão mais recente do [LogisimEvolution](https://github.com/reds-heig/logisim-evolution) e instale em seu sistema.

3. **Abra o Projeto no LogisimEvolution:**  
   Abra o LogisimEvolution, selecione `File > Open` e escolha o arquivo `computador_simulado.circ`.

4. **Explore a Simulação:**  
   Utilize as ferramentas e recursos do LogisimEvolution para testar o circuito, acompanhar o fluxo de dados e analisar a integração dos componentes.

5. **Vídeo do Projeto:**
   A simulação do projeto foi gravado por mim em meu canal do [YouTube](https://www.youtube.com/watch?v=z_KEP6LsSwA).

## Desafios e Considerações

- **Integração Complexa:**  
  A integração de diversos módulos (ULA, registradores, memória e unidade de controle) exigiu um planejamento meticuloso, principalmente no que tange à sincronização dos sinais e à organização do barramento de dados.

- **Resolução de Problemas:**  
  O projeto enfrentou desafios relacionados ao timing e disposição dos componentes, demandando iterações constantes para ajustar e validar cada parte do sistema.

- **Aprendizado Avançado:**  
  Este projeto não só testou os conhecimentos práticos de lógica digital, mas também aprofundou a compreensão sobre a arquitetura dos computadores modernos.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
