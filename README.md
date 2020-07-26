# Angular web service

## Instalando angular

Para poder usar el proyecto se necesita el CLI de angular, los pasos para instalarlo son los siguientes:

- Instalar [node](https://nodejs.org/es/) 

- Con [npm](https://www.npmjs.com/) instalar el [CLI de angular](https://github.com/angular/angular-cli).

```bash
npm install -g @angular/cli
```

- De forma opcional se puede instalar [git](https://git-scm.com/) para clonar el repositorio directamente.

```bash
git clone https://github.com/jlozoya/angular-web-service.git
```

- Despues hay que instalar las dependencias del proyecto.

```bash
npm install
```

En los proyectos de node las librerías se van agregando en el archivo package.json, se agregan de forma automática cuando usas `--save` al realizar la descarga, por ejemplo `npm install bootstrap@4.0.0-beta.2 --save`.

El último paso es ejecutar el proyecto para verificar que todo está en orden, para lo que hay dos opciones.

```bash
ng serve
```

```bash
ng build
```

Cuando compilas el proyecto, pero no lo quieres mover de la carpeta donde se genera a la raíz o lo vas a colocar en una carpeta diferente puedes usar el siguiente comando:

```bash
ng build --base-href /angular-web-service/dist/ --prod
```

# Angular CLI

Este proyecto se generó con [Angular CLI](https://github.com/angular/angular-cli) versión 1.3.2.

## Servidor de desarrollo

Ejecute `ng serve` para un servidor dev. Navegue hasta `http://localhost:4200/`. La aplicación se volverá a cargar automáticamente si cambia alguno de los archivos de codigo fuente.

O `ng serve --port 8000 -o` en caso de que el puerto este ocupado.

## Andamios de código

Ejecutar `ng generate component component-name` para generar un nuevo componente. También puedes usar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Construción

Ejecutar `ng build` para construir el proyecto. Los artefactos de compilación se almacenarán en el directorio `dist/`. Utilice el indicador `-prod` para una compilación de producción.

Para construir el proyecto y no moverlo de la carpeta donde se genera se esta usando el siguiente comando `ng build --base-href /angular-web-service/dist/ --prod`.

## Ejecución de pruebas unitarias

Ejecutar `ng test` corre las pruebas unitarias con [Karma](https://karma-runner.github.io).

## Ejecución de pruebas de extremo a extremo

Ejecutar `ng e2e` corre las pruebas de extremo a extremo a través de [Protractor] (http://www.protractortest.org/). Antes de ejecutar las pruebas asegúrese de que está sirviendo la aplicación a través de `ng serve`.

## Ayuda futura

Para obtener más ayuda sobre la CLI angular, utilice `ng help` o visite el [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Librerías instaladas

```node
npm install --save popper ngx-popper
npm install jquery --save
npm install --save-dev @types/jquery
npm install tether --save
npm install bootstrap@4.0.0-beta.2 --save
npm install ngx-pagination --save
npm install node-sass sass-loader raw-loader --save-dev
```
