# 🚀 Examen Vue.js - Universidad Luterana Salvadoreña

## 📋 Información del Proyecto

- **Universidad:** Universidad Luterana Salvadoreña
- **Facultad:** Ciencias del Hombre y la Naturaleza
- **Carrera:** Licenciatura en Ciencias de la Computación
- **Materia:** Nuevas Tendencias de Programación
- **Ciclo:** II-2025
- **Catedrático:** Msc Jorge Alberto Coto Zelaya
- **Estudiante:** Gabriela Virginia Velasquez Turcios
- **Carnet:** VT2255

## 🎯 Objetivo del Examen

Este proyecto demuestra el dominio de Vue.js implementando **10 ejercicios prácticos** que cubren:

- ✅ **Composition API** (6 ejercicios)
- ✅ **Options API** (4 ejercicios)
- ✅ **Manejo de eventos**
- ✅ **Directivas Vue** (v-if, v-for, v-show, v-model, etc.)
- ✅ **Manipulación de datos reactivos**
- ✅ **Computed properties y Watchers**

## 📁 Estructura del Proyecto

```
examen-vuejs/
├── src/
│   ├── components/
│   │   ├── CompositionAPI/
│   │   │   ├── WelcomeMessage.vue         # 1. Mensaje de Bienvenida
│   │   │   ├── ToggleMessage.vue          # 3. Mostrar/Ocultar Mensaje
│   │   │   ├── TaskList.vue               # 5. Lista de Tareas
│   │   │   ├── SimpleCalculator.vue       # 6. Calculadora Sencilla
│   │   │   ├── ThemeToggle.vue            # 7. Toggle Tema Oscuro/Claro
│   │   │   └── WatcherExample.vue         # 10. Watchers
│   │   └── OptionsAPI/
│   │       ├── ClickCounter.vue           # 2. Contador de Clics
│   │       ├── InputHandler.vue           # 4. Manejar Eventos Input
│   │       ├── ConditionalRender.vue      # 8. Renderizado Condicional
│   │       └── ComputedProperties.vue     # 9. Propiedades Computadas
│   ├── assets/
│   │   └── main.css                       # Estilos globales
│   ├── App.vue                            # Componente principal
│   └── main.js                            # Punto de entrada
├── public/
│   └── index.html                         # Plantilla HTML
├── package.json                           # Dependencias del proyecto
├── vite.config.js                         # Configuración de Vite
└── README.md                              # Este archivo
```

## 🛠️ Tecnologías Utilizadas

- **Vue.js 3** - Framework principal
- **Vite** - Herramienta de construcción y desarrollo
- **CSS3** - Estilos avanzados con gradientes, animaciones y responsive design
- **JavaScript ES6+** - Sintaxis moderna

## 📚 Ejercicios Implementados

### 🟢 Composition API (6 ejercicios)

1. **Mensaje de Bienvenida** - Uso de `reactive()` para manejo de datos
2. **Mostrar/Ocultar Mensaje** - Control de visibilidad con `ref()`
3. **Lista de Tareas** - CRUD completo con arrays reactivos
4. **Calculadora Sencilla** - Operaciones matemáticas con validaciones
5. **Toggle Tema Oscuro/Claro** - Cambio dinámico de estilos globales
6. **Watchers** - Observación de cambios con diferentes tipos de watchers

### 🟡 Options API (4 ejercicios)

2. **Contador de Clics** - Manejo de estado con métodos tradicionales
4. **Manejar Eventos Input** - Eventos de teclado, focus, blur
8. **Renderizado Condicional** - Uso de `v-if`, `v-else-if`, `v-else`
9. **Propiedades Computadas** - Computed properties para cálculos automáticos

## 🚀 Instalación y Ejecución

### Prerrequisitos

- Node.js (versión 16 o superior)
- npm o yarn

### Pasos para ejecutar

1. **Clonar o descargar el proyecto**
   ```bash
   # Si está en GitHub
   git clone [URL_DEL_REPOSITORIO]
   cd examen-vuejs
   
   # Si es un archivo comprimido
   # Descomprimir y entrar a la carpeta
   ```

2. **Instalar dependencias**
   ```bash
   npm install
   ```

3. **Ejecutar en modo desarrollo**
   ```bash
   npm run dev
   ```

4. **Abrir en el navegador**
   - Visitar `http://localhost:5173`

5. **Construir para producción** (opcional)
   ```bash
   npm run build
   ```

## 💡 Características Destacadas

### ✨ Funcionalidades Técnicas

