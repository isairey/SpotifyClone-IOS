<div align="center">

<img width="220" src="https://upload.wikimedia.org/wikipedia/commons/8/84/Spotify_icon.svg" />

# 🎵 SpotifyClone iOS

### Clon moderno de Spotify desarrollado en SwiftUI para iPhone 🚀

<p align="center">
  <b>SpotifyClone iOS</b> es una aplicación inspirada visualmente en Spotify que consume la API oficial de Spotify para mostrar canciones, playlists, podcasts, artistas y álbumes con una interfaz moderna desarrollada en SwiftUI.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/iOS-SwiftUI-orange?style=for-the-badge&logo=swift">
  <img src="https://img.shields.io/badge/Spotify-Web%20API-1DB954?style=for-the-badge&logo=spotify">
  <img src="https://img.shields.io/badge/Music-Streaming-black?style=for-the-badge">
  <img src="https://img.shields.io/badge/Open%20Source-iPhone%20App-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-preview">Preview</a> •
  <a href="#-características">Características</a> •
  <a href="#-spotify-api">Spotify API</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a>
</p>

</div>

---

# 🌌 Acerca de SpotifyClone iOS

**SpotifyClone iOS** es una aplicación multimedia creada para replicar la experiencia visual y funcional de Spotify en dispositivos iPhone utilizando SwiftUI y la API oficial de Spotify.

La aplicación permite:

- 🎵 Explorar canciones
- 🎧 Escuchar previews de tracks
- 🔎 Buscar artistas y álbumes
- 📚 Navegar playlists
- 🎤 Explorar podcasts
- ❤️ Descubrir contenido musical
- 📱 Disfrutar una UI moderna estilo Spotify

El proyecto fue desarrollado como práctica de:

- iOS Development
- SwiftUI
- REST APIs
- Arquitectura MVVM
- Streaming Apps
- Gestión multimedia
- UI/UX moderna

---

# 📸 Preview

<div align="center">

<img src="https://user-images.githubusercontent.com/62707916/136813393-a3dcc218-d800-4556-aa58-11b0019fd89b.png" width="220"/>

<img src="https://user-images.githubusercontent.com/62707916/136813456-e010e92f-2465-4f59-94a3-ecbe4bab71cf.png" width="220"/>

<img src="https://user-images.githubusercontent.com/62707916/136813590-cbb9dd10-3798-45ac-990c-8f6ace31b36e.png" width="220"/>

<img src="https://user-images.githubusercontent.com/62707916/136813659-5b816b8b-bcdb-4320-a166-6b203cb8ff0b.png" width="220"/>

</div>

---

# ✨ Características

# 🎵 Streaming y Música

- ▶️ Reproducción de previews
- 🎧 Streaming musical
- ⚡ Audio instantáneo
- 🎶 Navegación multimedia
- 📱 Experiencia estilo Spotify

---

## 🔎 Exploración Musical

- 🎤 Buscar artistas
- 🎵 Buscar canciones
- 💿 Explorar álbumes
- 🎧 Podcasts integrados
- 📚 Playlists dinámicas

---

## 📱 Interfaz Moderna

- ✨ SwiftUI moderno
- 🌙 Dark UI inspirada en Spotify
- ⚡ Navegación fluida
- 🎨 Diseño responsive
- 🎵 Componentes animados

---

## 🎛️ Reproductor Multimedia

- ⏯️ Play / Pause
- 📜 Barra de progreso
- 🔊 Controles multimedia
- 🎶 Información del track
- 🎧 Preview de 30 segundos

---

# 🌐 Spotify API

## ⚡ Integración Oficial

La aplicación consume la:

- Spotify Web API
- Spotify iOS SDK
- REST Endpoints
- OAuth Authentication

---

## 🔐 Autenticación

- Login Spotify
- Client ID / Secret
- OAuth flow
- Token handling
- Session management

---

# 🛠️ Tecnologías Utilizadas

