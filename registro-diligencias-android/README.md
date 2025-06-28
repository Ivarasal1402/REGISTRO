# Registro de Diligencias OAPCN

## Descripción
Aplicación web progresiva (PWA) para el registro de diligencias asignadas a conductores de la Oficina de Apoyo a la Sección de Cumplimiento a Nivel Nacional.

## Características

### ✨ Funcionalidades Principales
- **Registro de Diligencias**: Formulario completo para registrar información de viajes
- **Gestión de Datos**: Almacenamiento local de registros con persistencia
- **Generación de Documentos**: Exportación de registros en formato de texto
- **Vista Previa**: Visualización del documento antes de la descarga
- **Validación de Datos**: Verificación automática de campos obligatorios

### 📱 Características PWA
- **Instalable**: Se puede instalar como aplicación nativa en Android
- **Offline**: Funciona sin conexión a internet
- **Responsive**: Diseño adaptativo para móviles y escritorio
- **Service Worker**: Cache inteligente para mejor rendimiento

### 🎨 Diseño Moderno
- **Tailwind CSS**: Framework de utilidades para estilos
- **Shadcn/UI**: Componentes de interfaz profesionales
- **Lucide Icons**: Iconografía moderna y consistente
- **Gradientes**: Diseño visual atractivo con colores institucionales

## Instalación en Android

### Método 1: Desde el Navegador
1. Abrir la aplicación en Chrome o Edge en Android
2. Tocar el menú (⋮) del navegador
3. Seleccionar "Agregar a pantalla de inicio" o "Instalar aplicación"
4. Confirmar la instalación

### Método 2: Banner de Instalación
1. Al visitar la aplicación, aparecerá automáticamente un banner
2. Tocar "Instalar" en el banner
3. La aplicación se agregará a la pantalla de inicio

## Estructura del Proyecto

```
registro-diligencias/
├── public/
│   ├── manifest.json          # Configuración PWA
│   ├── sw.js                  # Service Worker
│   ├── icon-192.png          # Icono 192x192
│   └── icon-512.png          # Icono 512x512
├── src/
│   ├── components/ui/        # Componentes de interfaz
│   ├── App.jsx              # Componente principal
│   ├── App.css              # Estilos globales
│   └── main.jsx             # Punto de entrada
├── dist/                    # Archivos de producción
└── README.md               # Este archivo
```

## Tecnologías Utilizadas

- **React 18**: Framework de JavaScript
- **Vite**: Herramienta de construcción
- **Tailwind CSS**: Framework de CSS
- **Shadcn/UI**: Biblioteca de componentes
- **Lucide React**: Iconos
- **PWA**: Progressive Web App

## Comandos de Desarrollo

```bash
# Instalar dependencias
npm install

# Servidor de desarrollo
npm run dev

# Construir para producción
npm run build

# Vista previa de producción
npm run preview
```

## Uso de la Aplicación

### 1. Datos del Conductor
- Ingresar el nombre completo del conductor
- Agregar observaciones generales si es necesario

### 2. Registro de Diligencia
- **Fecha**: Seleccionar la fecha del viaje
- **Hora de Salida**: Hora de inicio del viaje
- **Km Salida**: Kilometraje inicial del vehículo
- **Destino**: Lugar de destino del viaje
- **Hora Llegada**: Hora de finalización del viaje
- **Km Llegada**: Kilometraje final del vehículo
- **Funcionario**: Nombre del funcionario transportado

### 3. Gestión de Registros
- Los registros se guardan automáticamente en el dispositivo
- Se pueden eliminar registros individuales
- Vista previa del documento antes de descargar
- Descarga en formato de texto plano

## Características de Seguridad

- **Almacenamiento Local**: Los datos se guardan solo en el dispositivo
- **Sin Servidor**: No se envían datos a servidores externos
- **Privacidad**: Información completamente privada y local

## Compatibilidad

- **Android**: 5.0+ (API 21+)
- **Navegadores**: Chrome 67+, Firefox 68+, Safari 11.1+
- **iOS**: 11.3+ (con limitaciones de PWA)

## Soporte

Para soporte técnico o reportar problemas, contactar al departamento de sistemas de OAPCN.

---

**Versión**: 1.0.0  
**Última actualización**: Junio 2025  
**Desarrollado para**: Oficina de Apoyo a la Sección de Cumplimiento a Nivel Nacional

