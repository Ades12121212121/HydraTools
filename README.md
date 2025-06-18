# HydraTools - Información Completa

## Descripción General
HydraTools es una herramienta profesional de línea de comandos diseñada para anonimización avanzada de sistemas, spoofing de IDs y operaciones stealth. Construida con criptografía de vanguardia y técnicas anti-detección, proporciona herramientas integrales para protección de privacidad y anonimización de sistemas.

## Características Principales

### Criptografía Avanzada
- **XChaCha20 Encryption**: Protección criptográfica avanzada de 256-bit
- **Generación Segura de Claves**: Generación criptográficamente segura de números aleatorios
- **Gestión de Claves**: Sistemas avanzados de generación y gestión de claves

### Anti-Detección y Stealth
- **Anti-Debug Multi-Capa**: Detección avanzada de debuggers y análisis forense
- **Modo Desarrollo**: Opción para desactivar anti-debug durante desarrollo
- **Stealth Mode**: Operaciones silenciosas sin logs del sistema
- **Anonimización Completa**: Modificación de identificadores del sistema

### Integración Tor
- **Descarga Automática**: Descarga e instalación automática de Tor Browser
- **Configuración de Proxy**: Configuración automática del proxy del sistema
- **Servicio Tor**: Inicio automático del servicio Tor en segundo plano
- **Redirección de Tráfico**: Todo el tráfico redirigido a través de la red Tor

### Browser Fingerprint Spoofing
- **Canvas Fingerprinting**: Generación de huellas digitales únicas para canvas
- **Audio Fingerprinting**: Spoofing de huellas de audio del navegador
- **System Fingerprinting**: Modificación de información del sistema
- **Scripts Automáticos**: Generación automática de scripts de spoofing

### Procesamiento por Lotes
- **Configuración por Archivos**: Ejecución de múltiples operaciones desde archivos de configuración
- **Operaciones Secuenciales**: Procesamiento ordenado de tareas
- **Logs Detallados**: Registro completo de todas las operaciones
- **Manejo de Errores**: Gestión robusta de errores durante el procesamiento

## Programas Soportados

### IDEs y Editores
- **Cursor IDE**: Reset completo con HWID y telemetría
- **Visual Studio Code**: Operaciones stealth avanzadas
- **Windsurf IDE**: Anonimización completa

### Software de Diseño
- **Adobe Photoshop**: Reset completo con eliminación de servicios y carpetas

### Software de Seguridad
- **Malwarebytes Premium**: Reset avanzado con generación de MachineGuid

### Software de Entretenimiento
- **Spotify**: Instalación y eliminación de AdBlock

## Características Avanzadas

### UI/UX Mejorada
- **Banners Aleatorios**: 4 banners diferentes que se muestran aleatoriamente
- **Gradientes de Color**: Sistema de colores con gradientes profesionales
- **Efectos Visuales**: Múltiples efectos de caja (gradiente, zebra, neon, sombra, doble, pixel)
- **Emojis y Símbolos**: Interfaz visual rica con emojis y símbolos

### Funciones de Sistema
- **Limpieza de Logs**: Eliminación de logs de eventos de Windows
- **Limpieza de Prefetch**: Eliminación de archivos de prefetch
- **Limpieza de Temp**: Limpieza de archivos temporales
- **Limpieza de Navegador**: Eliminación de datos del navegador
- **Modificación de Tiempo**: Alteración del tiempo del sistema
- **Spoofing de Información**: Modificación de información del sistema

### Funciones Específicas por Programa
- **Cambio de HWID**: Modificación de Hardware ID para cada programa
- **Modificación de Telemetría**: Alteración de datos de telemetría en archivos JSON
- **Limpieza de Cache**: Eliminación de cache y logs específicos
- **Modificación de Timestamps**: Imitación de timestamps de archivos del sistema

## Plataformas Soportadas

### Windows
- **Estado**: ✅ Completamente funcional
- **Características**: Todas las características implementadas
- **Requisitos**: Windows 10/11, privilegios de administrador
- **Compilación**: Visual Studio 2019+ o MinGW

### Linux
- **Estado**: ✅ Completamente funcional
- **Características**: Todas las características implementadas
- **Requisitos**: Ubuntu 18.04+, CentOS 7+, privilegios de root
- **Dependencias**: libssl-dev, libcrypto-dev, libcurl4-openssl-dev, libjson-c-dev, uuid-dev

