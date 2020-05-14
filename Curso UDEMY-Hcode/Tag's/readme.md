# Todas as Tag's Utilizadas no HTML e suas Funções

1. html = Tag usada para definir um documento HTML. Tag raíz da estrutura do documento (Exceção da DOCTYPE)

2. <DOCTYPE = Tag usada para o navegador reconhecer a versão do html como o html 5 ( <doctype html>)

3. <!(--Comment--)> = Comentários no html

4. body = Onde tá o corpo do nosso código html, todos os conteúdos da página
	- Por default, ela vem com { display: block / margin: 8px}
	- **Reset da tag body pro css: <style> body{ margin: 0; } </body>**

5. head = Serve como contêiner para as tags de cabeçalho. É onde serão feitas as configurações( primeiro a ser carregado da página)

6. title = Definir o título principal do documento
	- É ideal cada página ter um title único
	- As buscas do google, são baseadas na tag title
	- Filha da tag head

7. <meta = Usada para definir um metadado que será utilizado no cabeçalho do site
	- Possui todos os atributos globais
	- Atributos especificos:
		- charset: Define qual a codificação de caracteres foi usada no documento (ex: <meta charset="utf-8"/> )
		- content: Define o conteúdo associado ao http-equiv
		- http-equiv: Prove um cabeçalho http com informação do conteúdo do atributo(content-type/default-style/refresh)
			- <meta http-equiv="Refresh" content="5"> (Dá um comando para a página atualizar a cada 5 seg)
			- <meta http-equiv="Refresh" content="5;URL=title.html"> (A página atualiza em 5 seg e redireciona para a url informada)
		- name: Define o nome do metadado (application-name/author/description/generator/keywords/viewport)
			- <meta name = "application-name" content="Exemplo App"> (Dá nome ao aplicativo ou ao site)
			- <meta name = "description" content=" Esta página é um exemplo"> (Dá uma descrição para a página)
			- <meta name= "keywords" content="HTML5,meta,site,pagina"> (Dá palavras-chaves para buscas da página)
			- <meta name="author" content="Rafael Brito"> (dá um autor para a página)
			- <meta name="generator" content=" Visual Studio Code"> (informa em qual plataforma foi idealizado aquela página)

8. p = Usada para definir um parágrafo
	- Por padrão CSS, já vem com um espaçamento de 1em no topo e embaixo (ou seja quebra linha entre uma tag p e outra)

9. h1 = Usada para definir o primeiro cabeçalho mais importante da página
	- É importante que uma página tenha apenas uma tag h1

10. h2 = Usada para definir o segundo cabeçalho mais importante da página
	- É importante que já tenha uma tag h1 para ser utilizada a h2
	- Pode ter mais de uma, por corresponder a um subtítulo

11. h3 = Usada para definir o terceiro cabeçalho mais improtante da página
	- É importante que já tenha uma tag h1 e h2 
	- Pode ter mais de uma

12. h4 = Usada para definir o quarto cabeçalho mais importante da página
	- É importante que já tenha as tag's anteriores	

13. h5 = Usada para definir o quinto cabeçalho mais importante da página
	- É importante que já tenha as tag's anteriores

14. h6 = Usada para definir o sexto cabeçalho mais importante da página e ÚLTIMO!
	- É importante que já tenha as tag's anteriores
**Obs: É importante que caso queira uma fonte menor e não tenha utilizado as tag's h anteriores a h6, é recomendado alterar o padrão CSS do style da tag h posterior para o campo desejado**

15. <style = Usada para definir estilos CSS no próprio documento html 
	- atributos especificos
		- media = define qual dispositivo de midia o estilo se aplica
		- type = define o typo de mídia (text/css)
		
16. script = Usada para definir um script em JS executado no lado do cliente (é executado na página e não no servidor)
	- A tag permite ser escrito dentro dela ou apontar uma fonte externa(JS)
	- Atributos especificos
		- async = define q o script será executado d eforma assíncroma ( Funciona apenas para scripts externos)
		- charset = define o padrão de caracteres usados
		- defer = define que o script só será executado depois da página ser carregada
		- src = define a fonte externa do script
			- Ex: <script src="nome_do_arquivo.js"></script>
		- type = define o tipo de mídia do script
** Obs: a tag script deve ser escrita antes da tag body fechar **

17. div = usada para criar uma divisão ou seção do documento
	- Geralmente usada como contêiner para outros elementos

18. span = Usada para agrupar texto ou tags em um documento 
	- Não fornece nenhuma alteração visual por padrão
 	- seu objetos é aplicar um CSS pra texto
	- Ex: "<p Testando o <span class "vermelho">uso</span> da tag /p>" (<style> .vermelho { color: red; } </style>)

