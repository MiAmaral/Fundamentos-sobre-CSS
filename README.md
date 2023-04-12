# ✨ Projeto desenvolvido para estudo do CSS, promovido pelo programa START da Capgemini e elaborado pela ProWay ✨

• **Sintaxe CSS**:

    · Seletor: É utilizado para selecionar um ou mais elementos HTML aos quais se deseja aplicar o estilo. É escrito antes das chaves { } e seguido por um conjunto de declarações CSS. 

    · Declaração: É composta por uma ou mais propriedades CSS e seus valores, que definem como os elementos selecionados devem ser estilizados. Cada declaração é separada por um ponto-e-vírgula (;) e é escrita dentro das chaves { } após o seletor. 

    · Propriedade: É uma característica do estilo que se deseja aplicar aos elementos selecionados. As propriedades CSS são escritas em minúsculas e separadas dos valores por dois pontos (:). 

• **Formas de declarar CSS**:

    · Inline: A declaração CSS é adicionada diretamente na tag HTML, utilizando o atributo "style". 

    · Interno: A declaração CSS é incluída na seção <head> do documento HTML, utilizando a tag < style >. 

    · Externo: A declaração CSS é armazenada em um arquivo externo com extensão .css e é vinculada ao documento HTML por meio da tag <link>. 

• **Seletores de CSS**:
    ↳ São usados para aplicar estilos a elementos HTML específicos.

    · Class: É um atributo HTML que pode ser atribuído a um ou mais elementos e, em seguida, referenciado em um seletor CSS para aplicar um estilo a todos os elementos com a mesma classe. As classes são definidas no HTML com o atributo "class", e no CSS são referenciadas com um ponto antes do nome da classe.

    · ID (identificador): É um atributo HTML exclusivo que é atribuído a apenas um elemento. Os IDs são definidos no HTML com o atributo "id", e no CSS são referenciados com um # antes do nome do ID. Ao contrário das classes, os IDs devem ser exclusivos em todo o documento HTML. O uso de IDs deve ser limitado a casos específicos em que um estilo precisa ser aplicado apenas a um elemento único na tela.

    . Tag: O seletor de tag em CSS é usado para selecionar todos os elementos HTML com o mesmo nome de tag e aplicar estilos a eles. 

    A ordem de aplicação em cascata é: Tag (menos específico) -> Class -> Id (mais específico).

• **Representação das cores em CSS**:

    · Palavras-chave: O CSS define uma série de palavras-chave pré-definidas que representam cores comuns. Por exemplo, "red" representa a cor vermelha, "blue" representa a cor azul e assim por diante. 

    · Valores hexadecimais: Os valores hexadecimais são uma maneira de representar cores usando uma combinação de seis números ou letras. Os valores hexadecimais começam com o caractere "#", seguido por seis dígitos hexadecimais. Cada par de dígitos representa a quantidade de vermelho, verde e azul (RGB) em uma cor. 

    · Valores RGB: Representam as quantidades de vermelho, verde e azul (RGB) em uma cor. Os valores são escritos como uma série de três números separados por vírgulas, entre parênteses. Cada número representa uma cor primária (vermelho, verde ou azul) e varia de 0 a 255. 
       ↳ Também é possível usar valores RGBA (RGB com um valor alfa), que permitem especificar a opacidade da cor.

• **5 propriedades do fundo em CSS**:

    · Background-color: Define a cor de fundo de um elemento.

    · Background-image: Define uma imagem de fundo para um elemento.

    · Background-repeat: Define se a imagem de fundo deve ser repetida ou não, tanto horizontalmente como verticalmente.

    · Background-position: Define a posição inicial da imagem de fundo em relação ao elemento. O valor pode ser definido em porcentagem, pixels ou palavras-chave como "top", "bottom", "center", "left" e "right".

    · Background-size: Define o tamanho da imagem de fundo. O valor pode ser definido em pixels, porcentagem ou palavras-chave como "cover" (a imagem será ampliada ou reduzida para cobrir todo o elemento) ou "contain" (a imagem será ampliada ou reduzida para caber dentro do elemento).

