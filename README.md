# Gallery App - Ionic Angular

Esta es una aplicación móvil desarrollada con **Ionic Angular** que permite a los usuarios tomar o seleccionar una imagen, añadir una descripción y almacenarla junto con la fecha de creación. La aplicación también muestra las imágenes en una lista y refleja estos datos en un widget nativo de Android, actualizado automáticamente cada 5 segundos.

## Características

- **Captura de imágenes**: Permite tomar una foto con la cámara del dispositivo o seleccionar una imagen desde la galería.
- **Descripción de imágenes**: Los usuarios pueden añadir una descripción a la imagen antes de guardarla.
- **Almacenamiento en Firebase**: Las descripciones y fechas se guardan en Firestore de Firebase.
- **Almacenamiento de imágenes en Supabase**: Las imágenes se suben a Supabase Storage y su URL se guarda en Firestore.
- **Listar imágenes**: Las imágenes almacenadas se muestran en una lista, junto con su descripción y fecha de creación.
- **Widget nativo en Android**: Un widget nativo en Android muestra las imágenes y descripciones, y se actualiza automáticamente cada 5 segundos.

## Tecnologías utilizadas

- **Ionic Framework** (Angular)
- **Firebase Firestore** (para almacenar descripciones y fechas)
- **Supabase** (para almacenar imágenes)
- **Capacitor Camera** (para tomar o seleccionar imágenes)
- **Capacitor Preferences** (para compartir datos entre la aplicación y el widget)
- **Android Studio** (para crear el widget nativo de Android)

## Requisitos

Para ejecutar el proyecto en tu entorno local, necesitas tener instalados los siguientes programas:

- **Node.js**: [Instalar Node.js](https://nodejs.org/)
- **Ionic CLI**: [Instalar Ionic CLI](https://ionicframework.com/docs/cli)
- **Android Studio** (para el desarrollo del widget nativo)

## Instalación

Sigue estos pasos para ejecutar el proyecto en tu máquina local:

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tu_usuario/galeria-app.git
   cd galeria-app