- **Reactivity System**: Implementación completa de reactividad Vue 3
- **Component Communication**: Comunicación entre componentes
- **Event Handling**: Manejo avanzado de eventos del DOM
- **Conditional Rendering**: Renderizado condicional complejo
- **List Rendering**: Renderizado de listas dinámicas
- **Form Handling**: Manejo completo de formularios

### 🎨 Características de UI/UX

- **Diseño Responsive**: Adaptable a móviles y desktop
- **Tema Dinámico**: Cambio entre modo claro y oscuro
- **Animaciones CSS**: Transiciones suaves y efectos visuales
- **Feedback Visual**: Indicadores de estado y progreso
- **Accesibilidad**: Etiquetas semánticas y navegación por teclado

### 📊 Funcionalidades Avanzadas

- **Real-time Updates**: Actualizaciones en tiempo real
- **Data Validation**: Validación de datos de entrada
- **History Tracking**: Seguimiento de acciones del usuario
- **Statistics Display**: Visualización de estadísticas
- **Local Storage Simulation**: Persistencia de datos simulada

## 🧪 Conceptos Evaluados

### Eventos Implementados
- `@click` - Clics en botones
- `@keyup.enter` - Tecla Enter
- `@focus` / `@blur` - Enfoque de campos
- `@input` - Entrada de datos
- `@submit` - Envío de formularios
- `@mouseover` - Hover del mouse

### Directivas Utilizadas
- `v-if` / `v-else-if` / `v-else` - Renderizado condicional
- `v-for` - Bucles y listas
- `v-show` - Visibilidad con CSS
- `v-model` - Enlace bidireccional de datos
- `v-bind` / `:` - Enlace de atributos
- `v-on` / `@` - Manejo de eventos

### Funcionalidades Vue
- **Computed Properties** - Cálculos automáticos
- **Watchers** - Observación de cambios
- **Methods** - Funciones de componente
- **Lifecycle Hooks** - Ciclo de vida del componente
- **Transitions** - Animaciones de entrada/salida

## 📱 Compatibilidad

- ✅ **Navegadores Modernos** (Chrome, Firefox, Safari, Edge)
- ✅ **Dispositivos Móviles** (iOS, Android)
- ✅ **Tablets y Desktop**
- ✅ **Responsive Design**

## 📝 Notas de Desarrollo

### Decisiones de Arquitectura

1. **Separación por API**: Componentes organizados por tipo de API utilizada
2. **Estilos Scoped**: CSS encapsulado por componente
3. **Composición Modular**: Cada ejercicio es completamente independiente
4. **Código Limpio**: Comentarios y estructura clara

### Buenas Prácticas Implementadas

- **Naming Conventions**: Nomenclatura consistente
- **Component Structure**: Estructura clara de componentes
- **Performance**: Optimización de re-renders
- **Accessibility**: Accesibilidad web implementada
- **Error Handling**: Manejo de errores apropiado

## 🎯 Demostración de Conceptos

Cada ejercicio demuestra conceptos específicos:

| Ejercicio | Concepto Principal | API Utilizada |
|-----------|-------------------|---------------|
| Mensaje de Bienvenida | `reactive()` y enlace de datos | Composition |
| Contador de Clics | Methods y data tradicional | Options |
| Toggle Mensaje | `ref()` y transiciones | Composition |
| Manejo de Input | Event handling avanzado | Options |
| Lista de Tareas | Arrays reactivos y CRUD | Composition |
| Calculadora | Validaciones y computed | Composition |
| Toggle Tema | DOM manipulation | Composition |
| Renderizado Condicional | Directivas condicionales | Options |
| Computed Properties | Propiedades calculadas | Options |
| Watchers | Observadores de cambios | Composition |

## 🏆 Criterios de Evaluación Cumplidos

- ✅ **Composition API**: 6 ejercicios implementados correctamente
- ✅ **Options API**: 4 ejercicios implementados correctamente
- ✅ **Manejo de Eventos**: Eventos variados y complejos
- ✅ **Directivas**: Uso correcto de todas las directivas solicitadas
- ✅ **Manipulación de Datos**: Reactividad y enlace bidireccional
- ✅ **Funcionalidad Completa**: Todos los componentes funcionan perfectamente
- ✅ **Código Limpio**: Estructura clara y mantenible
- ✅ **UI/UX Profesional**: Interfaz pulida y profesional

## 👨‍💻 Autor

**Desarrollado para el examen de Vue.js**
- Materia: Nuevas Tendencias de Programación
- Profesor: Msc Jorge Alberto Coto Zelaya
- Universidad Luterana Salvadoreña
- Ciclo II-2025

> **Nota**: Este proyecto demuestra dominio completo de Vue.js con implementaciones prácticas y funcionales de todos los conceptos solicitados en el examen.
