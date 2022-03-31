HTML (Linguagem de Marcação de Hipertexto) em inglês (HyperText Markup Language) - É a base(raíz) para a construção de sites porque marca e define os elementos que serão mostrados na página que está sendo consrtuída e todos os elementos devem obrigatoriamente descender da HTML. A linguagem de marcação teve sua origem no ano de 1990 e seu controle é realizado através da World Wide Web Consortium (W3C). Esta linguagem é utilizada principalmente para dar significado e organizar um website. HTML utiliza Tags para fazer a marcação e dar significado à informação.

O que são as Tags que o HTML utiliza e para quê elas servem? - São conjuntos de caracteres que formam um elemento. Algumas Tags necessitam de fechamento e outras não. 

Para as que necessitam de fechamento, é utilizado o sinal de menor ( < ), seguido do nome do elemento e o sinal de maior ( > ) para abertura. Para fechamento, é utilizado o sinal de menor ( < ), seguido de barra ( / ), nome do elemento e o sinal de maior ( > ).

Para as que não necessitam de fechamento, também conhecidos como elementos vazios, somente utilizamos o sinal de menor ( < ), seguido do nome do elemento e o sinal de maior ( > ).

O que são os Elementos? - Eles são formados a partir das Tags e se encontram no meio delas. As Tags definem onde começam e terminam os elementos.

Exs: 
 <!-- A Tag <label> define que o conteúdo do Elemento é uma label (rótulo)  -->
    <label>Informe o seu nome</label>
  
    <!-- A Tag <address> define que o conteúdo do Elemento é um endereço (endereços físicos à virtuais)  -->
    <address>
      Este guia é uma iniciativa da comunidade e do Tableless <a href="http://tableless.com.br/contato">www.tableless.com.br</a>
    </address>

As Tags servem para a marcação e os Elementos servem para conceituar (muitas vezes semanticamente) o conteúdo presente dentro das Tags e possuem um começo e fim determinados.

Atributos - Informações que devem ser passadas pela Tag para que ela funcione. Alguns atributos são globais (funcionam em todas as Tags) e outros são específicos, que podem apenas ser utilizados para Tags específicadas. Atributos possuem nome e valor, alguns são raros e outros mais comuns.

Exs:  

title - Auxílio ao elemento. Similar a dica. 
class - Define uma ou mais classes de um elemento. 
style - Delimita as propriedades CSS em um elemento.

Estrutura básica do HTML - 

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="utf-8">
    <title>Título da página</title>
</head>
<body>
    Seu código aqui
</body>
</html>

Para fazer um Título -

<h1>Aqui vai o texto que é um título</h1>

Para fazer um parágrafo - 

<p>Aqui vai muito texto, um parágrafo</p>

Os considerados elementos básicos no HTML são - 

<base>	O elemento HTML Base (<base>) especifica o endereço (URL) utilizada por todos os endereços relativos contidos dentro de um documento. Há um número máximo de 1 (um) elemento Base <base> do documento.
<head>	O elemento HTML <head> providencia informações gerais (metadados) sobre o documento, incluindo seu título e links para scripts e folhas de estilos.
<link>	O Elemento HTML <link> especifica as relações entre o documento atual e um recurso externo. Possíveis usos para este elemento incluem a definição de uma estrutura relacional para navegação. Este elemento é mais usado para vincular as folhas de estilo.
<meta>	O elemento HTML <meta> define qualquer informação de metadados que não podem ser definidos por outros elementos HTML. (base, link, script, style ou title).
<style>	O elemento HTML <style> contém informações de estilo para um documento ou uma parte do documento. As informações de estilo específico estão contidas dentro deste elemento, geralmente no CSS.
<title>	O elemento HTML <title> (Elemento HTML Título) define o título do documento, mostrado na barra de título de um navegador ou na aba da página. Pode conter somente texto e quaisquer marcações contidas no texto não são interpretadas.

Existem também os elementos de separação de conteúdo, que servem para dividir as partes do documento em partes lógicas -

