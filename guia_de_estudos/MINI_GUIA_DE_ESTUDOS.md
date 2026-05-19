# Miniguia de Estudos: Python do Zero ao POO & APIs

Este guia é o resultado consolidado de um processo de curadoria ativa utilizando o NotebookLM. Ele foi desenhado para servir como uma consulta rápida e estruturada.

O aprendizado de Python deve seguir uma progressão lógica: da sintaxe básica à estruturação de sistemas complexos. A Programação Orientada a Objetos (POO) e APIs são o topo dessa pirâmide, exigindo a base de lógica e funções consolidada.

###### 1. Iniciante:
- Foco principal: Base e Lógica	Variáveis
- Tópicos Chaves: Tipos Primitivos, Operadores e Controle de Fluxo (if/else).

###### 2. Fundamental:
- Foco Principal: Estruturas e Loops
- Tópicos Chaves: Listas, Tuplas, Dicionários e Laços de Repetição (for/while).

###### 3. Intermediário:
- Foco Principal: Modularização
- Tópicos Chaves: Funções (def), Módulos, Pacotes e Tratamento de Erros (try/except).

###### 4. Avançado:
- Foco Principal: Paradigmas e APIs
- Tópicos Chaves: POO (Classes/Pilares), List Comprehension e Integração com APIs.

### Resumo dos principais conceitos:

**1. Fundamentos e Armazenamento**

Variáveis e Tipos: Espaços na memória para int, float, str e bool.

- Listas []: Mutáveis e ordenadas.

- Tuplas (): Imutáveis (segurança de dados).

- Dicionários {}: Pares de chave-valor.

**2. Controle de Fluxo e Repetição**

- Condicionais: Tomada de decisão lógica.
- Loops: O for é utilizado para iterações definidas (sequências), enquanto o while foca em repetições baseadas em condições lógicas.

**3. Modularização e Organização**

- Funções (def): Blocos reutilizáveis que isolam lógicas, recebem argumentos e retornam valores.
- Módulos/Pacotes: Divisão do programa em múltiplos arquivos para facilitar a manutenção.

**4. Programação Orientada a Objetos (POO)**

Paradigma que organiza o código em torno de Objetos (instâncias) criados a partir de Classes (moldes).

- Abstração: Foco no essencial, escondendo a complexidade.
- Encapsulamento: Proteção de dados e métodos (uso do _ ou __).
- Herança: Classes filhas herdam características das classes mães.
- Polimorfismo: Diferentes classes respondendo ao mesmo método de formas distintas.
- O self: A peça-chave que referencia a instância específica que está sendo manipulada.

**5. Tratamento de Erros**

- Exceções: Uso de try/except para capturar falhas e finally para ações de limpeza, garantindo que o programa não interrompa o fluxo abruptamente.

# Glossário

**Classe**: É o molde, projeto ou receita que define as características e comportamentos que todos os objetos criados a partir dela terão

**Objeto (ou Instância)**: É a realização concreta de uma classe na memória do computador; o "bolo" feito a partir da "forma"

**Atributo**: Representa as características ou dados que um objeto armazena, funcionando como variáveis internas da classe

**Método**: São as ações ou comportamentos que um objeto pode realizar, sendo implementados como funções dentro da classe

**Self**: Parâmetro obrigatório em métodos de instância que serve como uma referência ao próprio objeto que está sendo manipulado no momento.

**Herança**: Pilar da POO que permite que uma subclasse aproveite atributos e comportamentos de uma superclasse, facilitando o reuso de código

**Encapsulamento**: Prática de agrupar dados e proteger o acesso direto aos detalhes internos de uma classe para manter a integridade do sistema

**Polimorfismo**: Capacidade de objetos de diferentes classes responderem à mesma chamada de método de formas distintas

**Abstração**: Processo de ignorar detalhes irrelevantes e focar estritamente no que é essencial para o funcionamento do sistema

**Lista**: Estrutura de dados composta e mutável, onde os itens são organizados sequencialmente e acessados por índices numéricos

**Tupla**: Sequência de dados imutável, o que significa que seu conteúdo e tamanho não podem ser alterados após a criação

**Dicionário**: Estrutura que armazena dados em pares de chave e valor, permitindo o acesso por etiquetas literais em vez de posições numéricas

**Função**: Bloco de código reutilizável definido pela palavra-chave def para executar uma tarefa específica sempre que for chamado

**Exceção**: Representa um erro ou evento inesperado que ocorre durante a execução do programa e interrompe seu fluxo normal

**Modularização**: Técnica de dividir um programa grande em pequenos pedaços ou módulos independentes para facilitar a leitura e manutenção

# Prompts Reutilizáveis:

**1. O Explicador Didático (Foco em Analogias)**: 

"Com base nas fontes fornecidas, explique a principal diferença entre [Conceito A] e [Conceito B] em Python. Crie uma analogia do cotidiano para facilitar o entendimento de um iniciante."

**2. O Mapeador de Estrutura (Comparativo de Dados)**:

"De acordo com os documentos, qual a diferença prática entre [Estrutura 1] e [Estrutura 2]? Traga a explicação técnica, a regra de mutabilidade e um exemplo de quando escolher uma em detrimento da outra."

**3. O Debugger Pedagógico (Previsão de Erros)**:

"Liste 3 erros comuns que iniciantes cometem ao tentar implementar [Tópico] e, segundo as fontes, qual a melhor forma de resolvê-los? Apresente um bloco de 'Código com Erro' e um de 'Código Corrigido'."

**4. O Arquiteto de Transição (Mudança de Paradigma)**:

"Como posso transformar um código baseado em [Programação Estruturada] em um sistema baseado em [POO] seguindo as boas práticas das fontes? Forneça um passo a passo metodológico."

**5. O Gerador de Roadmap Lógico (Sequenciamento)**:

"Quais os tópicos de [Assunto] presentes no material são considerados base (iniciante) e quais são avançados? Sugira a ordem lógica de estudo para que um conceito sirva de base para o próximo."
