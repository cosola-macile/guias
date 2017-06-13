# Preparando Máquinas

## 1. Instalar chocolatey

* Navegar a http://chocolaty.org/install
* Abrir powerShell como administrador. Entra:

	```sh
	Set-ExecutionPolicy Bypass
	# Aceptar los requisitos utilizando Y
	```

- Copiar command text (No copiar el comentario)

	```
	# Don't forget to ensure ExecutionPolicy above
	iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

	```

- Verificar que choco se ha instalado correctamente

	```
	choco --version
	```

## 2. Visitar el sitio web de node y descargar la versión más reciente 8.1.0
	
	https://nodejs.org/en/download/current/

## 3. Verificar que todo esta instalado correctamente	
	
Abrir y cerrar la linea de comando, despues de haber instalado node
	
```
node --version
# Debe ver la version 8.1.0
npm --version
# Debe ver la version 5.0.3
```
	
## 4. Desde choco instalamos yarn

	
	choco install yarn -f (-f instala todos los defaults)
	Verificamos que todo esta instalado
	yarn --version
	
## 4. Instalar gulp


	npm install gulp -g 

## 5. Instalar servidor local


	npm install http-server -g