<address>	O elemento HTML <address> fornece informações de contato para seu ancestral article ou body mais próximo; no segundo caso, ele se aplica ao documento inteiro.
<article>	O Elemento HTML Article (<article>) representa uma composição independente em um documento, página, aplicação, ou site, ou que é destinado a ser distribuido de forma independente ou reutilizável, por exemplo, em sindicação. Este poderia ser o post de um fórum, um artigo de revista ou jornal, um post de um blog, um comentário enviado por um usuário, um gadget ou widget interativos, ou qualquer outra forma de conteúdo independente.
<aside>	O elemento HTML <aside> representa uma seção de uma página que consiste de conteúdo que é tangencialmente relacionado ao conteúdo do seu entorno, que poderia ser considerado separado do conteúdo. Essas seções são, muitas vezes, representadas como barras laterais. Elas muitas vezes contem explicações laterais, como a definição de um glossário; conteúdo vagamente relacionado, como avisos; a biografia do autor; ou, em aplicações web, informações de perfil ou links de blogs relacionados.
<footer>	O elemento HTML de Rodapé (<footer>) representa um rodapé para o seu sectioning content (conteúdo de seção) mais próximo ou sectioning root elemento (ou seja, seu parente mais próximo article, aside, nav, section, blockquote, body, details, fieldset, figure, td). Normalmente um rodapé contém informações sobre o autor da seção de dados, direitos autorais ou links para documentos relacionados.
<header>	O elemento HTML <header> representa um grupo de suporte introdutório ou navegacional. Pode conter alguns elementos de cabeçalho mas também outros elementos como um logo, seções de cabeçalho, formulário de pesquisa, e outros.
<h1> (en-US), <h2> (en-US), <h3> (en-US), <h4> (en-US), <h5> (en-US), <h6> (en-US)	Os elementos HTML <h1>–<h6> representam seis níveis de título de seção. <h1> é o nível de seção mais alto e <h6> é o mais baixo.
<main>	O elemento <main> define o conteúdo principal dentro do body em seu documento ou aplicação. Entende-se como conteúdo principal aquele relacionado diretamente com o tópico central da página ou com a funcionalidade central da aplicação. O mesmo deverá ser único na página, ou seja, dentro do elemento <main> não deverão ser incluidas seções da página que sejam comuns a todo o site ou aplicação, tais como mecanismos de navegação, informações de copyright, logotipo e campos de busca (a não ser, é claro,  caso a função principal do documento seja  fazer algum tipo de busca).
<nav>	O Elemento HTML de Navegação (<nav>) representa uma seção de uma página que aponta para outras páginas ou para outras áreas da página, ou seja, uma seção com links de navegação.
<section>	O elemento HTML <section> representa uma seção genérica contida em um documento HTML, geralmente com um título, quando não existir um elemento semântico mais específico para representá-lo.

Elementos textuais (servem para que o conteúdo textual se organize em forma de blocos ou seções) -

<blockquote>	O Elemento HTML <blockquote> (ou Elemento HTML de citação de bloco) indica que o texto incluído é uma longa citação. Normalmente, este é processado visualmente pelo recuo (ver Notas sobre como mudá-lo). A URL para a fonte da citação pode ser dada usando o atributo cite, enquanto uma representação de texto da fonte pode ser dada usando o cite elemento.
<dd>	A Tag inicial (dd) é obrigatória.
A Tag final (</dd>) pode ser omitida se seguida imediatamente por outro elemento dd, ou se o elemento pai não tiver mais conteúdo.
<div>	O elemento de divisão HTML <div> é um container genérico para conteúdo de fluxo, que de certa forma não representa nada. Ele pode ser utilizado para agrupar elementos para fins de estilos (usando class ou id), ou porque eles compartilham valores de atributos, como lang. Ele deve ser utilizado somente quando não tiver outro elemento de semântica (tal como article ou nav).
<dl>	O elemento HTML Definition List (<dl>) engloba uma lista de pares de termos e descrições. Um uso comum para este elemento é para implementar um glossário ou exibir metadados(uma lista de pares chave e valor).
<dt>	O elemento HTML <dt> (ou Elemento HTML de Definição de Termo) identifica um termo na lista de definição. Este elemento pode ocorrer somente em um elemento filho de dl. Geralmente seguido por um elemento dd; ou multiplos <dt> na mesma linha indicam vários termos  sendo definidos pelo próximo element dd.
<figcaption>	 
<figure>	O Elemento HTML <figure> representa o conteúdo independente, frequentemente com uma legenda (figcaption), e é normalmente referido como uma única unidade. Enquanto ela está relacionada com o fluxo principal, sua posição é independente do fluxo principal.Normalmente, isso é uma imagem, uma ilustração, um diagrama, um trecho de código ou uma esquema que é referenciado no texto principal, mas que pode ser movido para outra página ou para um apêndice, sem afetar o fluxo principal.
<hr>	O elemento HTML <hr> representa uma quebra temática entre elementos de nível de parágrafo (por exemplo , uma mudança da cena de uma história, ou uma mudança de tema com uma seção). Nas versões anteriores do HTML, representava uma linha horizontal. Pode continuar sendo exibida como uma linha horizontal nos navegadores, mas agora está definida em termos semânticos, em vez de termos de apresentação.
<li>	O elemento HTML <li>  (ou a Lista dos Itens de um elemento HTML) é usado para representar um item que faz parte de uma lista. Este item deve estar contido em um elemento pai: uma lista ordenada (ol), uma lista desordenada (ul), ou um menu (menu) e representa uma única entidade dessa lista. Em menus e listas desordenadas a relação de itens é exibida, normalmente, usando pontos de marcação (as bolinhas). Em listas ordenadas eles são, comumente, mostrados com algum contador ascendente - como um número, ou letra - à sua esquerda.
<menu> (en-US)	
<ol>	O Elemento HTML <ol> (ou Elemento HTML de lista ordenada) representa uma lista de itens ordenados. De forma característica esses itens ordenados em uma lista são mostrados com uma contagem que os precede, que pode ser de qualquer tipo, como numerais, letras, algarismos romanos, ou simples símbolos. Esse modelo numerado não é definido na descrição html da página, mas na folha de estilos CSS associada, pela propriedade list-style-type. 
<p>	O elemento HTML <p> representa um parágrafo. Em mídias visuais, parágrafos são representados como blocos indentados de texto com a primeira letra avançada e separados por linhas em branco. Já em HTML, parágrafos são usados para agrupar conteúdos relacionados de qualquer tipo, como imagens e campos de um formulário.

