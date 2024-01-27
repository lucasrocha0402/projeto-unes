<h2>Documentação do projeto</h2>

Primeiramente este é um projeto do curso que estou realizando de Desenvolvimento Web Completo, Que foi feito pelo instrutor Jorge Sant Ana.
Esse projeto tem o proposito de colocar em pratica o conhecimento das tags de HTML(HyperText Markup Language/Linguagem de Marcação de HiperTexto).

<h3>Explicando sobre as tags utilizadas no index.html</h3>

Como padrão estou utilizando no incio do arquivo doctypehtml para definir o tipo de versão do documento HTML, idioma e versão da linguagem e garantindo que o navegador
interprete corretamente. Configurações da página usando a tag meta e o atributo charset no caso estou utilizando o UTF-8 pois é uma codificação de caracter padrão pois abranje
uma vasta gama de caracter por ser bastante utilizada.
já a tag name utilizando o atributo "viewport" especifica que estamos configurando as propriedades de visualização da página.
e o atributo content="width=device-width, initial-scale=1.0": Este é o conteúdo da declaração de viewport. Ele consiste em duas partes:
width=device-width: Isso define a largura da área de visualização do dispositivo como sendo igual à largura da tela do dispositivo. Isso garante que a largura da página se 
ajuste automaticamente ao tamanho da tela do dispositivo, evitando a necessidade de rolagem horizontal.
initial-scale=1.0: Isso define o nível de zoom inicial da página quando ela é carregada pela primeira vez no navegador. Um valor de 1.0 significa que a página será exibida 
sem zoom inicial. Isso é importante para garantir que a página seja exibida corretamente e em escala adequada quando acessada em dispositivos móveis.

A tag body é usada para definir o conteúdo principal de uma página HTML. O atributo background especifica a imagem de fundo para a página. Neste caso, o caminho da imagem é 
midias/fundo.png. Eu utilizei a tag table para organizar o site(Não é uma pratica recomendada mas como ainda não comecei a estudar css e nem javascript fiz com ela mesmo),
estou usando o atributo border com valor 0 para não mostar a borda da tabela, o width 900 (largura de 900 pixels) e estou colocando no centro da pagina), tr para definir a 
linha da tabelas e td para definir os dados dentro da tabela. o primeiro dado é uma imagem de logo que está centralizado nessa linha, tambem fiz um mini cabeçalho onde
uriliza as rotas para outras páginas do site usando a tag a. 

Criei outra linha na tabela para colocar a capa da página usando a tag img e fazendo o conteudo consumir duas celulas de espaço com o atributo colspan.
Em seguida repeti o processo de criar uma nova linha e fazendo essa cosumir duas celulas, utilizei um h2 para informar que o titulo do paragrafo era explicando sobre a universidade
e utilizei a tag p para colocar os paragrafos.  No final da tabela criei outra linha com o mesmo esquema de centralização e coloquei o conteudo do h4 em negrito.

<h2>Explicando algumas tags que estão na pagina quem_somos.html</h2>

Repeti todo o processo que utilizei na página index.html em relação as tags doctyp e configurações trocando apenas a tag title. 
Em uma linha utilizei a tag ol que cria a possibilidade de criar uma lista ordenada e coloquei alguns itens por ordem.

<h2>Explicando algumas tags que estão na página contato.html</h2>

Repeti todo o processo que utilizei na página index.html em relação as tags doctyp e configurações trocando apenas a tag title. 
E em uma linha especifica da tabela coloquei a tag de form(Que criar a possibilidade de usar tags necessarias para um formulario) usei a tag input com o atributo text 
para poder digitar textos, e utilizei a tg textarea para o usuario poder escrever mais e utilizei o inputcom o tipo submit para o usuario poder enviar esses dados.



