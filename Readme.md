# Gestor de Contenido de Marketing

Una herramienta todo-en-uno para la planificación, gestión y exportación de publicaciones de marketing, ideal para organizar campañas de manera eficiente.

## Funcionalidades Principales
- **Actualización de Contadores**:
  - Los totales y el progreso completado de historias, carruseles, videos y boxins se actualizan automáticamente en la interfaz.
- **Exportación a Excel**:
  - Genera un archivo Excel con los datos de la grilla, organizado por día, fecha, tipo de contenido, producto, descripción y estado de completado.
  - El archivo se guarda con un nombre dinámico basado en la fecha actual.
- **Persistencia de Datos**:
  - Guarda datos y configuración en `localStorage` para evitar pérdidas al recargar la página.
- **Interfaz Interactiva**:
  - Los usuarios pueden marcar tareas completadas directamente desde la grilla utilizando checkboxes.
  - Se muestran notificaciones para informar sobre el estado de las acciones (como la exportación exitosa).
- **Inicialización Inteligente**:
  - La aplicación intenta cargar datos previos desde `localStorage` al iniciar, proporcionando continuidad automática.

## Tecnologías Utilizadas
- **HTML5 y CSS3**: Para la estructura y diseño moderno.
- **JavaScript (Eventos y DOM)**: Gestión de interactividad, manipulación dinámica de datos y generación de elementos en tiempo real.
- **LocalStorage**: Persistencia de datos entre sesiones.
- **Librería XLSX**: Exportación de datos a Excel con un formato profesional y organizado.

## Cómo Usar
1. **Carga de Datos**:
   - Subir un archivo Excel desde la interfaz o cargar datos guardados en `localStorage`.
2. **Generación de Grilla**:
   - Selecciona una fecha inicial y presiona "Generar Grilla" para planificar los próximos 30 días.
3. **Progreso**:
   - Usa los checkboxes para marcar las tareas completadas.
4. **Exportación**:
   - Exporta la grilla completa a un archivo Excel, ideal para compartir o analizar.
5. **Recuperación Automática**:
   - La aplicación restaura datos y configuración automáticamente al iniciar.

## Créditos
Desarrollado por Nelson Pereira.