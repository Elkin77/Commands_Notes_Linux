# Commands_Notes_Linux

Comandos instalación python + django

* sudo apt-get install python

* sudo apt-get install pip

* sudo apt-get install python-setuptools

*sudo pip install virtualenv
	
	* virtualenv .
		* python -m venv nombre1
	* source bin/active	
	* pip install django
	* django-admin.py --version
	* python -m pip freeze

iniciar proyecto en django
	*django-admin.py startproject app1
	


instalación de postgresql 

	* sudo apt-get install postgresql postgresql-contrib
		* su - postgres
			* postgres
				*\password postgres

	* sudo apt install pgadmin3
	* pip install psycopg2


sublime text

----- BEGIN LICENSE -----
sgbteam
Single User License
EA7E-1153259
8891CBB9 F1513E4F 1A3405C1 A865D53F
115F202E 7B91AB2D 0D2A40ED 352B269B
76E84F0B CD69BFC7 59F2DFEF E267328F
215652A3 E88F9D8F 4C38E3BA 5B2DAAE4
969624E7 DC9CD4D5 717FB40C 1B9738CF
20B3C4F1 E917B5B3 87C38D9C ACCE7DD8
5F7EF854 86B9743C FADC04AA FB0DA5C0
F913BE58 42FEA319 F954EFDD AE881E0B
------ END LICENSE ------



apt

Install the GPG key:

wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -

Ensure apt is set up to work with https sources:

sudo apt-get install apt-transport-https

Select the channel to use:

Stable

    echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list

Dev

    echo "deb https://download.sublimetext.com/ apt/dev/" | sudo tee /etc/apt/sources.list.d/sublime-text.list

Update apt sources and install Sublime Text

sudo apt-get update
sudo apt-get install sublime-text


-------------------------

    ls -l.
    ls -F.
    ls -laC.
    rm fichero.
    rm -rf directorio.
    cp fichero /home/datos/
    mv fichero /home/datos/
    cat archivo.


python---

listas
append ("maria") -> agregar
insert (2, "maria") -> insertar
extend(["Sandra","Ana"]) - > concatenar otra lista.
print(miLista.index("Ana")) ->indice
print("pepe" in miLista) - > in, si el elemento se encuentra en la lista.
miLista.remove("Ana") - > elimina elemento en una lista
miLista.pop() -> elimina ultimo elemento de la lista
miLista3 = miLista1 + miLista2 -> Une las listas
miLista3 =["elemento1", "elemento2"]*3 -> replica listas

tuplas
miLista = List(mitupla) - > convertir tupla en lista
mitupla = tuple(milista) - convertir lista en tupla.
