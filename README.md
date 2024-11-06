<div align="center">
    <a href="https://www.acceseo.com">
        <img
            alt="acceseo logo"
            src="logo-acceseo.svg"
            width="150">
    </a>
</div>

<h1 align="center">🐛 Configuración de Xdebug para Visual Studio Code</h1>

<div align="center">
    <a href="https://github.com/acceseo/xdebug-config-for-vscode/tree/main/README.en.md">English version</a> | <a href="https://github.com/acceseo/PHP-WebApp-Docker-Compose">acceseo/PHP-WebApp-Docker-Compose</a> | <a href="https://xdebug.org/">Xdebug</a>
</div>

<hr>

Configura automáticamente la extensión [PHP Debug](https://marketplace.visualstudio.com/items?itemName=xdebug.php-debug) de Visual Studio Code en proyectos basados en [acceseo/PHP-WebApp-Docker-Compose](https://github.com/acceseo/PHP-WebApp-Docker-Compose).

## 🧰 Versiones de Xdebug soportadas
* 2.*
* 3.*

## 🤖 Configuración automática de la última versión
```shell
curl --create-dirs -o ./.vscode/launch.json https://raw.githubusercontent.com/acceseo/xdebug-config-for-vscode/main/xdebug-3/.vscode/launch.json
```

## 🔨 Configuración manual de cualquier versión
Copia la carpeta `.vscode` que hay en la carpeta correspondiente a la versión deseada en la raíz de tu proyecto.

## 👷 Créditos
* Creado por [acceseo](https://acceseo.com)
