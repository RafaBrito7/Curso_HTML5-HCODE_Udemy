# Todas as Tag's Utilizadas no HTML e suas Funções

1. <html> = Tag usada para definir um documento HTML. Tag raíz da estrutura do documento (Exceção da DOCTYPE)

2. <DOCTYPE> = Tag usada para o navegador reconhecer a versão do html como o html 5 ( <doctype html>)

3. <!-- Comment --> = Comentários no html

4. <body> = Onde tá o corpo do nosso código html, todos os conteúdos da página
	- Por default, ela vem com { display: block / margin: 8px}
	- **Reset da tag body pro css: <style> body{ margin: 0; } </body>**

5. <head> = Serve como contêiner para as tags de cabeçalho. É onde serão feitas as configurações( primeiro a ser carregado da página)

6. <title> = Definir o título principal do documento
	- É ideal cada página ter um title único
	- As buscas do google, são baseadas na tag title
	- Filha da tag head

7. <meta> = Usada para definir um metadado que será utilizado no cabeçalho do site
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

8. <p> = Usada para definir um parágrafo
	- Por padrão CSS, já vem com um espaçamento de 1em no topo e embaixo (ou seja quebra linha entre uma tag p e outra)

9. <h1> = Usada para definir o primeiro cabeçalho mais importante da página
	- É importante que uma página tenha apenas uma tag h1

10. <h2> = Usada para definir o segundo cabeçalho mais importante da página
	- É importante que já tenha uma tag h1 para ser utilizada a h2
	- Pode ter mais de uma, por corresponder a um subtítulo

11. <h3> = Usada para definir o terceiro cabeçalho mais improtante da página
	- É importante que já tenha uma tag h1 e h2 
	- Pode ter mais de uma

12. <h4> = Usada para definir o quarto cabeçalho mais importante da página
	- É importante que já tenha as tag's anteriores	

13. <h5> = Usada para definir o quinto cabeçalho mais importante da página
	- É importante que já tenha as tag's anteriores

14. <h6> = Usada para definir o sexto cabeçalho mais importante da página e ÚLTIMO!
	- É importante que já tenha as tag's anteriores
**Obs: É importante que caso queira uma fonte menor e não tenha utilizado as tag's h anteriores a h6, é recomendado alterar o padrão CSS do style da tag h posterior para o campo desejado

15. <style> = Usada para definir estilos CSS no próprio documento html 
 