Parágrafos são Elementos block-level, e fecharão automaticamente caso outro Elemento block-level inicie antes da tag de fechamento </p>. Veja "Omissão de tag" abaixo.
<pre>	HTML texto preformatado (<pre>) é a tag utilizada para representar texto pré-formatado. Um texto dentro desse elemento é tipicamente exibido em uma fonte não proporcional da mesma maneira em que o texto original foi disposto no arquivo. Espaços em branco são mantidos no texto da mesma forma em que este foi digitado.  
<ul>	O elemento HTML <ul> (ou elemento HTML de Lista desordenada) representa uma lista de itens sem ordem rígida, isto é, uma coleção de itens que não trazem uma ordenação numérica e as suas posições, nessa lista, são irrelevantes. Caracteristicamente, os itens em uma lista desordenada são exibidos com um marcador que pode ter várias formas, como um ponto, um círculo, ou um quadrado. O tipo de marcador não é definido na descrição HTML da página, mas na CSS associada, utilizando a propriedade list-style-type.


Elementos para utilizar na criação de formulários -

<button>	O Elemento HTML <button> representa um botão clicável.
<datalist>	O elemento HTML Datalist (<datalist>) contém um conjunto de elementos option que representam as opções possíveis para o valor de outros controles.
<fieldset>	O elemento HTML <fieldset> é usado para agrupar elementos, assim como labels (label), dentro de um formulário web.
<form>	O elemento HTML <form> representa uma seção de um documento que contém controles interativos que permitem ao usuário submeter informação a um determinado servidor web.
<input>	
O elemento HTML <input> é usado para criar controles interativos para formulários baseados na web para receber dados do usuário. A semântica de um <input> varia consideravelmente dependendo do valor de seu atributo type.

<label>	Um elemento HTML <label> representa uma legenda para um item em uma interface de usuário. Ele pode estar associado com um elemento de controle, colocando este dentro do elemento label, ou usando o atributo for. Tal controle é chamado o controle etiquetado do elemento etiqueta. Um input pode ser associado a diversas etiquetas (<label>s).
<legend>	O Elemento HTML <legend> (ou Elemento HTML Campo "Legend") representa um rótulo para o conteúdo do seu ancestral fieldset.
<meter>	O elemento HTML meter (<meter>) pode representar um valor escalar dentro de um intervalo conhecido ou um valor fracionário.
<optgroup>	Em um Formulário Web, o elemento HTML <optgroup> cria um agrupamento de opções dentro do elemento select.
<option>	Em um formulário Web, o elemento HTML <option> é usado para criar um controle que representa um item dentro de um elemento HTML5 select, optgroup ou datalist.
<output>	O elemento de saída (<output>) é um elemento no qual um site ou aplicativo pode injetar os resultados de um cálculo ou o resultado de uma ação do usuário.
<progress>	o elemento HTML progress (<progress>) é usado para visualizar o progresso de uma tarefa. Embora as especifidades de como é mostrado ficam a cargo do desenvolvedor, tipicamente, é mostrado como uma barra de progresso.
<select>	O elemento HTML select (<select>) representa um controle que apresenta um menu de opções. As opções dentro do menu são representadas pelo elemento option, que podem ser agrupados por elementos optgroup. As opções podem ser pré-selecionadas para o usuário.
<textarea>	O elemento  HTML <textarea> representa um controle de edição para uma caixa de texto, útil quando você quer permitir ao usuário informar um texto  extenso em formato livre, como um comentário ou formulário de retorno.          

