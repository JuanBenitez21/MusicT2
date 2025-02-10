# AudioPlayer

### Descripción del Problema:
En este problema, tienes un reproductor de audio (`AudioPlayer`) que puede reproducir archivos de audio de distintos tipos, como MP3. Sin embargo, se ha introducido una nueva clase avanzada (`AdvancedAudioPlayer`) que puede reproducir formatos más avanzados como MP4 y VLC. Necesitas proporcionar una solución que permita a la clase `AudioPlayer` reproducir archivos utilizando la funcionalidad avanzada de la clase `AdvancedAudioPlayer` sin cambiar el código existente del reproductor de audio.

### Solución Propuesta:
La solución propuesta es implementar un adaptador que permita que la interfaz `AudioPlayer` utilice la clase `AdvancedAudioPlayer` como si fuera un reproductor de audio normal.

### Estructura del Código:

El código consta de las siguientes clases:

#### `AudioPlayer` (Interfaz):
Define la interfaz básica para un reproductor de audio.

#### `AdvancedAudioPlayer` (Clase):
Proporciona funcionalidades avanzadas para reproducir archivos MP4 y VLC.

#### `AdvancedAudioPlayerAdapter` (Clase):
Actúa como un adaptador que permite que la interfaz `AudioPlayer` utilice la funcionalidad de `AdvancedAudioPlayer`.

#### `Client` (Clase):
Ejemplo de cómo utilizar la interfaz `AudioPlayer` con el adaptador.

<img width="955" alt="Captura de pantalla 2025-02-10 a la(s) 1 48 32 p  m" src="https://github.com/user-attachments/assets/260220bf-8fbf-42e5-9c8e-135abfb93d82" />

