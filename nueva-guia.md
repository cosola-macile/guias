#Preparando Máquinas

## 1. Instalar chocolatey

* Navegar a http://chocolaty.org/install
* Abrir powerShell como administrador. Entra:

	```sh
	Set-ExecutionPolicy Bypass
	# Aceptar los requisitos utilizando Y
	```

- Copiar command text (No copiar el comentario)

	```
	...

	```

- Verificar que todo se ha instalado correctamente usando

	```
	choco --version
	```

## 2. Instalar nodejs

	Descargar nodejs
	Abrir y cerrar el powerShell
	Verificar que todo esta instalado correctamente
	node --version
	npm --version
	

## 3. Desde choco instalamos yarn

	
	choco install yarn -f (-f instala todos los defaults)
	Verificamos que todo esta instalado
	yarn --version
	
## 4. Instalar gulp


	npm install gulp -g 

## 5. Instalar servidor local


	npm install http-server -g
