# Vue Counter & Parent-Child Communication

Este proyecto es una aplicación Vue.js que demuestra conceptos fundamentales como el manejo de estado con Vuex, navegación con Vue Router y comunicación entre componentes.

## 🌐 Demo en vivo

La aplicación está desplegada en Firebase:
[https://vue-counter-parent-2024.web.app](https://vue-counter-parent-2024.web.app)

## 🚀 Características

1. **Contador con Vuex**
   - Manejo de estado global
   - Incremento y decremento de contador
   - Pruebas unitarias del estado

2. **Navegación con Vue Router**
   - Múltiples vistas
   - Navegación fluida entre componentes
   - Rutas configuradas y probadas

3. **Comunicación Parent-Child**
   - Componente padre e hijo
   - Paso de mensajes entre componentes
   - Pruebas de comunicación

## 🛠️ Tecnologías Utilizadas

- Vue.js 3
- Vuex 4
- Vue Router 4
- Jest (Pruebas Unitarias)
- Firebase Hosting

## 📋 Prerrequisitos

- Node.js (v14 o superior)
- npm (v6 o superior)

## 🔧 Instalación

1. Clonar el repositorio:
```bash
git clone [URL-del-repositorio]
```

2. Instalar dependencias:
```bash
npm install
```

3. Ejecutar en desarrollo:
```bash
npm run serve
```

## 🧪 Pruebas

Ejecutar pruebas unitarias:
```bash
npm run test:unit
```
![Captura de pantalla 2024-12-01 014144](https://github.com/user-attachments/assets/288bf099-27c7-428d-a3eb-905875b07ba8)

## 📦 Construcción

Para construir el proyecto:
```bash
npm run build
```

## 📝 Scripts Disponibles

- `npm run serve`: Inicia servidor de desarrollo
- `npm run build`: Construye para producción
- `npm run test:unit`: Ejecuta pruebas unitarias
- `npm run lint`: Ejecuta el linter

## 🔍 Estructura del Proyecto

```
src/
  ├── components/
  │   ├── Counter/
  │   │   └── Counter.vue
  │   ├── Parent/
  │   │   └── Parent.vue
  │   └── Child/
  │       └── Child.vue
  ├── store/
  │   └── index.js
  ├── router/
  │   └── index.js
  ├── App.vue
  └── main.js
```

## 🤝 Contribuir

1. Fork el proyecto
2. Crea tu rama de característica (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para detalles
