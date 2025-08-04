
# Incendio Radar Web

![Incendio Radar Logo](assets/logoo.png)

Flutter Web · OpenStreetMap · NASA FIRMS API · Responsive · Modern UI

Incendio Radar Web es una aplicación interactiva para visualizar incendios activos y sus huellas en España y Europa, usando datos en tiempo real de la NASA. Construida con Flutter Web para ofrecer una experiencia rápida, moderna y multiplataforma.

## 📱 Descripción

La app permite:
- Visualizar focos de incendios en un mapa interactivo.
- Consultar detalles de cada incendio (fecha, brillo, FRP, etc).
- Ver las huellas (áreas afectadas) como polígonos en el mapa.
- Filtrar por región y rango de días.
- Interfaz adaptativa para móvil y escritorio.

## 🏗️ Estructura del Proyecto

```
IncendioRadarWeb/
├── assets/                # Imágenes y recursos
│   └── logoo.png          # Logo principal
├── build/web/             # Archivos generados para despliegue web
├── lib/
│   ├── config/            # Configuración y claves
│   ├── models/            # Modelos de datos
│   ├── screens/           # Pantallas principales
│   ├── services/          # Lógica de negocio y API
│   ├── widgets/           # Componentes UI reutilizables
│   └── main.dart          # Punto de entrada
├── web/
│   └── index.html         # Configuración web y favicon
├── pubspec.yaml           # Dependencias y configuración Flutter
└── README.md              # Documentación del proyecto
```

## ⚙️ Instalación y Desarrollo

Clona el repositorio:
```sh
git clone https://github.com/juulsdev/IncendioRadarWeb.git
cd IncendioRadarWeb
```
Instala dependencias:
```sh
flutter pub get
```
Levanta el servidor de desarrollo:
```sh
flutter run -d chrome
```

## 🚀 Despliegue Web

El contenido de `build/web` puede subirse directamente a GitHub Pages, Vercel, Netlify o cualquier hosting estático.

## 🔥 Funcionalidades
- Mapa interactivo con OpenStreetMap y Flutter Map
- Visualización de incendios y huellas en tiempo real
- Detalles de cada incendio al hacer clic
- Responsive: funciona en móvil y escritorio

## 🤝 Contribución
1. Haz fork del repositorio.
2. Crea una rama de trabajo:
   ```sh
   git checkout -b feature/nueva-funcionalidad
   ```
3. Realiza tus cambios y haz commit.
4. Abre un Pull Request describiendo tus mejoras.

---
IncendioRadar – Julia Herrera
