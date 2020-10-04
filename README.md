# Template Relatório de Estágio Obrigatório FGA-UnB
 
Template para Relatório de estágio obrigatório adaptado do template de Trabalhos de Conclusão de Cursos (TCC) na Faculdade do Gama (FGA) em Latex. O template de TCC foi
desenvolvido e adaptado pelo professor Edson Alves <edsomjr@gmail.com> e licenciado em Creative Commons Atribuição 3.0: http://creativecommons.org/licenses/by/3.0/ .
O template para Relatório de estágio obrigatório  FGA-UnB foi adaptado por João Paulo Nunes Soares.

Em caso de dúvidas ou problemas com o template, me contate por meio de um dos canais a seguir ou crie uma issue no repositório.
 * Email: paulonsoares@yahoo.com.br
 * Telegram: @jpnsoares
 
 Caso veja alguma funcionalidade não presente, um bug no template ou algo que possa ser melhorado faça um pull request e colabore com outras pessoas. Contribuições são bem aceitas, abra um pull request com a mudança que ache interessante! Ela será analisada o mais breve possível :D

## Utilizando o template no Overleaf

Caso deseje editar este documento no Overleaf, siga os seguintes passos:

1. Realize o download do repositório no formato **.zip**. (Clone -> Download ZIP)

2. No Overleaf, na página "Seus Projetos" clique em *Novo Projeto*(localizado no canto superior esquerdo) e selecione a opção *Carregar Projeto*.

3. Selecione a pasta que você realizou o download no passo 1.

4. Após o projeto carregar, clique em **Menu**(localizado no canto superior esquerdo).

5. Na seção Configurações, selecione o arquivo **main.tex** como Documento Principal.

6. Compile o projeto.


## Instalando o abnTeX2 para compilar na máquina

### Ubuntu 12.10 ou superior

Uma vez que a versão recomendada do Tex Live é a 2012 ou superior, o processo de
instalação via apt-get funciona apenas a partir da versão 7.0 do Debian (também 
conhecida como Wheezy) e suas derivadas, como por exemplo Ubuntu 12.10 (também 
conhecida como Quantal Quetzal), Linux Mint 14, entre outras.

Para instalar o abnTeX2 (e as respectivas dependências, como o próprio TeXLive) 
em uma distribuição Debian ou derivada, utilize a instalação via apt-get (ou 
outro gerenciador de pacotes que preferir):

Adicione a seguinte linha ao arquivo /etc/apt/sources.list:
	
	deb http://distrib.abntex2.googlecode.com/hg/debian/ testing main

Opcionalmente, adicione a linha abaixo caso deseje baixar os fontes:

	deb-src http://distrib.abntex2.googlecode.com/hg/debian/ testing main

Adicione a chave pública ao chaveiro do apt:

	$ wget -O - http://distrib.abntex2.googlecode.com/hg/debian/89C55467.asc|sudo apt-key add - 

Instale o abntex2:

	$ sudo apt-get update && sudo apt-get install abntex2

Para atualizar uma instalação já existente, feita a partir do repositório:
	
	$ sudo apt-get update && sudo apt-get upgrade

Após o processo de instalação, você poderá ler os manuais e testar os exemplos 
que estarão disponíveis nos diretórios /usr/share/doc/abntex2/pdf e 
/usr/share/doc/abntex2/latex respectivamente.

Fonte: https://code.google.com/p/abntex2/wiki/InstalacaoLinux

### Ubuntu 12.04 ou inferior

