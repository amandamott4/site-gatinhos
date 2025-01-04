RESUMO DO CURSO (html) - FreeCodeCamp 

---
 HyperText Markup Language(HyperText Markup Language)
---

## Elementos HTML

Os elementos HTML possuem tags de abertura, como `<h1>`, e tags de fechamento, como `</h1>`. O texto que um elemento exibirá vai entre suas tags de abertura e fechamento. 

Altere o texto do elemento h1 abaixo de "Hello World" para "CatPhotoApp" e observe a mudança na visualização do navegador.

### Elementos de Título

Os elementos de título, que vão de h1 a h6, são usados para dar significado à importância do conteúdo abaixo deles. Quanto menor o número, maior a importância. Assim, os elementos h2 têm menos importância que os elementos h1. 

Utilize apenas um elemento h1 por página e coloque títulos de menor importância abaixo de títulos de maior importância.

### Elemento `p`

O elemento `p` é usado para criar um parágrafo de texto nos sites.

### Comentários

Colocar comentários permite que você deixe mensagens sem afetar a exibição do navegador. Também permite que você deixe o código inativo. Um comentário em HTML começa com `<!--`, contém uma ou várias linhas de texto e termina em `-->`.

### Elementos HTML5

O HTML5 tem alguns elementos que identificam diferentes áreas de conteúdo. Esses elementos tornam seu HTML mais fácil de ler e ajudam com a otimização dos mecanismos de busca (SEO) e com a acessibilidade.

O elemento `main` é usado para representar o conteúdo principal do corpo de um documento HTML. O conteúdo do elemento `main` deve ser único e não ser repetido em outras partes do documento.

### Aninhamento e Identação

No passo anterior, você colocou os elementos `h1`, `h2`, comentário e `p` dentro do elemento `main`. Isso é chamado de aninhamento. Elementos aninhados devem ser colocados duas posições à direita do elemento no qual estão aninhados. Esse espaçamento é chamado de identação e é usado para tornar o HTML mais fácil de ler.

### Imagens

Você pode adicionar imagens ao seu site usando o elemento `img`. Elementos `img` têm uma tag de abertura sem uma tag de fechamento. Um elemento sem uma tag de fechamento é conhecido como um elemento nulo.

### Atributos

Atributos em HTML são palavras especiais usadas dentro da tag de abertura de um elemento para controlar seu comportamento. O atributo `src` em um elemento `img` especifica o URL da imagem (onde a imagem está localizada).

Todos os elementos `img` devem ter um atributo `alt`. O texto de um atributo `alt` é usado por leitores de tela para melhorar a acessibilidade. Ele é exibido se a imagem não puder ser carregada.

### Links

Você pode fazer uma ligação com outra página usando o elemento de âncora (`a`). 

O texto de um link deve ser colocado entre as tags de abertura e fechamento de um elemento de âncora (`a`).

Para abrir links em uma nova aba, use o atributo `target` no elemento âncora (`a`). O atributo `target` especifica onde será aberto o link. `target="_blank"` abre o link em uma nova aba ou janela.

### Seções

Antes de adicionar conteúdo novo, você deve usar um elemento `section` para separar o conteúdo de fotos de gatos do resto do conteúdo.

O elemento `section` é usado para definir seções em um documento, como capítulos, cabeçalhos, rodapés ou quaisquer outras seções do documento. É um elemento semântico que ajuda na SEO e na acessibilidade.

### Listas Não Ordenadas

Para criar uma lista de itens não ordenados, use o elemento `ul`. 

O elemento `li` é usado para criar um item em uma lista ordenada ou não ordenada.

### Imagens em Listas

Após a lista não ordenada, adicione uma nova imagem com o valor do atributo `src`.

### Elemento `figure`

O elemento `figure` representa um conteúdo autônomo e permitirá que você associe uma imagem com uma legenda. 

O elemento de legenda da figura (`figcaption`) é usado para adicionar uma descrição à imagem no elemento `figure`.

### Ênfase e Importância

Para dar ênfase a uma palavra ou frase, use o elemento `em`.

O código de uma lista ordenada (`ol`) é semelhante ao de uma lista não ordenada, mas a lista de itens em uma lista ordenada é numerada quando exibida.

### Acessibilidade

Para melhorar a acessibilidade da imagem que você adicionou, adicione um atributo `alt`.

O elemento `strong` é usado para indicar que algum texto é de grande importância ou urgência.

### Formulários

Agora você irá adicionar um formulário web para coletar informações dos usuários.

O elemento `form` é usado para obter informações do usuário, como nome, e-mail e outras.

