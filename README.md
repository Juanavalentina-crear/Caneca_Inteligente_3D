# 🗑️♻️ Caneca Inteligente 3D

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![React](https://img.shields.io/badge/React-18.x-61DAFB?logo=react)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.x-38B2AC?logo=tailwind-css)
![License](https://img.shields.io/badge/License-MIT-green.svg)

**Sistema interactivo de clasificación automática de residuos con visualización 3D, inteligencia artificial y monitoreo en tiempo real.**

[Demo en Vivo](#) · [Reportar Bug](../../issues) · [Solicitar Función](../../issues)

</div>

---

## 📸 Vista Previa

<div align="center">
  <img src="https://via.placeholder.com/800x450/0f172a/3b82f6?text=Caneca+Inteligente+3D" alt="Vista previa del proyecto" />
  <p><i>Sistema de clasificación inteligente con vista 360° y análisis en tiempo real</i></p>
</div>

---

## ✨ Características Principales

### 🎮 Vista 3D Interactiva
- Caneca renderizada en Canvas HTML5
- Rotación 360° con arrastre del mouse
- Animaciones fluidas de tapa y compartimientos
- Efectos visuales y de iluminación realistas

### 🤖 Inteligencia Artificial
- Sistema de visión computacional
- Identificación automática de residuos
- Clasificación en tiempo real
- Retroalimentación visual instantánea

### 📊 6 Compartimientos Inteligentes
| Tipo | Icono | Descripción |
|------|-------|-------------|
| **Orgánico** | 🍎 | Residuos biodegradables |
| **Plástico** | 🥤 | Botellas, envases, bolsas |
| **Papel** | 📄 | Cartón, periódico, documentos |
| **Vidrio** | 🍾 | Botellas, frascos de vidrio |
| **Metal** | 🥫 | Latas, aluminios, metales |
| **No Aprovechables** | ❓ | Residuos no reciclables |

### 📡 Monitoreo en Tiempo Real
- Niveles de llenado por compartimiento
- Alertas automáticas (80%, 90%, 100%)
- Sistema de alarma sonora
- Historial completo de actividad

### 📈 Estadísticas y Análisis
- Gráfico circular de distribución
- Gráfico de barras de niveles actuales
- Panel de métricas del sistema
- Exportación de datos (próximamente)

---

## 🚀 Inicio Rápido

### Prerrequisitos

Asegúrate de tener instalado:
- [Node.js](https://nodejs.org/) (v14.0 o superior)
- npm (incluido con Node.js) o yarn

### Instalación

```bash
# 1. Clonar el repositorio
git clone https://github.com/TU_USUARIO/caneca-inteligente-3d.git

# 2. Navegar al directorio
cd caneca-inteligente-3d

# 3. Instalar dependencias
npm install

# 4. Iniciar servidor de desarrollo
npm start
```

La aplicación se abrirá automáticamente en [http://localhost:3000](http://localhost:3000)

### Build para Producción

```bash
npm run build
```

Los archivos optimizados estarán en la carpeta `build/`

---

## 📦 Dependencias

### Principales
```json
{
  "react": "^18.2.0",
  "react-dom": "^18.2.0",
  "lucide-react": "^0.263.1",
  "recharts": "^2.5.0"
}
```

### Desarrollo
```json
{
  "tailwindcss": "^3.3.0",
  "autoprefixer": "^10.4.14",
  "postcss": "^8.4.24"
}
```

---

## 🎮 Modo de Uso

### 1. **Rotar la Caneca**
Arrastra con el mouse sobre la vista 3D para rotar la caneca 360° y explorar todos los ángulos.

### 2. **Clasificar Residuos**
Haz clic en cualquiera de los 6 botones de tipo de residuo para simular la clasificación automática.

### 3. **Monitorear Niveles**
Observa las barras de progreso que muestran el llenado de cada compartimiento en tiempo real.

### 4. **Vaciar Compartimientos**
Cuando un compartimiento esté lleno o casi lleno, haz clic en el icono 📦 para vaciarlo.

### 5. **Revisar Historial**
Consulta los 3 paneles de historial:
- **Visión IA**: Actividad del escáner
- **Clasificación**: Residuos procesados
- **Monitoreo**: Cambios en niveles

### 6. **Analizar Estadísticas**
Revisa los gráficos para ver:
- Distribución total de residuos
- Niveles actuales por tipo
- Métricas del sistema

---

## 🏗️ Estructura del Proyecto

```
caneca-inteligente-3d/
├── public/
│   ├── index.html           # HTML principal
│   └── favicon.ico          # Icono de la app
├── src/
│   ├── App.jsx              # 🎯 Componente principal
│   ├── index.js             # Punto de entrada
│   ├── index.css            # Estilos globales + Tailwind
│   └── components/          # (para futuras expansiones)
├── .gitignore               # Archivos ignorados por Git
├── package.json             # Dependencias y scripts
├── tailwind.config.js       # Configuración de Tailwind
├── postcss.config.js        # Configuración de PostCSS
└── README.md                # 📖 Este archivo
```

---

## 🛠️ Tecnologías Utilizadas

<table>
  <tr>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="48" height="48" alt="React" />
      <br>React
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="48" height="48" alt="JavaScript" />
      <br>JavaScript
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="48" height="48" alt="HTML5" />
      <br>HTML5 Canvas
    </td>
    <td align="center" width="96">
      <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" width="48" height="48" alt="Tailwind" />
      <br>Tailwind CSS
    </td>
  </tr>
</table>

### Bibliotecas y APIs
- **Canvas API**: Renderizado 3D de la caneca
- **Web Audio API**: Sistema de alertas sonoras
- **Lucide React**: Iconos modernos y escalables
- **Recharts**: Gráficos interactivos

---

## 🎨 Personalización

### Cambiar Colores de Compartimientos

Edita el array `wasteTypes` en `src/App.jsx`:

```javascript
const wasteTypes = [
  { 
    id: 'organic', 
    name: 'Orgánico', 
    color: '#10b981',  // ← Cambia este color
    icon: '🍎', 
    category: 'organic' 
  },
  // ... más tipos
];
```

### Ajustar Umbrales de Alertas

Modifica los valores en la función `simulateScan`:

```javascript
if (newValue >= 100) {
  // Contenedor lleno
} else if (newValue > 80) {  // ← Cambia este valor
  addAlert('🟡 Casi lleno', 'warning');
}
```

### Modificar Velocidad de Escáner

Ajusta los `setTimeout` en `simulateScan`:

```javascript
setTimeout(() => {
  setIsScanning(false);
  // ...
}, 2000);  // ← Cambia este valor (milisegundos)
```

---

## 📱 Responsividad

El diseño está optimizado para múltiples dispositivos:

| Dispositivo | Resolución | Estado |
|-------------|------------|--------|
| Desktop 4K | 3840×2160 | ✅ Optimizado |
| Desktop HD | 1920×1080 | ✅ Optimizado |
| Laptop | 1366×768 | ✅ Optimizado |
| Tablet | 768×1024 | ✅ Optimizado |
| Mobile | 375×667 | ✅ Optimizado |

---

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Aquí está cómo puedes ayudar:

1. **Fork** el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m '✨ Add: nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un **Pull Request**

### Guía de Estilo para Commits

```
✨ Add: nueva funcionalidad
🐛 Fix: corrección de bug
💄 Style: cambios de estilo/UI
♻️ Refactor: refactorización de código
📝 Docs: actualización de documentación
🚀 Perf: mejora de rendimiento
✅ Test: añadir o actualizar tests
```

---

## 📋 Roadmap

### Versión 1.1 (En desarrollo)
- [ ] Modo multi-idioma (ES/EN)
- [ ] Tema claro/oscuro
- [ ] Exportación de reportes PDF
- [ ] Sistema de notificaciones push

### Versión 2.0 (Planeado)
- [ ] Integración con API real de reconocimiento de imágenes
- [ ] Modo multi-caneca para edificios
- [ ] Sistema de usuarios y autenticación
- [ ] Dashboard administrativo
- [ ] Aplicación móvil nativa (React Native)

### Versión 3.0 (Futuro)
- [ ] Integración con IoT para canecas físicas
- [ ] Machine Learning para mejorar clasificación
- [ ] Sistema de recompensas gamificado
- [ ] API REST para integración externa
- [ ] Blockchain para tracking de reciclaje

---

## 🐛 Problemas Conocidos

- En algunos navegadores antiguos, el Web Audio API puede no funcionar correctamente
- La rotación 3D puede tener menor rendimiento en dispositivos de gama baja
- Los gráficos pueden tardar en cargar con muchos datos

**Reporta bugs en:** [Issues](../../issues)

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

```
MIT License

Copyright (c) 2024 [Tu Nombre]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

## 👨‍💻 Autor

**[Tu Nombre]**

- 🌐 Website: [tupagina.com](https://tupagina.com)
- 🐙 GitHub: [@tu-usuario](https://github.com/tu-usuario)
- 💼 LinkedIn: [Tu Perfil](https://linkedin.com/in/tu-perfil)
- 📧 Email: tuemail@ejemplo.com
- 🐦 Twitter: [@tu_twitter](https://twitter.com/tu_twitter)

---

## 🙏 Agradecimientos

Este proyecto fue inspirado por:
- Iniciativas de ciudades inteligentes y sostenibles
- Tecnologías de clasificación automática de residuos
- Soluciones IoT para gestión ambiental

### Recursos Utilizados
- [Lucide Icons](https://lucide.dev/) - Iconos modernos
- [Recharts](https://recharts.org/) - Biblioteca de gráficos
- [Tailwind CSS](https://tailwindcss.com/) - Framework CSS
- [React](https://react.dev/) - Biblioteca de UI

---

## 📊 Estadísticas del Proyecto

![GitHub stars](https://img.shields.io/github/stars/TU_USUARIO/caneca-inteligente-3d?style=social)
![GitHub forks](https://img.shields.io/github/forks/TU_USUARIO/caneca-inteligente-3d?style=social)
![GitHub issues](https://img.shields.io/github/issues/TU_USUARIO/caneca-inteligente-3d)
![GitHub pull requests](https://img.shields.io/github/issues-pr/TU_USUARIO/caneca-inteligente-3d)

---

## 🌍 Impacto Ambiental

Este proyecto busca contribuir a:
- ♻️ Mejor clasificación de residuos
- 🌱 Reducción de contaminación
- 📊 Datos para políticas ambientales
- 🎓 Educación en reciclaje
- 🏙️ Ciudades más sostenibles

---

<div align="center">

**¿Te gustó el proyecto? ¡Dale una ⭐ en GitHub!**

Hecho con ❤️ y ♻️ para un mundo más sostenible

[⬆ Volver arriba](#-caneca-inteligente-3d)

</div>