Conforme consta na página de [instalação do abnTeX2 em distribuições GNU/Linux](https://code.google.com/p/abntex2/wiki/InstalacaoLinux#Instala%C3%A7%C3%A3o_autom%C3%A1tica_do_TeX_Live_e_do_abnTeX2_(recomendado)
, a instalação via apt-get funciona apenas a partir da versão 12.10 do Ubuntu, 
pois é nela que está disponível a versão 2012 do Tex Live, que é a recomendada 
para utilização com o abnTeX2.

Para instalar o abnTeX2 no Ubuntu 12.04 é necessário, pelo menos, atualizar o 
Tex Live. Uma das formas possíveis é utilizando os pacotes existentes no 
repositório [texlive-backports](https://launchpad.net/~texlive-backports/+archive/ppa)
, conforme orientações abaixo.

Adicione o repositório texlive-backports, digitando o seguinte em um terminal:

	$ sudo add-apt-repository ppa:texlive-backports/ppa

Caso o pacote texlive do Ubuntu 12.04 já esteja instalado digite:
	
	$ sudo apt-get update && sudo apt-get upgrade

Caso o pacote texlive do Ubuntu 12.04 ainda não esteja instalado digite:

	$ sudo apt-get update && sudo apt-get install texlive

Outra forma de atualizar o Tex Live é manualmente, conforme descrito na página 
de [instalação do abnTeX2 em distribuições GNU/Linux](https://code.google.com/p/abntex2/wiki/InstalacaoLinux#Instala%C3%A7%C3%A3o_manual_a_partir_do_instalador_do_TUG)

Fonte: https://code.google.com/p/abntex2/wiki/FAQ#Por_que_eu_não_consigo_instalar_o_abnTeX2_no_Ubuntu_12.04_via_a

### Outras distribuições linux

Informações para instalar o abnTeX2 em outras distribuições linux:

https://code.google.com/p/abntex2/wiki/InstalacaoLinux

### Windows

Informações para instalar o abnTeX2 no Windows:

https://code.google.com/p/abntex2/wiki/InstalacaoWindows

### Mac OS

Informações para instalar o abnTeX2 no Mac OS X:

https://code.google.com/p/abntex2/wiki/InstalacaoMac

## Compilando

Para compilar o texto através do Makefile digite:

	$ make clean
	$ make
	
	
## English

# Template Compulsory Internship Report FGA-UnB
 
Template for Report of mandatory internship adapted from the Template for Course Completion Works (TCC) at Faculdade do Gama (FGA) in Latex. The CBT template was
developed and adapted by professor Edson Alves <edsomjr@gmail.com> and licensed in Creative Commons Attribution 3.0: http://creativecommons.org/licenses/by/3.0/.
The template for the FGA-UnB Mandatory Internship Report was adapted by João Paulo Nunes Soares.

In case of doubts or problems with the template, contact me through one of the channels below or create an issue in the repository.
 * Email: paulonsoares@yahoo.com.br
 * Telegram: @jpnsoares

## Using the template in Overleaf

If you want to edit this document in Overleaf, follow these steps:

1. Download the repository in **. Zip ** format. (Clone -> Download ZIP)

2. In Overleaf, on the "Your Projects" page click on * New Project * (located in the upper left corner) and select the option * Load Project *.

3. Select the folder you downloaded in step 1.

4. After the project loads, click ** Menu ** (located in the upper left corner).

5. In the Settings section, select the ** main.tex ** file as the Main Document.

6. Compile the project.


## Installing abnTeX2 to compile on the machine

### Ubuntu 12.10 or higher

Since the recommended version of Tex Live is 2012 or higher, the process of
installation via apt-get works only from version 7.0 of Debian (also
known as Wheezy) and its derivatives, such as Ubuntu 12.10 (also known as
known as Quantal Quetzal), Linux Mint 14, among others.

To install abnTeX2 (and its dependencies, like TeXLive itself)
on a Debian or derived distribution, use the installation via apt-get (or
other package manager you prefer):

Add the following line to the /etc/apt/sources.list file:

deb http://distrib.abntex2.googlecode.com/hg/debian/ testing main

Optionally, add the line below if you want to download the fonts:

deb-src http://distrib.abntex2.googlecode.com/hg/debian/ testing main

Add the public key to the apt keyring:

$ wget -O - http://distrib.abntex2.googlecode.com/hg/debian/89C55467.asc|sudo apt-key add -

Install abntex2:

$ sudo apt-get update && sudo apt-get install abntex2

To update an existing installation, made from the repository:

$ sudo apt-get update && sudo apt-get upgrade

After the installation process, you can read the manuals and test the examples
which will be available in the / usr / share / doc / abntex2 / pdf and
/ usr / share / doc / abntex2 / latex respectively.

Source: https://code.google.com/p/abntex2/wiki/InstalacaoLinux

### Ubuntu 12.04 or less

As stated in the [installation of abnTeX2 on GNU / Linux distributions] page (https://code.google.com/p/abntex2/wiki/InstalacaoLinux#Instala%C3%A7%C3%A3o_autom%C3%A1tica_do_TeX_Live_e_do_abnTeX2_ (recommended)
, installation via apt-get works only with Ubuntu version 12.10,
because it is there that the 2012 version of Tex Live is available, which is the recommended one
for use with abnTeX2.

To install abnTeX2 on Ubuntu 12.04 it is necessary, at least, to update the
Tex Live. One of the possible ways is to use the existing packages in the
[texlive-backports] repository (https://launchpad.net/~texlive-backports/+archive/ppa)
, according to the guidelines below.

Add the texlive-backports repository by typing the following in a terminal:

$ sudo add-apt-repository ppa: texlive-backports / ppa

If the texlive package for Ubuntu 12.04 is already installed type:

$ sudo apt-get update && sudo apt-get upgrade

If the Ubuntu 12.04 texlive package is not yet installed, type:

$ sudo apt-get update && sudo apt-get install texlive

Another way to update Tex Live is manually, as described on the page
[installation of abnTeX2 on GNU / Linux distributions] (https://code.google.com/p/abntex2/wiki/InstalacaoLinux#Instala%C3%A7%C3%A3o_manual_a_partir_do_instalador_do_TUG)

Source: https://code.google.com/p/abntex2/wiki/FAQ#Por_que_eu_não_consigo_instalar_o_abnTeX2_no_Ubuntu_12.04_via_a

### Other linux distributions

Information for installing abnTeX2 on other Linux distributions:

https://code.google.com/p/abntex2/wiki/InstalacaoLinux

### Windows

Information for installing abnTeX2 on Windows:

https://code.google.com/p/abntex2/wiki/InstalacaoWindows

### Mac OS

Information for installing abnTeX2 on Mac OS X:

https://code.google.com/p/abntex2/wiki/InstalacaoMac

## Compiling

To compile the text through the Makefile type:

$ make clean
$ make


