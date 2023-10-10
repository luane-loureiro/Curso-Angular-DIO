# Entendendo a composição de componentes
----
Uma aplicação Angular é baseada em componentes. Com eles, nós podemos encapsular comportamentos e regras da interface, o que torna a criação de aplicações algo mais simples. Inclusive, um componente pode encapsular outros componentes.

Isso é um ponto muito positivo, porque o componente pode ser reaproveitado em vários lugares da aplicação.

Um componente é composto de 3 itens:

- Template HTML
- CSS
- Uma classe que gerencia as propriedades e comportamentos

## :question: O que são componentes:
- um elemento que seja visual, customizável e replicável.
- é um pedacinho da sua aplicação como, como uma peça de Lego, onde vc poode montar varias coisas diferentes com as mesmas peças.


## :syringe: como minha aplicação é montada:
- a composição dos componentes é montada através de injeção de dependencias.
- A injeção de dependencias nada mais é que um padrão de desenvolvimento muito utilizada em diversos cenários.
- unm ingeçao de componente é quando uma coisa  depende de outra coisa para funcionar, não produz esse conteudo diretamente, tende a depender de algo externo para funcionar.

Injeção de dependências é um padrão de projeto que pode ser aplicado independentemente da linguagem.

Esse padrão permite deixar as classes de componentes mais limpas e eficientes, delegando tarefas complexas e regras de negócios para os serviços.

Indo mais a fundo, injeção de dependências é o processo de prover as instâncias necessárias que uma determinada classe precisa para ser instanciada e utilizada.

A grande vantagem é que temos um menor acoplamento entre nossas classes.

O Angular implementa um mecanismo de injeção de dependências e executa ele na inicialização da aplicação.

# Usando o Stack Blitz
----
## 🔗 links:
[Satck Blitz](https://stackblitz.com/)

[docs stack Blitz](https://developer.stackblitz.com)

## ❓ O que é Stack Blitz?
- StackBlitz, um ambiente de desenvolvimento online para frontend, Node.js e ecossistema JavaScript.

# ⬅️📂Arquivos SRC-out (fora da pasta SRC)
----
- ficam todos os arquivos de configuração do angular, node e typeScript.
  
# ➡️📁 Arquivos SRC-in (dentro da pasta SRC)
----
- Pasta onde fica todo o código fonte editado e criado pelo desenvolvedor.

### Index.html
- aponta para o componete raiz, um app.
- recebe a injeção de um app root.

### main.ts
- arquivo que inicia os modulos, responsavel por iniciar o seu projeto.

### Pollyfiles.ts
- arquivo que aumenta a compatibilidade com os navegadores.
- na maior parte o tempo não precisa ser alterado, mas pode ser configurado para que algumn comando mais moderno possa ser adaptado pra navegadores antigos.

### stilist.css
- Arquivo que configura os estilos, cores, fontes, alinhamentos...

.
## 📂 Pasta APP
### app.component.html
- html do component
  
### app.component.css
- folha de estilos.
  
### app.componet.ts 
- funcionabilidade do componete

# Comparando com Estruturas de arquivos React e Vue
----
- Diferentes feameworks utilizam estruturas muito Parecidas entre sí.
- O que muda é levemente a organização dos arquivos e as esteções.


