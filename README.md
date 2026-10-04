# 🎵 Musant — El Ritmo de tus Emociones

![Musant Banner](https://via.placeholder.com/1200x400/121212/8A2BE2?text=MUSANT+%E2%80%94+Sinestesia+y+M%C3%BAsica+en+Streaming)

## 📌 Resumen General del Proyecto

**Musant** es una plataforma de música en streaming de nueva generación diseñada sobre los conceptos de **sinestesia e Inteligencia Artificial**. A diferencia de los reproductores tradicionales basados únicamente en géneros musicales, Musant organiza, visualiza y recomienda contenido mediante un sistema de **firmas cromáticas** que vincula frecuencias sonoras, ritmos y estados de ánimo con una paleta visual vibrante y de alto contraste (**Morado, Negro, Blanco, Rojo, Verde y Amarillo**).

---

## 🎨 Identidad Visual y Paleta Cromática

La interfaz utiliza un modo oscuro mate predeterminado (`#121212`) para ahorrar batería y reducir la fatiga visual, destacando acentos en neón:

| Color | Hex | Estado de Ánimo / Espectro Musical |
| :--- | :--- | :--- |
| **Negro (Base)** | `#121212` | Fondo mate y ahorro energético |
| **Blanco (Texto)** | `#FFFFFF` | Tipografía principal y máxima legibilidad |
| **Morado (Insignia)** | `#8A2BE2` | Logo, R&B, Dream Pop, Synthwave e introspección |
| **Rojo (Adrenalina)** | `#FF0055` | Trap, Metal, Techno, Rock y alta energía |
| **Verde (Calma)** | `#00FF66` | Lo-Fi, Acústico, Ambient y concentración |
| **Amarillo (Euforia)** | `#FFCC00` | Pop, Disco, Reggaeton, Fiesta y tendencias |

---

## 🚀 Funcionalidades Clave

* **🔮 Sinestesia A.I. & Chroma Wheel:** Control gestual circular que permite arrastrar el pulgar entre colores para fusionar estilos musicales en tiempo real (ej. Morado + Amarillo = *R&B Bailable*).
* **📷 Modo Camaleón (Lente Musant):** Escaneo mediante la cámara del móvil para extraer la paleta de colores de cualquier entorno (un atardecer, ropa, arte) y generar una playlist que suena como se ve la imagen.
* **🖼️ Live Canvas Player & RGB Smart Home:** Visualizador en 3D con halo de luz dinámico que se sincroniza con sistemas de iluminación inteligentes (Philips Hue, Govee) al ritmo de la música.
* **🌐 Social Color-Pulse:** Mapa interactivo donde los perfiles de tus amigos brillan con el color del estado de ánimo musical que escuchan en directo.

---

## 📁 Arquitectura del Código Fuente

```text
musant-app/
├── README.md
├── .gitignore
├── src/
│   ├── assets/
│   │   └── theme/             # Colores oficiales (#8A2BE2, #FF0055, etc.)
│   ├── components/
│   │   ├── ChromaWheel.jsx    # Rueda cromática gestual de navegación
│   │   └── Player.jsx         # Reproductor a pantalla completa
│   ├── screens/
│   │   ├── HomeScreen.jsx     # Inicio por estados de ánimo
│   │   └── CameleonScreen.jsx # Captura y procesamiento con la cámara
│   ├── services/
│   │   ├── aiService.js       # Extracción de colores de imagen
│   │   └── audioService.js    # Motor de reproducción e hibridación
│   └── utils/
│       └── colorAlgorithms.js # Algoritmo de conversión BPM a color
