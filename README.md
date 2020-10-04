# Template Relatório de Estágio Obrigatório FGA-UnB
 
Template para Relatório de estágio obrigatório adaptado do template de Trabalhos de Conclusão de Cursos (TCC) na Faculdade do Gama (FGA) em Latex. O template de TCC foi
desenvolvido e adaptado pelo professor Edson Alves <edsomjr@gmail.com> e licenciado em Creative Commons Atribuição 3.0: http://creativecommons.org/licenses/by/3.0/ .
O template para Relatório de estágio obrigatório  FGA-UnB foi adaptado por João Paulo Nunes Soares.

Em caso de dúvidas ou problemas com o template, me contate por meio de um dos canais a seguir ou crie uma issue no repositório.
 * Email: paulonsoares@yahoo.com.br
 * Telegram: @jpnsoares

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


# Modèle de rapport de stage obligatoire FGA-UnB
 
Modèle de rapport de stage obligatoire adapté du modèle de travaux d'achèvement de cours (TCC) à Faculdade do Gama (FGA) en Latex. Le modèle CBT était
développé et adapté par le professeur Edson Alves <edsomjr@gmail.com> et sous licence Creative Commons Attribution 3.0: http://creativecommons.org/licenses/by/3.0/.
Le modèle de rapport de stage obligatoire FGA-UnB a été adapté par João Paulo Nunes Soares.

En cas de doute ou de problème avec le modèle, contactez-moi via l'un des canaux ci-dessous ou créez un problème dans le référentiel.
 * Courriel: paulonsoares@yahoo.com.br
 * Télégramme: @jpnsoares

## Utilisation du modèle dans Overleaf

Si vous souhaitez modifier ce document dans Overleaf, procédez comme suit:

1. Téléchargez le référentiel au format **. Zip **. (Cloner -> Télécharger ZIP)

2. Dans Overleaf, sur la page "Your Projects", cliquez sur * New Project * (situé dans le coin supérieur gauche) et sélectionnez l'option * Load Project *.

3. Sélectionnez le dossier que vous avez téléchargé à l'étape 1.

4. Une fois le projet chargé, cliquez sur ** Menu ** (situé dans le coin supérieur gauche).

5. Dans la section Paramètres, sélectionnez le fichier ** main.tex ** comme document principal.

6. Compilez le projet.


## Installation de abnTeX2 à compiler sur la machine

### Ubuntu 12.10 ou supérieur

Étant donné que la version recommandée de Tex Live est 2012 ou supérieure, le processus de
l'installation via apt-get ne fonctionne qu'à partir de la version 7.0 de Debian (également
connu sous le nom de Wheezy) et ses dérivés, tels que Ubuntu 12.10 (également connu sous le nom de
connu sous le nom de Quantal Quetzal), Linux Mint 14, entre autres.

Pour installer abnTeX2 (et ses dépendances, comme TeXLive lui-même)
sur une distribution Debian ou dérivée, utilisez l'installation via apt-get (ou
autre gestionnaire de paquets que vous préférez):

Ajoutez la ligne suivante au fichier /etc/apt/sources.list:

deb http://distrib.abntex2.googlecode.com/hg/debian/ testing main

Si vous le souhaitez, ajoutez la ligne ci-dessous si vous souhaitez télécharger les polices:

deb-src http://distrib.abntex2.googlecode.com/hg/debian/ testing main

Ajoutez la clé publique au trousseau de clés apt:

$ wget -O - http://distrib.abntex2.googlecode.com/hg/debian/89C55467.asc|sudo apt-key add -

Installez abntex2:

$ sudo apt-get update && sudo apt-get install abntex2

Pour mettre à jour une installation existante, réalisée à partir du référentiel:

$ sudo apt-get mise à jour && sudo apt-get mise à jour

Après le processus d'installation, vous pouvez lire les manuels et tester les exemples
qui sera disponible dans le répertoire / usr / share / doc / abntex2 / pdf et
/ usr / share / doc / abntex2 / latex respectivement.

Source: https://code.google.com/p/abntex2/wiki/InstalacaoLinux

### Ubuntu 12.04 ou moins

Comme indiqué dans la page [installation de abnTeX2 sur les distributions GNU / Linux] (https://code.google.com/p/abntex2/wiki/InstalacaoLinux#Instala%C3%A7%C3%A3o_autom%C3%A1tica_do_TeX_Live_e_do_abnTe (recommandé)
, l'installation via apt-get ne fonctionne qu'avec Ubuntu version 12.10,
car c'est là que la version 2012 de Tex Live est disponible, qui est celle recommandée
à utiliser avec abnTeX2.

Pour installer abnTeX2 sur Ubuntu 12.04, il est au moins nécessaire de mettre à jour le
Tex Live. L'un des moyens possibles consiste à utiliser les packages existants dans le
[texlive-backports] référentiel (https://launchpad.net/~texlive-backports/+archive/ppa)
, conformément aux directives ci-dessous.

Ajoutez le référentiel texlive-backports en tapant ce qui suit dans un terminal:

$ sudo add-apt-repository ppa: texlive-backports / ppa

Si le package texlive pour Ubuntu 12.04 est déjà installé, tapez:

$ sudo apt-get mise à jour && sudo apt-get mise à jour

Si le package texlive Ubuntu 12.04 n'est pas encore installé, tapez:

$ sudo apt-get mise à jour && sudo apt-get install texlive

Une autre façon de mettre à jour Tex Live est manuellement, comme décrit sur la page
[installation d'abnTeX2 sur les distributions GNU / Linux] (https://code.google.com/p/abntex2/wiki/InstalacaoLinux#Instala%C3%A7%C3%A3o_manual_a_partir_do_instalador_do_TUG)

Source: https://code.google.com/p/abntex2/wiki/FAQ#Por_que_eu_não_consigo_instalar_o_abnTeX2_no_Ubuntu_12.04_via_a

### Autres distributions Linux

Informations pour installer abnTeX2 sur d'autres distributions Linux:

https://code.google.com/p/abntex2/wiki/InstalacaoLinux

### Les fenêtres

Informations pour installer abnTeX2 sous Windows:

https://code.google.com/p/abntex2/wiki/InstalacaoWindows

### Mac OS

Informations pour installer abnTeX2 sur Mac OS X:

https://code.google.com/p/abntex2/wiki/InstalacaoMac

## Compilation

Pour compiler le texte via le type Makefile:

$ rendre propre
$ faire