### macOS
- **Estado**: 🔄 Próximamente
- **Características**: En desarrollo
- **Requisitos**: macOS 10.15+
- **Dependencias**: OpenSSL, curl, json-c, util-linux

## Estructura de Archivos

### Windows
- `hydratools-windows.exe`: Ejecutable compilado

### Linux
- `hydratools-linux`: Ejecutable compilado

### macOS
- `hydratools_mac.c`: Código fuente principal (en desarrollo)

## Comandos Disponibles

### Comandos Básicos
- `help`: Muestra el menú de ayuda
- `programs`: Lista programas soportados
- `clear`: Limpia la consola
- `exit/quit`: Sale del programa

### Comandos de Reset
- `reset <prog>`: Reset específico de programa (cursor, vscode, windsurf)
- `hwid <prog>`: Cambia Hardware ID para programa específico
- `json <prog>`: Modifica datos de telemetría en archivos JSON
- `all <prog>`: Reset completo con proxy y configuración

### Comandos de Sistema
- `mac`: Cambia dirección MAC
- `anonymize`: Anonimización completa del sistema
- `tor`: Descarga y configura red Tor
- `fingerprint`: Spoofing de huella digital del navegador

### Comandos Específicos
- `photoshop`: Reset de Adobe Photoshop
- `malwarebytes`: Reset de Malwarebytes Premium
- `spotify`: Instala Spotify AdBlock
- `spotify-reset`: Elimina Spotify AdBlock

### Comandos Avanzados
- `batch <file>`: Ejecuta operaciones por lotes desde archivo de configuración

## Instalación y Uso

### Windows
1. Descargar el ejecutable compilado
2. Ejecutar como administrador
3. Usar comandos según necesidades

### Linux
1. Descargar archivos fuente
2. Ejecutar: `sudo ./hydratools-linux`

### macOS
1. Descargar archivos fuente (cuando esté disponible)
2. Ejecutar: `sudo ./hydratools-mac`

## Notas Importantes

### Distribución
- Solo se distribuyen ejecutables compilados
- No se incluye código fuente en releases
- Código fuente disponible en repositorio privado

### Seguridad
- Requiere privilegios de administrador/root
- Usar VPN para máxima anonimización
- Reiniciar sistema después de cambios importantes
- Considerar uso de máquinas virtuales

### Limitaciones
- Algunas funciones requieren reinicio del sistema
- Compatibilidad limitada con WSL en Windows
- Dependencias específicas por plataforma
- Funciones de red requieren conexión a internet

## Características Técnicas

### Criptografía
- **Algoritmo**: XChaCha20 (variante de ChaCha20)
- **Tamaño de clave**: 256 bits
- **Tamaño de nonce**: 192 bits
- **Implementación**: BCrypt (Windows), OpenSSL (Linux/macOS)

### Anti-Debug
- Métodos múltiples de detección
- Verificación de proceso padre
- Análisis de flags del proceso
- Detección de trazas del sistema

### Stealth
- Modificación de timestamps
- Limpieza de logs del sistema
- Eliminación de archivos temporales
- Spoofing de información del sistema

### UI/UX
- 16 gradientes de color diferentes
- 7 efectos de caja distintos
- 4 banners ASCII art aleatorios
- Sistema de emojis y símbolos
- Animaciones de progreso

## Desarrollo y Mantenimiento

### Estado del Proyecto
- **Estado**: Activo en desarrollo
- **Plataformas**: Windows (completo), Linux (completo), macOS (en desarrollo)
- **Última actualización**: Diciembre 2024

### Roadmap
- macOS: Implementación completa
- Nuevas funciones de criptografía
- Mejoras en UI/UX
- Soporte para más programas
- Funciones de red avanzadas

### Contribuciones
- Proyecto privado
- Desarrollo interno
- No acepta contribuciones externas
- Mantenimiento continuo

## Información Legal

### Uso
- Solo para fines educativos y de investigación
- Uso responsable requerido
- No se garantiza anonimización completa
- Usuario responsable de cumplir leyes locales

### Licencia
- Software privado
- No código abierto
- Distribución restringida
- Uso comercial prohibido
