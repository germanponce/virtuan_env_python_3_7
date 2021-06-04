# Entorno Virtual Python 3.7

"""
Para instalar librerias debemos hacer lo siguiente:

sudo directorio/bin/pip3.7 install libreria

En caso de Error probar:

directorio/bin/python3.7 directorio/bin/pip3.7 install imaplib

Debemos instalar previamente:

Edit the source list sudo nano /etc/apt/sources.list to add the following line: 

deb http://security.ubuntu.com/ubuntu xenial-security main

Then sudo apt update and sudo apt install libssl1.0.0.


Si el Pip o Python3.7 te da un error indicando una ruta como:
/opt/odoo14/python/pip3 no such file interpreter

Esto se debe a que los binarios compilados como pip, python3.7 tienen en la cabecera la ruta original del compilado.

Para ello editamos los archivos de la carpeta bin como pip3.7:

nano /path/odoo/python/bin/pip3.7

Agregamos, por ejemplo la nueva rura de Odoo:
#!/opt/odoo/python/bin/python3.7


"""
