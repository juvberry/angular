# Angular

## modularização ;)

os modulos sao um limitador de de contexto, enquanto os componentes são o que traz vida aos modulos.

### interpolação

no html, utilizar a propriedade inscrita no app.component

### property binding

one way = só colchetes (nao atualiza o valor da propriedade) -> apenas exibição

two way = colchetes e parenteses (atualiza direto o valor da propriedade) -> exibir e alterar

**ciclo de vida** seriam os onInit, onChange, etc. 

****

sempre precisamos declarar em declarations o componente que criamos. declarar no modulo que ele está


para obter alguma informação de dentro do nosso componente para o html, usa-se o [] em volta.

obter uma variavel de template, do nosso component.

por ex: `[src]=""` ou `[disabled]='courseForm.invalid'`


### injeção de dependência

serviços = metodos simples e variavies que nao serao alterados. ;)


### pipe

alterar exibição ou formatação do texto. 

### routes

path: '' = raiz do nosso path, quando ele chamar a url, vai linkar com a rota e entao redirecionaar para redirectTo

path: '**' = quando nao encontra a rota

**quando estamos trabalhando com rotas, nao precisamos do selector, se o component for chamado dentro de outro component, por exemplo, aí sim usamos o selector**

#### routerLink

primeiro vc passa a rota e depois os parametros que vc quer pegar/utilizar

para passar uma classe diferente para o seu link ativo, utiliza routerLinkActive

### shared

interessante criar um modulo para cada componente que iremos deixar na shared, caso queiramos utilizar um separado do outro.