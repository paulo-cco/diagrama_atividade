# Diagrama de Atividades na UML

Material introdutório sobre o **Diagrama de Atividades da UML**, com foco na modelagem de fluxos de controle, concorrência e processos de negócio em sistemas orientados a objetos.

## Sobre o conteúdo

O material apresenta o Diagrama de Atividades como um diagrama comportamental da UML. Ele descreve a sequência de passos de um processo, incluindo decisões, caminhos alternativos e atividades que podem ocorrer em paralelo.

## Tópicos abordados

- **Onde o diagrama se encaixa na UML:** classificação como diagrama comportamental, foco na lógica do fluxo e aplicação na modelagem de processos de negócio.
- **Definição e propósito:** representação visual de processos passo a passo, casos de uso detalhados e fluxos algorítmicos.
- **Simbologia oficial de fluxo:**
  - **Início e fim:** indicam os pontos inicial e final do fluxo.
  - **Ação/atividade:** representa uma tarefa executada no processo.
  - **Decisão e fusão:** representam bifurcações condicionais e a união de caminhos alternativos.
  - **Fluxo de controle:** indica a sequência lógica entre as atividades.
- **Concorrência e paralelismo:** uso de barras de divisão (*fork*) e sincronização (*join*) para representar atividades paralelas.
- **Raias de responsabilidade (*swimlanes*):** organização das atividades por ator, equipe ou departamento.
- **Estudo de caso — pedido de e-commerce:** exemplo com as etapas de checkout, validação do pagamento, separação dos itens e despacho do pedido.
- **Comparação entre diagramas UML:** diferenças de finalidade entre Diagrama de Caso de Uso, Diagrama de Sequência e Diagrama de Atividades.
- **Boas práticas:** definir um único ponto de entrada, usar guardas exclusivas em decisões e decompor processos complexos em subatividades.

## Objetivo

Compreender como representar graficamente o comportamento de um processo, identificar a ordem das atividades, visualizar decisões e caminhos alternativos e demonstrar tarefas executadas simultaneamente ou por diferentes responsáveis.

## Quando utilizar

Utilize o Diagrama de Atividades quando for necessário detalhar **como um processo é executado**, desde seu início até sua conclusão, especialmente quando houver condições, ramificações, paralelismo ou divisão de responsabilidades.

## Autoria

Apresentação elaborada por **Paulo, Davi e Isaac** — Ciências da Computação.
