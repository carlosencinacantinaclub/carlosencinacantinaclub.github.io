# Sonidos de Notificación

## 📁 Archivos de Sonido Requeridos

Para que funcionen las notificaciones sonoras, necesitas agregar estos archivos en la carpeta `public/sounds/`:

### 🔊 Archivos Necesarios:

1. **`pedido.mp3`** - Sonido para pedidos nuevos
   - Duración recomendada: 2-4 segundos
   - Tono: Agudo, alegre, llamativo
   - Ejemplo: "Ding" o "Chime" corto

2. **`cuenta.mp3`** - Sonido para solicitud de cuenta
   - Duración recomendada: 3-5 segundos
   - Tono: Más grave, profesional, distintivo
   - Ejemplo: "Bell" o "Notification" mediano

### 📊 Especificaciones Técnicas:

- **Formato**: MP3 (compatible con todos los navegadores)
- **Calidad**: 128kbps o superior
- **Volumen**: Moderado (no muy alto)
- **Duración**: Corta (2-5 segundos máximo)

### 🎵 Sugerencias de Sonidos:

#### Para Pedidos (`pedido.mp3`):
- Sonido de campanita
- "Ding" corto y alegre
- Notificación de WhatsApp
- Sonido de caja registradora

#### Para Cuentas (`cuenta.mp3`):
- Sonido de timbre
- "Bell" más grave
- Notificación de email
- Sonido de cajero automático

### 🔧 Instalación:

1. Descarga o crea los archivos de sonido
2. Colócalos en `public/sounds/`
3. Asegúrate de que se llamen exactamente:
   - `pedido.mp3`
   - `cuenta.mp3`

### ✅ Verificación:

Los archivos deben estar accesibles en:
- `http://localhost:5173/sounds/pedido.mp3`
- `http://localhost:5173/sounds/cuenta.mp3`

### 🚨 Nota Importante:

Si no se encuentran los archivos, las notificaciones funcionarán normalmente pero sin sonido (se mostrará un warning en consola).
