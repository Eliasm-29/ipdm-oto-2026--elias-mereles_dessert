# Dessert Clicker App

Trabajo práctico de la materia **Dispositivos Móviles** — IPDM Otoño 2026.

**Alumno:** Elias Mereles

## Descripción

Dessert Clicker es una app Android en la que cada vez que el usuario toca la imagen del postre, se "compra" ese postre: se suma al contador de ingresos y de postres vendidos, y cambia la imagen mostrada por un postre distinto.

## Temas aplicados

- **Ciclo de vida de la Activity**: se agregaron logs (`Log.d`) en cada callback del ciclo de vida (`onCreate`, `onStart`, `onResume`, `onPause`, `onStop`, `onRestart`, `onDestroy`) para observar en Logcat cuándo se dispara cada uno.
- **Cambios de configuración**: uso de `rememberSaveable` para conservar el estado de la app (ingresos, cantidad de postres vendidos) cuando ocurre un cambio de configuración, como rotar la pantalla.

## Ejercicio de referencia

- Ruta de aprendizaje: [Componentes de la Arquitectura](https://developer.android.com/courses/pathways/android-basics-compose-unit-4-pathway-1?hl=es-419)
- Codelab: Stages of the Activity lifecycle

## Cómo ejecutar

1. Abrir el proyecto en Android Studio.
2. Esperar a que sincronice Gradle.
3. Ejecutar en un emulador o dispositivo Android.
4. Ver los logs del ciclo de vida en la ventana **Logcat**, filtrando por el tag correspondiente.
