# Lista de comandos

## Comandos git

* git init
* git add
* git commit -m ""
* git status
* git rm
* git log
* git branch
* git checkout
* git pull
* git push
* git merge

# Folhas de Estilo

## 1. [HTML Best Practises - github](https://github.com/hail2u/html-best-practices)

### Geral

* Iniciar com DOCTYPE;

* Não usar DOCTYPE obsoleto, seja simples;

* Usar referências de caracteres numéricos para caracteres de controle ou invisíveis;

* Colocar espaço ao início e ao final do conteúdo do comentário;

* Não negligenciar o fechamento das tags abertas;

* Não misture o formato das tags com espaços vazios ou elementos(ex.: '/');

* Não colocar espaço ao redor das tags nem para valores atribuidos;

* Não misturar caracteres (ex.: começar o comando com letra minúscula e fechar com letra maiúscula);

* Não misture aspas;

* Não separar os atributos com 2 ou mais espaços brancos entre eles;

* Omitir valor de atributo booleano;

* SVG e MathML podem ser usados diretamente em um documento HTML5, por isso, deve-se omitir namespaces;

* Não usar atributos XML;

* Prefira usar o padrão semântico ARIA de forma implícita;

### Elemento raiz

* Adicione o atributo "lang" ao html e mantenha o seu valor o mais curto possível (ex.: en, ja);

* Evite o máximo possível atributos " data-* ";

### Documento metadata

* Adicione o elemento "title";

* Não utilize o elemento "base";

* Adicionar atributo de "title" a folhas de estilo alternadas;

* Para URL, usar o elemento "link";

* Especificar a codificação do caracter do documento;

* Especificar a codificação do caracter do documento primeiro;

* Usar UTF-8;

* Omitir o atributo "type" para CSS;

* Não comente conteúdo do elemento "style";

* Não misturar tags do CSS e JavaScript;

### Seções

* Adicionar o elemento "body";

* Esquecer/não colocar o elemento "hgroup";

* Usar o elemento "address" apenas para informação de contato;

### Conteúdo agrupado

* Não comece com nova linha no elemento "pre";

* Usar elemento apropriado no elemento "blockquote";

* Não incluir atribuição diretamente ao elemento "blockquote";

* Escreva um item da lista por linha, linhas longas são difíceis de ler;

* Use o atributo "type" para o elemento "ol";

* Não use o elemento "dl" para diálogos;

* Coloque o elemento "figcaption" primeiro ou por último dentro do elemento "figure";

* Use o elemento "main";

* Esqueça o elemento "div" o máximo possível;

### Semântica no nível do texto

* Não divida o mesmo link que pode ser agrupado;

* Usar o atributo "download" apenas para baixar um recurso;

* Se necessário, utilize os atributos "rel", "hreflang" e "type";

* Limpar/não utilizar texto link (ex.: Click here);

* Não utilize o elemento "em" para warning or caution;

* Evite ao máximo os elementos "s", "i", "b" e "u";

* Não coloque citações (com aspas) no conteúdo do elemento "q";

* Adicionar o atributo "title" ao elemento "abbr";

* Adicionar o atributo "datetime" ao elemento "time";

* Especifique a linguagem do código com o atributo "class" prefixado com "language-";

* Mantenha o elemento "kbd"o mais simples possível;

* Evite ao máximo o elemento "spam";

* Quebrar linha após o elemento "br";

* Não utilize o elemento "br" apenas para apresentação;

### Edições

* Não passe os elementos "ins" e "del" sobre outros elementos;

### Conteúdo incorporado

* Fornecer o elemento "img" para o elemento "picture";

* Se necessário, adicionar o atributo "alt" para o elemento "img";

* Se possível, atributo "alt" vazio;

* Se possível, omitir o atributo "alt";

* Elemento "iframe" vazio;

* Marcação do conteúdo do elemento "map";

* Fornecer conteúdo de retorno para os elementos "audio" ou "video";

### Dados tabulados (td)

* Escreva uma célula por linha;

* Usar o elemento "th" para células de cabeçalho;

### Formas

* Se possível, omitir o atributo "for";

* Usar o atributo "type" apropriadamente para o elemento "input";

* Adicionar o atributo "value" a " input type="submit" ";

* Adicionar o atributo "title" ao elemento "input" quando tiver o atributo "pattern";

* Não usar o atributo "placeholder" para marcação;

* Escrever um elemento "option" por linha;

* Adicionar o atributo "max" ao elemento "progress";

* Adicionar os atributos "min" e "max" ao elemento "meter";

* Colocar o elemento "legend" primeiro quando estiver contido no elemento "fieldset";

### Scripting

* Omitir o atributo "type" para JavaScript;

* Não comentar conteúdo do elemento "script";

* Não utilizar script-injected no elemento "script";

### Other

* Identação de forma consistente;

* Usar caminho absoluto para links internos;
