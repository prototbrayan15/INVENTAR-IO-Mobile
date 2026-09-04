# INVENTAR-IO Mobile

Aplicación móvil desarrollada para facilitar la gestión y consulta de productos en pequeños negocios y tiendas de barrio.

El proyecto hace parte de la evidencia **GA8-220501096-AA2-EV02 – APK (desarrollar módulos móviles según requerimientos del proyecto)** del programa de **Tecnólogo en Análisis y Desarrollo de Software del SENA**.

## Descripción del proyecto

INVENTAR-IO es una aplicación móvil orientada a la administración básica de inventario. Permite registrar productos y mantener organizada la información relacionada con ellos desde un dispositivo Android.

La aplicación fue desarrollada teniendo en cuenta los requerimientos definidos para el proyecto y buscando una interfaz sencilla, clara y fácil de utilizar.

## Funcionalidades principales

* Registro de usuarios.
* Inicio de sesión.
* Visualización de productos registrados.
* Registro de nuevos productos.
* Edición de productos.
* Eliminación de productos.
* Búsqueda de productos por nombre o categoría.
* Consulta de información del inventario.
* Generación y consulta de reportes.
* Navegación mediante un menú principal.

## Tecnologías utilizadas

* Java
* Android Studio
* Android SDK
* XML para las interfaces.
* RecyclerView para la visualización de productos.
* Git y GitHub para el control de versiones.

## Organización del proyecto

El código fuente se encuentra organizado en paquetes de acuerdo con la función de cada componente:

* `activities`: contiene las actividades y pantallas principales de la aplicación.
* `adapter`: contiene el adaptador utilizado para mostrar los productos.
* `model`: contiene las clases que representan los datos del sistema.
* `repository`: contiene la gestión de la información utilizada por la aplicación.
* `service`: contiene la lógica relacionada con los servicios y reportes.
* `utils`: contiene clases auxiliares, validaciones y constantes.

## Módulos desarrollados

### Autenticación

Permite registrar usuarios e iniciar sesión mediante las credenciales correspondientes.

### Gestión de productos

Permite agregar, consultar, editar y eliminar productos del inventario.

### Búsqueda

Permite localizar productos utilizando el nombre o la categoría.

### Reportes

Permite consultar información relacionada con los productos y el inventario.

### Información

Contiene información general relacionada con la aplicación.

## Arquitectura

El proyecto se encuentra organizado por componentes y paquetes, separando las actividades de presentación, los modelos, el adaptador de productos, el repositorio y las clases auxiliares.

Esta organización permite mantener el código más ordenado y facilita el mantenimiento de los diferentes módulos de la aplicación.

## Pruebas realizadas

Durante el desarrollo se realizaron pruebas de funcionamiento de los principales módulos:

* Registro de usuario.
* Inicio de sesión.
* Validación de credenciales.
* Registro de productos.
* Edición de productos.
* Eliminación de productos.
* Consulta del inventario.
* Búsqueda de productos.
* Navegación entre las diferentes pantallas.

Las pruebas se realizaron utilizando el emulador de Android Studio.

## Ambiente de desarrollo

**IDE:** Android Studio
**Plataforma:** Android
**Lenguaje:** Java
**Interfaz:** XML
**Dispositivo de prueba:** Emulador Pixel 6
**SDK utilizado:** Android SDK

## Control de versiones

El proyecto utiliza **Git** para el control de versiones y **GitHub** como repositorio remoto, permitiendo conservar el código fuente y realizar seguimiento de los cambios realizados durante el desarrollo.

## Integrantes

**Brayan Stiven Palacios Reyes**

**Daniel Santiago Paredes Daza**

## Evidencia

Proyecto desarrollado para la evidencia:

**GA8-220501096-AA2-EV02 – APK (desarrollar módulos móviles según requerimientos del proyecto).**

## Estado del proyecto

Proyecto funcional en ambiente de prueba, con los módulos principales de gestión de inventario implementados y probados en Android Studio.