Para adicionar um link- <a href="">Nome escolhido</a>

CSS (em inglês: Cascading Style Sheets) - Define o estilo(aparência) da página criada em HTML. é uma linguagem de folhas de estilos. É a linguagem que define o estilo da página e elementos como cor, fonte, posicionamento dos elementos e layout. Foram criadas novas tags e atributos de estilo para o HTML e em resumo, ele passou a exercer tanto a função de estruturar o conteúdo quanto de apresentá-lo para o usuário final. E isso acarretou em um problema, pois os desenvolvedores não conseguiam mais definir um padrão para os cabeçalhos e os conteúdos. O CSS surgiu para permitir a separação de conteúdo e formato de um documento específicos. Isso permitiu a flexibilização e controle sobre a exibição em um documento, permitiu seu compartilhamento e reduziu a repetição na estrtura do documento. Com isto, as linguagens de marcação passaram novamente a exercer sua função de marcar e estruturar o conteúdo de um documento, enquanto o CSS encarregou-se da aplicação dos estilos necessários para a aparência dela. Isto é feito por meio da criação de um arquivo externo que contém todas as regras aplicadas e com isto, é possível fazer alterações de estilo em todas as páginas de um site e outros documentos que utilizam CSS de forma fácil e rápida. O CSS também permite que as mesmas marcações de um documento sejam apresentadas em diferentes estilos, conforme os métodos de renderização. Cabeçalhos e rodapés geralmente são desenvolvidos em CSS. 

Uma coisa que você notará sobre escrever CSS é que muito disso é sobre caixas — indicar seu tamanho, cor, posição, etc. Muitos dos elementos HTML da sua página podem ser pensados como caixas umas em cima das outras.

Toda essa estrutura é chamada de conjunto de regras (mas geralmente usamos o termo "regra", por ser mais curto). Note os nomes das partes individuais:

Seletor (Selector)
O nome do elemento HTML no começo do conjunto de regras. Ele seleciona o(s) elemento(s) a serem estilizados (nesse caso, elementos <p>). Para dar estilo a um outro elemento, é só mudar o seletor.
Declaração (Declaration)
Uma regra simples como color: red; especificando quais das propriedades do elemento você quer estilizar.
Propriedades (Property)
Forma pela qual você estiliza um elemento HTML. (Nesse caso, color é uma propriedade dos elementos <p>.) Em CSS, você escolhe quais propriedades você deseja afetar com sua regra.
Valor da propriedade (Property value)
À direita da propriedade, depois dos dois pontos, nós temos o valor de propriedade, que escolhe uma dentre muitas aparências possíveis para uma determinada propriedade (há muitos valores color(cor) além do red(vermelho)).
Note outras partes importantes da sintaxe:

Cada linha de comando deve ser envolvida em chaves ({}).
Dentro de cada declaração, você deve usar dois pontos (:) para separar a propriedade de seus valores.
Dentro de cada conjunto de regras, você deve usar um ponto e vírgula (;) para separar cada declaração da próxima.
Então para modificar múltiplos valores de propriedades de uma vez, você deve escrevê-los separados por ponto e vírgula, desse modo:

p {
  color: red;
  width: 500px;
  border: 1px solid black;
}
Copy to Clipboard
Selecionando múltiplos elementos
Você também pode selecionar vários tipos de elementos e aplicar um único conjunto de regras a todos eles. Inclua múltiplos seletores separados por vírgulas. Por exemplo:

p, li, h1 {
  color: red;
}
Copy to Clipboard
Diferentes tipos de seletores
Há muitos tipos diferentes de seletores. Abaixo, nós mostramos apenas os seletores de elementos, que selecionam todos os elementos de um determinado tipo nos documentos HTML. Mas nós podemos fazer seleções mais específicas que essas. Aqui estão alguns dos tipos mais comuns de seletores:

Nome do seletor	O que ele seleciona	Exemplo
Seletor de elemento (às vezes, chamado tag ou seletor de tipo)	Todos os elementos HTML de determinado tipo.	p
Seleciona <p>
Seletor de ID	O elemento na página com o ID específicado. Em uma determinada página HTML, é uma boa prática usar um elemento por ID (e claro, um ID por elemento) mesmo que seja permitido usar o mesmo ID para vários elementos.	#my-id
Seleciona <p id="my-id"> ou <a id="my-id">
Seletor de classe	O(s) elemento(s) na página com a classe específicada (várias instâncias de classe podem aparecer em uma página).	.my-class
Seleciona <p class="my-class"> e <a class="my-class">
Seletor de atributo	O(s) elemento(s) na página com o atributo especificado.	img[src]
Seleciona <img src="myimage.png"> mas não <img>
Seletor de pseudo-classe	O(s) elemento(s) específicado(s), mas somente quando estiver no estado especificado. Ex.: com o mouse sobre ele.	a:hover
Seleciona <a>, mas somente quando o mouse está em cima do link.
Há muito mais seletores para explorar e você pode achar uma lista mais detalhada em nosso Guia de seletores.

