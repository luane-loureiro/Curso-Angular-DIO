# Entendendo o Scoped
----
A componentização é algo que permite a reutilização de trechos de código, isolamento de contexto, diminuição de tags das páginas, melhor leitura do código e padronização do projeto. Frameworks como, React e Vue utilizam esse método na construção de aplicações. 

Segundo a documentação do Angular, o componente é o principal bloco de construção para aplicativos, e é composto por um template, um estilo e uma classe. É no template que encontraremos toda a estrutura HTML, a árvore DOM do componente. Já o estilo é onde será feita a estilização, e a classe onde é definido o comportamento e a lógica feita em Typescript.

Para configurar um componente, no arquivo TS é passado o decorador @Component. Esse decorador é um método que recebe um objeto com os metadados como parâmetro. É criado um seletor, que será usado como tag HTML em outro template, o template passando o caminho do arquivo HTML, mas pode ser passado inline, e o arquivo de folha de estilo ou, assim como o template, passado inline.

Também temos a classe onde adicionamos propriedades e comportamentos ao componente.

## Pasta APP

dentro da pasta app encontramos as partes principais do nosso componente:

- app.componet.html -> template
- app.componet.css -> estilo
- app.componet.ts -> classe


