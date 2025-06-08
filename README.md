# M-Society Anonimatium P2P v4.0 🔐

![Logo](https://i.ibb.co/N2xphmmm/asd-1.png)

**Anonimatium Pro** es una herramienta avanzada de comunicación peer-to-peer (P2P) cifrada de extremo a extremo, diseñada para usuarios que valoran la privacidad y seguridad en sus comunicaciones digitales.

## 🌟 Características Principales

- **Cifrado AES-256**: Todas las comunicaciones están encriptadas con el estándar militar AES-256
- **Comunicación Directa P2P**: Conexiones directas sin servidores intermedios
- **Anonimato Automático**: Asigna identidades anónimas aleatorias
- **Interfaz Segura**: Diseñada para operaciones discretas con estilo oscuro
- **Auto-descubrimiento**: Sistema integrado de gestión de conexiones
- **Multiplataforma**: Compatible con Windows, Linux y macOS
- **Sistema de Logs**: Registro completo de actividades en la interfaz

## 🛡️ Problemas Resueltos

1. **Privacidad Comprometida**:
   - Elimina la necesidad de servidores centralizados que puedan registrar conversaciones
   - No requiere registro de usuarios ni datos personales

2. **Interceptación de Comunicaciones**:
   - Cifrado de extremo a extremo imposibilita la lectura por terceros
   - Cada sesión genera claves únicas

3. **Metadatos Expuestos**:
   - Sistema de nicknames anónimos rotatorios
   - No almacena información de conexión después de cerrar la sesión

4. **Centralización de Servicios**:
   - Arquitectura descentralizada pura
   - Cada nodo es igual en la red

5. **Censura**:
   - Conexiones directas difíciles de bloquear
   - Puerto de escucha aleatorio en cada ejecución

## 🚀 Cómo Funciona

1. **Inicio Automático**:
   - Al ejecutar, la herramienta:
     - Genera un nickname anónimo (ej: `Anon_5832`)
     - Detecta tu IP local
     - Abre un puerto aleatorio (49152-65535)
     - Inicia el servidor de escucha

2. **Conexión entre Peers**:
   - Para conectar a otro peer necesitas su `IP:puerto`
   - El sistema negocia automáticamente:
     1. Intercambio cifrado de nicknames
     2. Establecimiento de canal seguro
     3. Confirmación mutua de conexión

3. **Flujo de Mensajes**:
   - Cada mensaje se cifra con:
     - AES-256 en modo CBC
     - IV único por mensaje
     - Codificación Base64 para transmisión
   - Se descifra solo en el extremo receptor

4. **Gestión de Conexiones**:
   - Detección automática de desconexiones
   - Actualización en tiempo real de peers conectados
   - Notificaciones del sistema para eventos importantes

## 📊 Ventajas Clave

| Característica | Beneficio |
|---------------|-----------|
| **Sin Servidores** | Elimina puntos únicos de fallo y vigilancia |
| **Cifrado Fuerte** | Protección contra escuchas incluso en redes no confiables |
| **Auto-configuración** | No requiere conocimientos técnicos para usar |
| **Interfaz Limpia** | Muestra solo información esencial cuando es necesario |
| **Multiplataforma** | Misma seguridad en cualquier sistema operativo |

## 📝 Sistema de Logs

- **Registro Completo**: Todas las actividades se registran en la interfaz con:
  - Marca de tiempo implícita
  - Identificación clara de mensajes del sistema
  - Diferenciación visual de usuarios
- **Persistencia**: Los logs permanecen durante la sesión pero:
  - No se guardan en disco por defecto (volátiles)
  - Opción de copiar manualmente si se requiere

## 🖥️ Requisitos Técnicos

windows, linux o mac
(si nececitas la app para linux o mac contactanos por [discord](https://discord.gg/9QRngbrMKS))

## ⚠️ Limitaciones

1. **NAT/Firewalls**: Puede requerir configuración manual en redes restrictivas
2. **Descubrimiento de Peers**: Necesita conocer la IP/puerto del peer para conectarse
3. **Sin Historial**: Los mensajes no persisten después de cerrar la aplicación
4. **Ancho de Banda**: Rendimiento depende de la conexión directa entre peers

## 🔧 Uso Avanzado

- **Cambiar Nickname**: Click en "✏️ Nickname"
- **Conectar a Peer**: Click en "🔗 Conectar" e ingresa `IP:puerto`
- **Enviar Mensaje**: Escribe y presiona Enter o click en "🚀 Enviar"
- **Logo Clickable**: Click en el logo para visitar M-Society

## 📜 Licencia

GPLv3 - Software libre para uso personal y comunitario. Prohibido su uso con fines maliciosos.

## 🌍 Filosofía

"La privacidad no es un lujo, es un derecho fundamental. Anonimatium devuelve el control al usuario."

--- 

**Nota**: Este software es para fines educativos y de privacidad personal. Los desarrolladores no se responsabilizan por mal uso.
