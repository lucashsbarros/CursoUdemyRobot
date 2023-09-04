## WebTesting
Esse repositório contém testes automatizados através da ferramenta Robot Framework, sendo utilizado Keywords na sua base (sendo Keywords palavras chaves para efetuar os testes automatizados), foi criado os scripts de teste de forma **Procedural** e **GHERKIN com BDD**  e para a realização dos testes utilizamos o site da Amazon. 
## Tecnologias Utilizadas

 1. Python mais atual  *(versão 3.11.5)* Baixar do site:
    https://www.python.org/downloads/
 2. Robot Framework *(versão 6.1.1)*
    
	a) comando para baixar via CMD `pip install robotframework`
	b) caso já tenha instalado uma versão do robot framework utilizar o comando `pip install -U robotframework` para atualizar e `robot --version` para conferir a versão instalada.
	
 4. Instalando as Libraries
	a) SeleniumLibrary *(versão 6.1.1)*
	site: https://github.com/robotframework/SeleniumLibrary/#installation
	comando instalar/atualizar: `pip install -U robotframework-seleniumlibrary`	

	b) RequestLibrary *(versão 1.0a4)*
	site: https://github.com/MarketSquare/robotframework-requests#readme
	comando instalar/atualizar: `pip install -U robotframework-requests`

	**Observação:** caso queira conferir quais versões estão instaladas digite o comando abaixo: `pip list`

 5. Instalando editor de Código

	a) DRACULA OFFICIAL
Pesquisar na parte de Plugins da sua IDE (no nosso caso foi o IntelliJ) 
	
	b) Robot Framework Language Server 1.11
Pesquisar na parte de Plugins da sua IDE (no nosso caso foi o IntelliJ) 

 6. Instalação de WebDrivers
	a) CHROME *(versão 116)*
	Link: 
	https://edgedl.me.gvt1.com/edgedl/chrome/chrome-for-testing/116.0.5845.96/win64/chromedriver-win64.zip	
	
	b) FIREFOX *(versão 117)*
		link: https://github.com/mozilla/geckodriver/releases	
		
	**IMPORTANTE 1** - Deve baixar o WebDrive compativel com a versão do seu navegador.
	**IMPORTANTE 2** - Caso atualize o navegador é OBRIGATÓRIO atualizar os webdrivers
	
	c) Ir em "Editar variaveis do programa" ir até a opção PATH, dar dois cliques, copiar e colar o caminho que houver SCRIPTS no final. Por fim copiar os dois webdrivers .EXE dentro desse caminho 

	d) Conferir se as instalações estão corretas no CMD:

    chromedriver --version
    geckodriver --version

 7. Instalar extensão TRUEPATH (qaworld.ga) no seu navegador

	  link: https://chrome.google.com/webstore/detail/truepath/mgjhkhhbkkldiihlajcnlfchfcmhipmn?gclid=CjwKCAjwrranBhAEEiwAzbhNtXfzMkKUuClIwBabo0ibxFEoljG1MDnTvC2dTwbNl9TrYVFL8YagqhoCtC0QAvD_BwE

## Testes Automatizados
Em construção...

## Notas Gerais
**Importante** - Ressaltar que hoje (30/08/2023) quando utilizamos o site da Amazon para efetuar algum teste automático o mesmo está implantado a ferramenta reCAPTCHA, onde é necessário inserir letras aleatórias, com isso, o teste pode falhar da primeira vez, mas para prosseguir, basta preencher uma vez e rodar o teste novamente que se estiver correto, vai ser validado.
