# Kotlin Concepts

Aplicación Android desarrollada en Kotlin para practicar conceptos de interfaz, navegación, cálculo y gestión básica de listas. El proyecto está estructurado como una "colección de mini apps" accesibles desde un menú principal.

## Descripción general

La app inicia en una pantalla principal con varios botones que llevan a diferentes funcionalidades:

- Saludo / primer ejemplo de navegación entre actividades
- Calculadora de IMC
- App de tareas (ToDo)
- Pantalla de Super Héroes (estructura inicial / en desarrollo)

La intención del proyecto es servir como práctica de Android con Kotlin, usando actividades, intents, RecyclerView, Material Components y diseño con XML.

## Funcionalidades actuales

### 1. Menú principal

La actividad principal permite acceder a cada mini proyecto desde una única pantalla.

### 2. Primera app de saludo

- El usuario escribe su nombre.
- Se envía el texto mediante Intent a otra Activity.
- Se muestra un mensaje de bienvenida: "Hola <nombre>".

### 3. Calculadora corporal / IMC

- Permite seleccionar género masculino o femenino.
- Ajusta peso y edad con botones + y -.
- Calcula el Índice de Masa Corporal usando la fórmula:

  IMC = peso / altura²

- Muestra el resultado en una nueva pantalla.

### 4. ToDo app

- Muestra categorías: Personal, Negocios y Otros.
- Permite filtrar tareas según la categoría seleccionada.
- Añade tareas mediante un diálogo.
- Gestiona tareas en un RecyclerView.
- La selección de tareas y categorías actualiza la visualización en tiempo real.

### 5. Super Hero app

- Existe la activity base y la estructura de la pantalla.
- Actualmente está incompleta o en etapa inicial de desarrollo.

## Tecnologías usadas

- Kotlin
- Android SDK
- AndroidX
- AppCompat
- Material Components
- RecyclerView
- CardView
- ViewCompat / WindowInsets para manejo de barras del sistema

## Estructura del proyecto

```text
Kotlin-Comcepts/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── AndroidManifest.xml
│   │   │   ├── java/
│   │   │   │   └── com/thouma/concepts/
│   │   │   │       ├── menu/
│   │   │   │       │   ├── MenuActivity.kt
│   │   │   │       │   ├── firstApp/
│   │   │   │       │   ├── bodycalculator/
│   │   │   │       │   ├── todoApp/
│   │   │   │       │   └── superheoapp/
│   │   │   └── res/
│   │   │       ├── layout/
│   │   │       ├── drawable/
│   │   │       └── values/
│   └── build.gradle.kts
├── build.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
├── settings.gradle.kts
├── gradle/
└── README.md
```

## Requisitos

- Android Studio
- JDK 8+
- Gradle wrapper incluido en el proyecto
- Emulador o dispositivo Android físico

## Cómo ejecutar el proyecto

1. Clona el repositorio:

```bash
git clone https://github.com/richard-allcca/Kotlin-Comcepts.git
```

1. Abre la carpeta en Android Studio.

2. Espera a que Gradle sincronice las dependencias.

3. Selecciona un dispositivo/emulador.

4. Ejecuta la aplicación con el botón Run.

## Comandos útiles

```bash
./gradlew clean
./gradlew build
./gradlew assembleDebug
```

## Estado del proyecto

Este repositorio funciona como proyecto de aprendizaje y práctica de conceptos Android con Kotlin. Algunas partes están más desarrolladas que otras, y la sección de Super Héroes aún requiere continuidad.

## Autor

Richard / Thouma

## Tutorial

<https://www.youtube.com/watch?v=vJapzH_46a8&list=PL8ie04dqq7_M8nfPA9DPiAy7NsoZQpVAf>
