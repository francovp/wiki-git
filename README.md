# Guía de introducción

Si usted es un recién nacido o un viejo sabio de la tierra media, esta Guía de introducción utiliza un flujo de trabajo básico para proporcionar una visión general de la interfaz de GitKraken desde la clonación de su repositorio hasta la ejecución exitosa de acciones de Git.

## Instalación

Los pasos escenciales incluyen:

1.  Instalar GitKraken
2.  Crearse una cuenta y la configuración de su perfil

Una vez completado esto, usted está listo para su aventura.

## Proyectos en GitKraken

Hay tres formas de iniciar un repositorio Git cuando se trabaja en un proyecto:

1. **Open **- Abrir un repositorio Git local, que ya está iniciado y está disponible localmente.
2. **Clon** - clonar un repositorio Git remoto que ya está iniciado.
3. **Init** - Crear un repositorio Git vacío o reinicializar uno ya existente.

## Abrir un proyecto existente

GitKraken le permite cargar sus repositorios existentes y continuar donde lo dejó. También es útil para visualizar el trabajo pasado realizado.

Si usted está viniendo de un proyecto Git ya tiene a nivel local, vaya a File -&gt; Open Repo para empezar de inmediato con GitKraken.

![](https://gitlab.com/innervycslabs/wiki-innervycs/uploads/02e840698b676a96eb2fda27de6ad71d/image.png)

## Clonar un proyecto existente

Si el proyecto no está en su equipo local o si desea una copia nueva, clone el proyecto a través File -&gt; Clone

![](https://gitlab.com/innervycslabs/wiki-innervycs/uploads/43700cc639bbfcf1a8b6ac26d9d597ac/image.png)

A continuación, le pedirá que abra el proyecto que acaba de copiar en GitKraken.

## Iniciar un nuevo proyecto

Empezar un proyecto en GitKraken es muy fácil, se hace a través de File -&gt; Init.

![](https://gitlab.com/innervycslabs/wiki-innervycs/uploads/071538f88d5581f83a213097b8f40b1c/image.png)

Todo lo que necesita hacer es llenar los campos y seleccionar Crear repositorio para que la magia ocurra.

#### Entrada:

* Nueva ruta de repositorio
* Plantilla .gitignore \(opcional\)
  * GitKraken trae incluido plantillas de archivos .gitignore que se pueden seleccionar al inicializar y crean automáticamente un archivo .gitignore en su copia de trabajo \(working copy\).

  * Al iniciar un proyecto con un lenguaje o un framework específico como base, puede ser preferible seleccionar el .gitignore relacionado. Esto creará entradas comunes de archivos para no ser rastreados en Git. Siempre se pueden añadir o eliminar entradas, y crear exclusiones modificando el archivo directamente.
* Licencia \(opcional\)

  * Para obtener más información, echa un vistazo a la Iniciativa Open Source  o averiguar más acerca de Escoger una licencia.

  * GitKraken también permite seleccionar una licencia para el trabajo que va a hacer. Si el proyecto es privado no es necesario seleccionar un valor aquí, pero si quieres que el proyecto sea abierto al público tendría que considerar que lo sea en virtud de sus términos deseados. Al inicializar, GitKraken creará un archivo LICENSE en su repositorio.

#### Salida:

* Un nuevo proyecto Git inicializado en la ruta del repositorio especificado, además agregando una carpeta .git. Todo lo demás se llamará su directorio de trabajo \(working directory\).
* Se abre el proyecto.
* Un "Initial commit" en una rama master que contiene un archivo README.md en blanco junto con un .gitignorey LICENSE.md si procede.

**tl;dr** haz completado el " Hello World " de Git el cual le llevó a hacer su primer commit en solo un par de clicks!

El proceso para la consecución de este primer commit se describe adicionalmente en la sección** Flujo de trabajo.**

> **GitKraken también permite inicializar un repositorio directamente en un proveedor de alojamiento Git remoto como GitHub y Bitbucket.**

Al inicializar un repositorio para un proveedor de alojamiento remoto, hay opciones adicionales disponibles como una descripción y nivel de acceso. El repositorio se creará en el proveedor remoto y puede ser clonado inmediatamente.

