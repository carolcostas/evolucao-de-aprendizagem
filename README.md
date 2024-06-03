![](https://i.imgur.com/xG74tOh.png)



## Conteúdos a serem trabalhados nesse módulo:

- LinkedIn
- Gestão de tempo
- Métodos de strings
- Métodos de arrays
- Funções
- Tipos de Dados II
- Gestão de Tempo
- Tipos Utilitários
- Currículo e Apresentação

## O que eu já sei sobre os assuntos que serão abordados nesse módulo?

- Soft skills são habilidades importantes no ambiente de trabalho, como comunicação e trabalho em equipe. Muitas pessoas obtêm oportunidades de trabalho graças às suas soft skills bem desenvolvidas, mesmo que não possuam todas as hard skills necessárias, pois é mais fácil ensinar um funcionário a programar do que aprender a se comunicar bem ou controlar o temperamento.
- LinkedIn é uma plataforma onde as pessoas podem criar perfis profissionais e se conectar com outras na área. É uma grande oportunidade para fazer networking, aprender o que outros profissionais têm a ensinar, aprender sobre ética e ficar por dentro de novos eventos e oportunidades.
- Gestão de tempo envolve organizar suas tarefas de forma eficaz para fazer o melhor uso do tempo.
- Métodos de strings são maneiras de manipular texto em programação.

## O que quero aprender sobre os assuntos que serão abordados nesse módulo?

- Quero aprender dicas práticas de entrevista de emprego (como o candidato é avaliado, como se comportar, quais perguntas mais caem, como se destacar em uma entrevista).
- Adentrando o mundo da ética, quero aprender o que preciso saber sobre a LGPD para exercer a profissão.
- Quero entender o Git mais a fundo, como fazer junções de branches e como voltar na linha do tempo.
- Gostaria de obter conhecimentos mais aprofundados sobre TypeScript e por que é tão importante assim.
- Quero saber o que são métodos de arrays e strings.

## Minha evolução: o que aprendi sobre os assuntos que foram abordados nesse módulo?

- Aprendi algumas estratégias simples de gerenciamento de tempo, como fazer listas de tarefas e definir prioridades.
- Aprendi alguns métodos básicos de strings, como concatenar e dividir texto.
- Aprendi alguns métodos básicos de arrays, como adicionar e remover itens de uma lista.
- Aprendi que os currículos devem ser feitos da forma mais simples possível em arquivos TXT para serem acessíveis aos robôs de busca. Deve-se priorizar as informações em vez da estética.

### Funções

- Funções são blocos de código reutilizáveis que devemos utilizar para não ter que ficar reescrevendo o mesmo código.
- Os parâmetros são variáveis que podem ser utilizadas dentro da função.
- Podemos utilizar desestruturação de objetos ou shorthand para facilitar a escrita do código dentro das funções.

### Tipos de Dados II

- `type` é uma palavra reservada do TypeScript para informar o tipo de uma variável, podendo ser string, number, boolean, array ou objeto.
- Os tipos literais são tipos de dados que já carregam um valor, e uma vez que esse valor é definido, deve ser declarado exatamente da mesma maneira.
- Permite que uma variável tenha mais de um tipo. Utiliza o símbolo | para definir que pode ser um tipo ou outro.
- Mescla mais de um tipo, geralmente usado com objetos. Utiliza o símbolo &.
- Tuplas permitem definir um tamanho para um array e qual será o tipo de cada elemento que compõe esse array.
- Tipos de conjunto permitem mesclar mais de dois tipos, mas só podem ser utilizados com objetos; nunca uma variável poderá armazenar mais de um tipo de valor.
- `Type Narrowing` é uma técnica utilizada para tornar um tipo utilizado o mais assertivo possível (validações). O objetivo do TypeScript é evitar erros ao desenvolver códigos.
- `Type Assertion` força o TypeScript a identificar uma propriedade como um determinado tipo de dado. Mas se fizer isso sem certeza, pode ocasionar erros.
- `Unknown` é usado ao utilizar uma API, indicando um tipo desconhecido. O unknown precisa de uma verificação do tipo antes de realizar operações com ele. Precisamos esperar algum tipo de informação ao utilizar uma API e queremos que essas informações estejam de acordo com o que esperamos.


#### Exemplos de Tipos Utilitários:

- `Partial`: transforma todas as propriedades de um tipo em parciais, tornando-as opcionais.
- `Required`: transforma todas as propriedades de um tipo em obrigatórias.
- `Readonly`: transforma o código manipulado, possibilitando apenas a leitura e não permitindo a alteração de uma propriedade já cadastrada (só é possível acessar a informação).
- `Pick`: cria novos tipos personalizados, utilizando apenas as propriedades necessárias. Exemplo: `type novoTipo = Pick<tipoManipulado, 'propriedade1' | 'propriedade2'>`.
- `Omit`: ao contrário do Pick, o Omit cria um novo modelo e remove as propriedades que não serão utilizadas. A sintaxe é a mesma.
- `Record`: cria um tipo de um objeto onde as propriedades têm o mesmo tipo.
- `Exclude`: exclui um ou mais tipos específicos de uma união de tipos, gerando um novo tipo contendo apenas os tipos restantes.
- `Extract`: extrai um ou mais tipos específicos de uma união de tipos, criando um novo tipo contendo apenas os tipos extraídos.

O `Exclude` é mais voltado para a manipulação de tipos em uma união de tipos, enquanto o `Omit` é mais útil para a manipulação de propriedades em objetos.