• **As propriedades de fonte em CSS**:

    · Font-family: Define o tipo de fonte a ser usada. É possível especificar uma lista de fontes em ordem de preferência, separando-as por vírgulas. Caso uma fonte não esteja disponível, a próxima fonte da lista será usada em seu lugar.
    
    · @font-face: Permite ao desenvolvedor usar fontes personalizadas que não estão disponíveis nos sistemas do usuário. Com essa propriedade, o desenvolvedor pode definir o caminho de um arquivo de fonte e nomear a fonte.

    · Font-size: Define o tamanho da fonte. O valor pode ser especificado em pixels, ems, rems, porcentagens ou palavras-chave.

    · Font-style: Define o estilo da fonte, que pode ser normal, italic ou oblique.

    · Font-weight: Define a espessura da fonte, que pode ser normal, bold, lighter ou bolder. 

    · Font-variant: É usada para especificar a variação da fonte, como o uso de letras maiúsculas pequenas (small-caps) ou a variação de fontes com caracteres específicos.

    · Font-size: Define o tamanho da fonte. O valor pode ser especificado em pixels, ems, rems, porcentagens ou palavras-chave. A melhor opção, no momento, é rems.

• **As propriedades de texto em CSS**:

    · Text-indent: É usada para definir o recuo da primeira linha do texto dentro de um elemento.

    · Text-align: Defini o alinhamento do texto dentro de um elemento, como alinhamento à esquerda, à direita, centralizado ou justificado.

    · Text-decoration: É usada para adicionar decorações ao texto, como sublinhado, sobrelinhado, tachado ou nenhum decoração.

    · Letter-spacing: Usado para definir o espaçamento entre caracteres do texto, permitindo aumentar ou diminuir o espaço entre caracteres.

    · Text-transform: É usada para transformar o texto em maiúsculas, minúsculas ou capitalizar as primeiras letras das palavras. Essa propriedade pode melhorar a legibilidade do texto e destacar determinadas palavras ou frases.
         ↳ Enquanto text-transform é usado para transformar todo o texto em maiúsculas, minúsculas ou capitalizar as primeiras letras das palavras, font-variant é usado para especificar a variação da fonte, como o uso de letras maiúsculas pequenas ou outras variações disponíveis na fonte.

• **Link no CSS**:
    ↳ Para alterar a aparência de um link é importante utilizar pseudo-seletores, que são palavras-chave que precedem os seletores CSS e que permitem selecionar elementos com base em seu estado ou posição no documento. Alguns mais utilizados são:

    · :hover: É acionado quando o usuário passa o mouse sobre o link
    · :active: Acionado quando o link é clicado. 
    · :visited: acionado quando o link já foi visitado pelo usuário.

• **Dimensões no CSS**:
   ![Modelo de Caixa](https://marcoalbasini.b-cdn.net/web/wp-content/uploads/2021/12/box-model.png)

    · Box-sizing: Define como o tamanho total de um elemento é calculado, levando ou não em conta a sua borda e preenchimento interno (padding). Os valores possíveis são "content-box" (tamanho total é a soma do conteúdo + borda + preenchimento) e "border-box" (tamanho total é a soma do conteúdo + preenchimento, incluindo a borda).

    · Width: Define a largura do elemento. Pode ser especificada em pixels, em porcentagem, em unidades de medida relativas (como "em" ou "rem") ou como um valor automático.

    · Height: Define a altura do elemento. Pode ser especificada da mesma forma que a largura.

    · Display: Define como o elemento deve ser exibido na página. Os valores mais comuns são "block" (elemento ocupa toda a largura disponível e é exibido em uma nova linha), "inline" (elemento é exibido na mesma linha que o conteúdo anterior e seguinte, ocupando apenas o espaço necessário) e "inline-block" (semelhante a "inline", mas com possibilidade de definir largura e altura).

    · Padding: Define o preenchimento interno do elemento, isto é, a distância entre o conteúdo e a borda do elemento. Pode ser especificado individualmente para cada lado (top, right, bottom, left) ou em conjunto com um único valor (que será aplicado em todos os lados).

    · Border: Define a borda do elemento, que pode ter largura, estilo e cor definidos individualmente para cada lado. Pode ser especificado em conjunto com um único valor (que será aplicado em todos os lados) ou em formato abreviado (por exemplo, "border: 2px solid red").

    · Margin: Define a margem externa do elemento, isto é, a distância entre a borda do elemento e o elemento anterior ou seguinte na página. Pode ser especificado individualmente para cada lado ou em conjunto com um único valor (que será aplicado em todos os lados).