19. link =  Usada para definir uma assosiação entre o documento atual e um externo ( ** Criei um arquivo .html com exemplos ** )
	- Uso mais comum para linkar com um documento CSS
	- Recomendado o uso dentro do HEAD
	- Atributos Específicos
		- crossorigin = define como o elemento lida com solicitações de origem cruzada
			- anonymous, use-credentials
		- href = define o link referente ao documento que será associado
			- url
		- hreflang = define a linguagem do documento associado
			- código de linguagem
		- media = define em qual dispositivo se aplica este documento 
		- rel = define o relacionamento entre o documento atual e o associado
			- alternate, author, dns-prefetch, help, icon, license, next, pingback
			- preconnect, prefetch, preload, prerender, prev, search, stylesheet
		- sizes = define um tamanho de largura e altura para associação de ícones
			- AlturaxLargura
		- type = define o tipo de mídia do documento associado
			- tipo de mídia

20. noscript = Define um conteúdo alternativo para usuários que desativaram scripts no navegador
	- Só será exibido se não houve suporte para script

21. embed = Usada para definir um conteúdo externo embutido
	- Atributos especificos
		- height = define a altura do conteúdo embutido
		- src = define a fonte do conteúdo embutido
		- type = define o tipo do conteúdo embutido
		- width = define a largura do conteúdo embutido

22. object = Usada para definir um objeto incorporado no documento
	- É possivel incorporar um aúdio, vídeo, pdf, applets Java, Activex e etc
	- Atributos especificos
		- data = Define a url do recurso que será usada como objeto
		- form = Define a qual formulário esse objeto pertence 
			- id do formulário
		- height = Define a altura do objeto
		- name = Define o nome do objeto
		- type = Define o tipo de mídia do objeto
		- usemap = Define o nome do mapa de imagem para ser usado com o objeto 
			- id do objeto
		- width = Define a largura do objeto

23. param = Usada para definir um parâmetro para plugin incorporados com a tag object
	- Atributos específicos
		- name 
			- nome do parâmetro
		- value
 			- valor do parâmetro

24. base = Usada para definir um URL padrão para todos os links da página
	- Pode havar no máximo uma tag base dentro da tag head
	- Se a tag base estiver presente ela deverá ter um atributo href ou target, ou ambos
	- Atributos especificos
		- href = Define o url base para todos os links da página
		- target = define onde o link deverá ser aberto
			- _blank, _parent, _self, _top, Nome de um frame

24. iframe = Usada para definir um quadro ou janela embutido	
	- O quadro é usado para incorporar outro documento no documento html atual
	- Atributos Específicos
		- height = define a altura do quadro
		- name = define o nome
		- sandbox = ativa conteudos restritos 
			- allow-forms, allow-pointer-look, allow-popups, allow-same-origins, allow-scripts,allow-top-navigation
		- src = Define qual a fonte do documento a ser embutido
		- srcdoc = Define qual a estrutura do documento a ser embutido
		- width = Define a largura do quadro

25. a = Usada para criar hyperlinks e vincular uma pagina html com outra
	- Por padrão vem sempre com um sublinhado pra identificar que é um link
	- Atributos Especificos
		- download = usado para forçar um download do destino do link
		- href = define qual o endereço do link de destino
		- hreflang = define qual a linguagem do link de destino
		- media = define qual a mídia ou dispositivo do link do destino
		- ping = Endereço de rastreio para monitorar ciques no link de destino
		- referrerpolicy = define qual referenciador deve ser enviado
		- rel = define qual a relação do documento atual e o destino 
		- target = define onde o link deverá ser aberto
		- type = define o tipo de mídia do link de destino
<h2> ** Estrutura do URL ** </h2> 
	- protocolo://domínio:porta/caminho/recurso?parâmetros#fragmento
	- Exemplos:
		- https://www.hcode.com.br = Protocolo + domínio
		- https://hcode.com.br/#/contato = Protocolo + domínio + fragmento
		- https://google.com/search?q=hcode = Protocolo + domínio + recurso + parâmetro
		- http://localhost:8000 = Protocolo + domínio + porta
<h2> URI </h2>
	- Uniform Resource Indentifier - Identificador Padrão de Recursos
	- Usado para identificar um recurso
		- https = Identificador de um site seguro	
		- http = Identificador de um site
		- ftp = Identificador de um transferido de arquivos
		- file = Identificador de um arquivo local
		- mailto = Identificador de um email
		- tel = Identificador de um telefone 
		- javascript = Identificador de código JavaScript
	- Estilo CSS Padrão da Tag a
		- a:link{
			color:blue;
			text-decoration: underline;
			cursor: pointer; }
		- a:visited{
			color: #551A8B }
		- a:link:active{
			color: red; }
** Obs: Exemplos Práticos no arquivo a.html **

26. img = Usada para inserir imagem na página
	- Os atributos src e alt são obrigatórios 
	- Atributos Específicos
		- alt = define um texto alternativo para imagem
		- crossorigin = define como o elemento lida com solicitações de origem cruzada
		- height = define a altura da imagem
		- ismap = define a imagem como um mapa de imagem do lado do servidor 
		- longdesc = define uma descrição detalhada da imagem
		- sizes = define tamanhos alternativos da imagem
		- src = define qual a fonte/link da imagem
		- srcset = define a url da imagem em diferentes situações 
		- usemap = define a imagem como um mapa de imagem do lado do cliente
		- width = define a largura da imagem
 ** Obs: Exemplos Práticos no arquivo a.html **

