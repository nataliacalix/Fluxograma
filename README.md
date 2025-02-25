# Fluxogramas - Pesquisa

## Introdução
Fluxogramas são representações visuais de processos, utilizando símbolos e setas para descrever a sequência de etapas. Eles são ferramentas poderosas para organizar ideias, explicar processos, identificar problemas e comunicar informações de forma clara e concisa.

---

## Perguntas da Pesquisa

### O que é um fluxograma?
Um fluxograma é um diagrama que descreve um processo, sistema ou algoritmo de computador. Ele usa símbolos para representar diferentes tipos de ações e setas para mostrar a ordem em que essas ações ocorrem.

### Quais os principais símbolos utilizados e seus significados?

- **Início/Fim (oval):** Indica o começo e o fim do processo.
- **Processo (retângulo):** Representa uma ação ou tarefa.
- **Decisão (losango):** Indica um ponto de decisão, com duas ou mais opções de caminho.
- **Entrada/Saída de dados (paralelogramo):** Mostra a entrada ou saída de informações.
- **Conector (círculo):** Liga partes do fluxograma em páginas diferentes ou em áreas distantes.
- **Seta:** Indica a direção do fluxo do processo.

### Como os fluxogramas são utilizados no desenvolvimento de sistemas?
No desenvolvimento de sistemas, os fluxogramas são utilizados para:

- **Planejar a lógica do programa:** Antes de escrever o código, o fluxograma ajuda a visualizar a sequência de passos que o programa deve seguir.
- **Documentar o sistema:** O fluxograma serve como um guia visual para entender o funcionamento do sistema, facilitando a manutenção e futuras alterações.
- **Comunicar a lógica do sistema:** O fluxograma ajuda a explicar a lógica do sistema para outras pessoas, como outros desenvolvedores ou usuários finais.

---

## Exemplos de Fluxogramas Aplicados à Lógica de Programação

### Verificar se um número é par ou ímpar:
```mermaid
graph TD;
    A[Início] --> B{Número é par?};
    B -- Sim --> C[Exibir "Par"];
    B -- Não --> D[Exibir "Ímpar"];
    C --> E[Fim];
    D --> E;
```

### Calcular a média de dois números:
```mermaid
graph TD;
    A[Início] --> B[Ler número 1];
    B --> C[Ler número 2];
    C --> D[Calcular média = (número 1 + número 2) / 2];
    D --> E[Exibir média];
    E --> F[Fim];
```

---

## Ferramentas Utilizadas

- **Lucidchart:** Ferramenta online para criação de diagramas, incluindo fluxogramas.
- **Draw.io:** Ferramenta online gratuita para criação de diversos tipos de diagramas.
- **Markdown:** Linguagem de marcação leve utilizada para criar o arquivo README.md e os fluxogramas em formato de texto.
- **Git e GitHub:** Sistema de controle de versão e plataforma de hospedagem de código-fonte utilizados para criar e gerenciar o repositório.

---

## Conclusão
Os fluxogramas são ferramentas essenciais no processo de desenvolvimento de sistemas, pois permitem:

- Visualizar a lógica do programa de forma clara e organizada.
- Identificar erros e inconsistências na lógica antes da codificação.
- Facilitar a comunicação entre os membros da equipe de desenvolvimento.
- Documentar o sistema para futuras manutenções e atualizações.

Ao utilizar fluxogramas, os desenvolvedores podem criar sistemas mais eficientes, robustos e fáceis de manter.