## 📱 Desarrollo iOS

<p>
  <img src="https://skillicons.dev/icons?i=swift" />
</p>

- Swift
- SwiftUI
- AVFoundation
- Combine
- CocoaPods

---

## ⚙️ Librerías y Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github" />
</p>

### Dependencias principales

- Alamofire
- SwiftLint
- Introspect
- Spotify iOS SDK

---

# 📂 Estructura del Proyecto

```bash
SpotifyClone/
│
├── Views/                   # Interfaces SwiftUI
├── ViewModels/              # Arquitectura MVVM
├── Services/                # Consumo de APIs
├── Models/                  # Modelos de datos
├── Components/              # Componentes reutilizables
├── Assets/                  # Recursos gráficos
├── SpotifyCloneApp.swift
└── README.md
```

---

# ⚡ Instalación

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/usuario/SpotifyClone
```

---

## 2️⃣ Abrir proyecto en Xcode

```bash
SpotifyClone.xcodeproj
```

---

## 3️⃣ Configurar Spotify Developer

Crear aplicación en:

```bash
https://developer.spotify.com
```

---

## 4️⃣ Configurar credenciales

Editar:

```bash
YourSensitiveData.swift
```

Agregar:

```swift
CLIENT_ID
CLIENT_SECRET
```

---

## 5️⃣ Configurar Redirect URI

Ejemplo:

```txt
https://www.github.com
```

Debe coincidir con:

```swift
AuthViewModel.swift
```

---

## 6️⃣ Ejecutar aplicación

```bash
Run ▶
```

---

# 🔥 Funcionalidades Técnicas

## 🎧 Sistema Multimedia

- AVFoundation
- Audio previews
- Playback controls
- Audio session management
- Media streaming

---

## ⚡ Arquitectura MVVM

- ViewModels separados
- Dependency Injection
- State management
- Clean architecture
- Modular structure

---

## 🌐 Consumo REST API

- Spotify REST API
- JSON parsing
- Authentication flow
- Data caching
- Async networking

---

# 📦 Pantallas Incluidas

## 📱 Interfaces principales

- 🏠 Home Screen
- 🔎 Search Screen
- 🎵 Track Details
- 📚 Playlist Details
- 🎤 Artist Details
- 🎧 Podcast Details
- 💿 Album Details

---

# 🧠 Objetivos del Proyecto

## 🎯 Aprender y practicar

- SwiftUI
- REST APIs
- OAuth Authentication
- Arquitectura MVVM
- Multimedia iOS
- Spotify SDK
- UI/UX moderna
- Gestión de memoria

---

# 📊 Roadmap

## 🚧 Próximamente

- ❤️ Favoritos reales
- 🎵 Reproducción completa
- 📚 Queue system
- 🔥 Más animaciones
- ☁️ Persistencia de sesión
- 🎧 Equalizer visual
- 📱 Mejor navegación
- 🚀 Optimización de rendimiento

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Haz Fork del proyecto
2. Crea una rama

```bash
git checkout -b feature/nueva-funcion
```

3. Realiza cambios
4. Haz commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

5. Haz push

```bash
git push origin feature/nueva-funcion
```

6. Abre un Pull Request 🚀

---

# 👨‍💻 Autor

<div align="center">

## Gabriel

iOS Developer apasionado por SwiftUI, aplicaciones multimedia y experiencias modernas inspiradas en Spotify.

</div>

---

# 🌟 Apoya el Proyecto

Si te gusta SpotifyClone iOS:

⭐ Dale una estrella al repositorio  
🍴 Haz Fork del proyecto  
📢 Compártelo con otros desarrolladores

---

# 📜 Licencia

Proyecto Open Source desarrollado con fines educativos y práctica de desarrollo iOS.

---

<div align="center">

### 🎵 SpotifyClone iOS — Experiencia Spotify moderna desarrollada en SwiftUI.

</div>
