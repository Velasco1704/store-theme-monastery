# Store Theme Monastery

## Que es Store Theme Monastery

El **Store Theme Monastery** es una réplica con fines prácticos del comercio electrónico [Monastery](https://monasterycouture.com.co/). Este proyecto tiene como objetivo principal facilitar el aprendizaje sobre VTEX IO.

## Instalación

### 1. Clonar repositorio

Copia el [repositorio](https://github.com/Velasco1704/store-theme-monastery) del proyecto y clonarlo en en tu terminal.

```bash
git clone https://github.com/Velasco1704/store-theme-monastery
```

### 2. Acceder a la Carpeta del Proyecto

Después de clonar el repositorio, entra a la carpeta del proyecto utilizando el siguiente comando:

```bash
cd store-theme-monastery
```

### 3. Iniciar Sesión en VTEX

Para poder trabajar con VTEX, necesitas iniciar sesión con tu cuenta. Utiliza el siguiente comando y reemplaza {account} con tu nombre de cuenta de VTEX:

```bash
vtex login { account }
```

### 4. Seleccionar el Espacio de Trabajo

Una vez que hayas iniciado sesión, selecciona el espacio de trabajo en el que deseas trabajar utilizando el siguiente comando. Reemplaza {workspace} con el nombre de tu espacio de trabajo:

```bash
vtex use { workspace }
```

### 5. Enlazar el Proyecto al Espacio de Trabajo

Finalmente, enlaza el proyecto a tu espacio de trabajo para visualizarlo ejecutando el siguiente comando:

```bash
vtex link
```

## Descripción general del proyecto

Después de haber clonado el proyecto encontraras varias carpetas y cada una con un propósito:

### Store

La carpeta **store** es el corazón del proyecto, en ella se encuentra la carpeta de **blocks** y el archivo de **routes.json**:

- **Blocks**: Aquí reside toda la aplicación, organizada en varias carpetas para mantener un orden óptimo en cuanto a la estructura responsive de la aplicación.
- **Routes**: En este archivo se configura todas las rutas custom de la app.

### Assets

La carpeta **assets** es la encargada de almacenar todas la imágenes y fuentes.

### Styles

La carpeta **styles** se conforma de 3 subcarpetas y estas son **config**, **css** y **iconspacks**:

- **Config**: Es la encargada de la configuración general de los estilos de la app como fuentes y variables.
- **Css**: Lleva todo el css de la app subdividido en varias carpetas como la carpeta **blocks**.
- **Iconspacks**: Se encarga de almacenar todos los iconos de la app.