Fontes e texto
Agora que exploramos algumas noções básicas de CSS, vamos começar a adicionar mais regras e informações no nosso arquivo estilo.css para deixar nosso exemplo bonito. Vamos começar fazendo nossas fontes e textos parecerem um pouco melhores.

Primeiro de tudo, volte e encontre a fonte do Google Fonts que você armazenou em algum lugar seguro. Adicione o elemento <link> em algum lugar dentro do cabeçalho no index.html (novamente, em qualquer lugar entre as tags <head> e </ head>). Será algo parecido com isto:
<link href="http://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
Copy to Clipboard
Esse código vincula sua página a uma folha de estilo que baixa a família de fontes Open Sans junto com sua página web e permite que você a defina em seus elementos HTML usando sua própria folha de estilos.
Em seguida, exclua a regra existente no seu arquivo estilo.css. Foi um bom teste, mas o texto vermelho não parece muito bom.
Adicione as seguintes linhas em seu lugar, substituindo a linha do espaço reservado pela linha font-family que você obteve do Google Fonts. (font-family significa apenas a(s) fonte(s) que você deseja usar para o seu texto.) Esta regra primeiro define uma fonte base global e o tamanho da fonte para a página inteira (já que <html> é o elemento pai de toda a página, e todos os elementos dentro dele herdam o mesmo font-size e font-family):
html {font-size: 10px; /* px significa "pixels": o tamanho da fonte base é agora de 10 pixels */
  font-family: "Open Sans", sans-serif; /* este deve ser o nome da fonte que você obteve no Google Fonts */
}
Copy to Clipboard
Nota: Qualquer coisa em um documento CSS entre /* e */ é um comentário CSS, que o navegador ignora quando renderiza o código. Este é um lugar para você escrever notas úteis sobre o que você está fazendo.

Agora definiremos tamanhos de fonte para elementos que contêm texto dentro do corpo HTML (<h1> (en-US), <li> e <p>). Também centralizaremos o texto do nosso cabeçalho e definiremos a altura da linha e o espaçamento das letras no conteúdo do corpo para torná-lo um pouco mais legível:
h1 {
  font-size: 60px;
  text-align: center;
}

p, li {
  font-size: 16px;
  line-height: 2;
  letter-spacing: 1px;
}
Copy to Clipboard
Você pode ajustar esses valores de px para o que você desejar, para deixar seu design com a aparência que quiser, mas no geral seu design deve parecer com isso:

Como esperado, o layout CSS é baseado principalmente no modelo de caixas. Cada um dos blocks que ocupam espaço na sua página tem propriedades como essas:

padding, o espaço ao redor do conteúdo (ex.: ao redor do texto de um parágrafo).
border, a linha sólida do lado de fora do padding.
margin, o espaço externo a um elemento.
Nessa seção nós também vamos usar:

width (largura de um elemento).
background-color, a cor atrás do conteúdo de um elemento e do padding.
color, a cor do conteúdo de um elemento (geralmente texto).
text-shadow: cria uma sombra no texto dentro de um elemento.
display: define a maneira de dispor um elemento (não se preocupe com isso ainda).
Então, vamos começar e adicionar mais CSS à nossa página! Continue adicionando essas novas regras à parte inferior da página e não tenha medo de experimentar alterações nos valores para ver o que aparece.



Atributos CSS:

strong {
	color: blue;
}

h1 {
	font-style: italic;
}

Segundo exemplo:

<html>
<head>
    <title>TreinaWeb</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <p>Hello <strong>World</strong></p>
    <h1>Seja bem-vindo ao TreinaWeb!</h1>
</body>
</html>

Fontes:  https://www.treinaweb.com.br/blog/o-que-e-e-como-comecar-com-html-e-css/ , https://tableless.github.io/iniciantes/manual/html/ , https://tableless.github.io/iniciantes/manual/css/, https://developer.mozilla.org/pt-BR/docs/Aprender/Getting_started_with_the_web/HTML_basico , https://developer.mozilla.org/pt-BR/docs/Aprender/Getting_started_with_the_web/CSS_basico