O atributo `action` indica para onde os dados do formulário devem ser enviados.

No exemplo, `action="/submit-url"` informa ao navegador que os dados do formulário devem ser enviados para o caminho `/submit-url`.

O elemento `input` permite várias formas de coletar dados de um formulário web. Assim como os elementos `img`, elementos `input` são nulos e não precisam de tags de fechamento.

Há muitos tipos de entradas que você pode criar usando o atributo `type`. Você pode facilmente criar um campo de senha, botão de reset ou um controle para permitir que os usuários selecionem um arquivo do computador.

Para que os dados de um formulário sejam acessados pelo local especificado no atributo `action`, você deve dar ao campo de texto um atributo `name` e atribuir um valor para representar os dados sendo enviados.

Texto de placeholder é usado para dar uma dica às pessoas sobre que tipo de informação inserir em um `input`.

Para evitar que um usuário envie seu formulário sem que informações obrigatórias estejam faltando, você precisa adicionar o atributo `required` a um elemento `input`. Não há necessidade de definir um valor para o atributo `required`. Basta adicionar a palavra `required` ao elemento `input`, certificando-se de que há espaço entre ele e outros atributos.

### Botões e Elementos Inline

Mesmo que você tenha adicionado seu botão abaixo do campo de texto, eles aparecem próximos um do outro na página. Isso porque tanto os elementos `input` quanto `button` são elementos inline, que não aparecem em novas linhas.

O botão que você adicionou enviará o formulário por padrão. No entanto, confiar no comportamento padrão pode causar confusão.

### Radio Buttons

Você pode usar botões de opção para perguntas onde deseja apenas uma resposta entre várias opções.

Elementos `label` são usados para ajudar a associar o texto de um elemento `input` ao próprio elemento `input` (especialmente para tecnologias assistivas como leitores de tela).

O atributo `id` é usado para identificar elementos HTML específicos. O valor de cada atributo `id` deve ser único em relação a todos os outros valores de `id` na página.

### Botões de Opção e Nomes

Note que ambos os botões de opção podem ser selecionados ao mesmo tempo. Para que selecionar um botão de opção deselecione automaticamente o outro, ambos os botões devem ter um atributo `name` com o mesmo valor.

Se você selecionar o botão de opção "Indoor" e enviar o formulário, os dados do formulário para o botão serão baseados nos atributos `name` e `value`. Como seus botões de opção não possuem um atributo `value`, os dados do formulário incluirão `indoor-outdoor=on`, o que não é útil quando você tem vários botões.

### Agrupando Inputs

O elemento `fieldset` é usado para agrupar inputs relacionados e labels em um formulário web. Elementos `fieldset` são elementos block-level, o que significa que aparecem em uma nova linha.

O elemento `legend` atua como uma legenda para o conteúdo no elemento `fieldset`. Ele dá aos usuários contexto sobre o que eles devem inserir nessa parte do formulário.

### Checkboxes

Formulários geralmente usam checkboxes para perguntas que podem ter mais de uma resposta. O elemento `input` com um atributo `type` definido como `checkbox` cria uma checkbox.

Há outra maneira de associar o texto de um elemento `input` com o próprio elemento. Você pode aninhar o texto dentro de um elemento `label` e adicionar um atributo `for` com o mesmo valor que o atributo `id` do elemento `input`.

Assim como botões de opção, os dados do formulário para checkboxes selecionados são pares de atributos `name` / `value`. Embora o atributo `value` seja opcional, é uma boa prática incluí-lo em qualquer checkbox ou botão de opção na página.

### Rodapé

O elemento `footer` é usado para definir um rodapé para um documento ou seção. Um rodapé geralmente contém informações sobre o autor do documento, dados sobre direitos autorais, links para termos de uso, informações de contato e muito mais.

### Estrutura do Documento

Observe que tudo o que você adicionou à página até agora está dentro do elemento `body`. Todos os elementos de conteúdo da página que devem ser renderizados na página ficam dentro do elemento `body`. No entanto, outras informações importantes vão dentro do elemento `head`.

O elemento `head` é usado para conter metadados sobre o documento, como seu título, links para folhas de estilo e scripts. Os metadados são informações sobre a página que não são exibidas diretamente na página.

O elemento `title` determina o que os navegadores mostrarão na barra de título ou na aba da página.

Observe que todo o conteúdo da página está aninhado em um elemento `html`. O elemento `html` é o elemento raiz de uma página HTML e envolve todo o conteúdo da página.

Você também pode especificar o idioma de sua página, adicionando o atributo `lang` ao elemento `html`.

