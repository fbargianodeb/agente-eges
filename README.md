# agente-eges

Interfaz web moderna para el asistente virtual de **Eges | Inteligencia Estratégica**. Este proyecto separa la estructura (HTML) del diseño (CSS) para facilitar su mantenimiento y personalización.

## 🚀 Características

* **Glassmorphism Design:** Una tarjeta central con efecto de desenfoque de fondo y bordes suaves.
* **Indicador de Estado:** Animación CSS "pulse" que muestra la disponibilidad del agente en tiempo real.
* **Responsive:** Diseño adaptado para dispositivos móviles y escritorio usando Flexbox.
* **Integración:** Preparado para conectar con el widget de chat de **Journey Builder**.

## 📂 Estructura del proyecto

El código está organizado de la siguiente manera:

- `index.html`: Contiene la estructura semántica y la configuración del widget.
- `style.css`: Contiene todas las variables de color, tipografía y animaciones.

## 🛠️ Instalación y Uso

1. Descarga ambos archivos en una misma carpeta.
2. Abre el archivo `index.html` en tu navegador.
3. **Importante:** Para que el chat funcione, asegúrate de reemplazar los valores `XX1`, `XX3` y `XXX4` en el archivo HTML con tus credenciales reales:

```html
<journey-builder-chat
    window_title="Base de conocimiento - Agente Eges"
    flow_id="TU_FLOW_ID"
    host_url="TU_HOST_URL"
    api_key="TU_API_KEY">
</journey-builder-chat>