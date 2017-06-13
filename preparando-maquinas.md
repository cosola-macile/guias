# Preparando Máquinas

Esta preparación es para las máquinas de windows.

## 1. Instalar chocolatey

* Navegar a http://chocolaty.org/install
* Abrir powerShell como administrador. Entra:

```sh
Set-ExecutionPolicy Bypass
# Aceptar los requisitos utilizando Y
```

- Copiar command text (No copiar el comentario)

```sh
# Don't forget to ensure ExecutionPolicy above
iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

```

- Verificar que choco se ha instalado correctamente

```sh
choco --version
```

## 2. Visita [el sitio web de node](https://nodejs.org/en/download/current/) y descarga la versión más reciente `8.1.0`

## 3. Verifica que todo esta instalado correctamente	
	
Abre y cierra la linea de comando, después de haber instalado node
	
```sh
node --version
# Debe ver la version 8.1.0
npm --version
# Debe ver la version 5.0.3
```
	
## 4. Desde choco instalamos yarn

```sh
choco install yarn -y # -y instala todos los defaults
# Verificamos que todo esta instalado
yarn --version
# Debemos ver la version 0.24.6
```

## 5. Instala gulp

```sh
npm install gulp -g 
```
