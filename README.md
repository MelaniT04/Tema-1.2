# Tema 1.2 Melani Toapanta: Entorno portable de Dart y Flutter

## Características del Equipo
* **Procesador:** AMD Ryzen 7 8840HS w/ Radeon 780M Graphics      (3.30 GHz)
* **Memoria RAM:** 16.0 GB (13.8 GB utilizable)
* **Tarjeta Gráfica:**  Radeon 780M Graphics (2 GB)
* **Almacenamiento:** 477 GB SSD
* **Sistema Operativo:** Windows 11 de 64 bits

## Entorno de Desarrollo
* **Versión de Flutter y Dart:** Flutter 3.x / Dart 3.x (obtenidas mediante `flutter --version`)
* **Ruta del Entorno:** `C:\dev\flutter\bin` (configurada en la variable de entorno PATH)
* **Destinos Disponibles:** Windows (desktop), Google Chrome (web)

## Problema Resuelto
Lo que sucedió al presionar F5 fue lo siguiente, el programa se ejecuta en la consola de depuración, solo permite leer y no permite escribir ya que bloquea la entrada del teclado. El problema se resolvio creando el archivo `.vscode/launch.json` con la propiedad `"console": "terminal"`, lo que redirige la ejecución a una terminal interactiva real.