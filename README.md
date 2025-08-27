# 🌌 Rick and Morty Location Explorer

Una aplicación web interactiva desarrollada con React que permite explorar las ubicaciones del multiverso de Rick and Morty. Descubre dimensiones, planetas y lugares únicos mientras navegas por los residentes que habitan cada ubicación.

## 🌟 Características

- **🎲 Carga aleatoria** de ubicaciones al iniciar la aplicación
- **🔍 Búsqueda por ID** de ubicación específica
- **📍 Información detallada** de cada ubicación (tipo, dimensión, población)
- **👥 Lista de residentes** con información completa de cada personaje
- **🖼️ Lazy loading** de imágenes para optimizar el rendimiento
- **📱 Diseño responsivo** que se adapta a diferentes dispositivos
- **⚡ Interfaz rápida** con estados de carga elegantes
- **🎨 UI moderna** inspirada en el universo de Rick and Morty

## 🚀 Demo en Vivo

🔗 **[https://00005-rick-morty-location-explorer.netlify.app/](https://00005-rick-morty-location-explorer.netlify.app/)**

## 🛠️ Tecnologías Utilizadas

- **React 17** - Biblioteca de JavaScript para interfaces de usuario
- **Axios** - Cliente HTTP para consumo de APIs
- **React Lazy Load** - Carga perezosa de imágenes
- **CSS3** - Estilos y animaciones personalizadas
- **Rick and Morty API** - Fuente de datos oficial

## 📁 Estructura del Proyecto

```
rick-morty-location-explorer/
├── public/
│   ├── favicon.jpg           # Icono de la aplicación
│   └── index.html           # Plantilla HTML principal
├── src/
│   ├── components/
│   │   ├── LocationInfo.js   # Información de ubicación
│   │   ├── ResidentInfo.js   # Tarjeta de residente
│   │   ├── ResindentsList.js # Lista de residentes
│   │   └── SearchBox.js      # Barra de búsqueda
│   ├── images/
│   │   ├── image.svg         # Recursos gráficos
│   │   └── titleIntro.svg    # Logo de Rick and Morty
│   ├── App.js               # Componente principal
│   ├── index.css            # Estilos globales
│   ├── loader.css           # Animaciones de carga
│   └── index.js             # Punto de entrada
├── package.json             # Dependencias del proyecto
└── README.md               # Documentación
```

## 🎨 Características de la Interfaz

### Pantalla Principal
- Logo oficial de Rick and Morty
- Barra de búsqueda intuitiva con placeholder descriptivo
- Carga automática de una ubicación aleatoria al inicio
- Loader animado durante las peticiones a la API

### Información de Ubicación
- **Nombre** de la ubicación destacado
- **Tipo** de lugar (Planeta, Dimensión, Estación Espacial, etc.)
- **Dimensión** de origen
- **Población** calculada automáticamente

### Lista de Residentes
- **Imágenes** de alta calidad con lazy loading
- **Información detallada** de cada personaje:
  - Nombre completo
  - Estado vital y especie
  - Lugar de origen
  - Número de episodios en los que aparece

## 🚀 Instalación y Uso

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/FROSTYLAN/rick-morty-location-explorer.git
   ```

2. **Navega al directorio:**
   ```bash
   cd rick-morty-location-explorer
   ```

3. **Instala las dependencias:**
   ```bash
   npm install
   ```

4. **Inicia el servidor de desarrollo:**
   ```bash
   npm start
   ```

5. **Abre tu navegador en:**
   ```
   http://localhost:3000
   ```

## 📱 Responsividad

La aplicación está optimizada para:
- 💻 **Desktop** - Experiencia completa con grid de residentes
- 📱 **Mobile** - Diseño adaptativo con navegación táctil
- 📟 **Tablet** - Layout intermedio optimizado

## 🎯 Funcionalidades Principales

### Exploración Aleatoria
- Al cargar la aplicación, se muestra una ubicación aleatoria
- Perfecto para descubrir nuevos lugares del multiverso

### Búsqueda Dirigida
- Busca ubicaciones específicas por su ID (1-126)
- Validación de entrada y manejo de errores

### Información Completa
- Datos detallados de cada ubicación
- Lista completa de todos los residentes
- Información rica de cada personaje

## 🔧 Scripts Disponibles

### `npm start`
Inicia la aplicación en modo desarrollo.\
Abre [http://localhost:3000](http://localhost:3000) para verla en el navegador.

### `npm test`
Lanza el corredor de pruebas en modo interactivo.

### `npm run build`
Construye la aplicación para producción en la carpeta `build`.\
Optimiza la construcción para el mejor rendimiento.

### `npm run eject`
**Nota: esta es una operación irreversible.**\
Si no estás satisfecho con las herramientas de construcción, puedes hacer "eject".

## 🌐 API Utilizada

Este proyecto consume la [Rick and Morty API](https://rickandmortyapi.com/):
- **Endpoint de ubicaciones:** `https://rickandmortyapi.com/api/location/{id}`
- **Endpoint de personajes:** `https://rickandmortyapi.com/api/character/{id}`
- **Rango de ubicaciones:** 1-126 ubicaciones disponibles

## 🔧 Posibles Mejoras

- [ ] Implementar búsqueda por nombre de ubicación
- [ ] Añadir filtros por tipo de ubicación y dimensión
- [ ] Crear sistema de favoritos
- [ ] Implementar paginación para ubicaciones
- [ ] Añadir modo oscuro
- [ ] Integrar información de episodios
- [ ] Crear rutas para navegación avanzada
- [ ] Añadir animaciones de transición

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 👨‍💻 Autor

**Charles Castillo (FROSTYLAN)**
- GitHub: [@FROSTYLAN](https://github.com/FROSTYLAN)
- LinkedIn: [Charles Castillo](https://linkedin.com/in/charles-castillo-772968234)

---

⭐ ¡No olvides dar una estrella al proyecto si te gustó!

🚀 **¡Explora el multiverso de Rick and Morty!** 🛸
