ORÁCULO AI V2 — PROTOTIPO CON MOTOR DE VISIÓN + BÚSQUEDA WEB

QUÉ HACE
- Permite seleccionar JPG/PNG/WEBP desde móvil o computadora.
- Envía la imagen al backend solo al pulsar “Analizar con IA”.
- Usa OpenAI Responses API con entrada de imagen y herramienta web_search.
- Devuelve descripción, texto visible, elementos, pistas con cautela y fuentes públicas.
- Búsqueda externa manual de texto y enlaces a buscadores visuales.

IMPORTANTE
- No identifica personas ni realiza reconocimiento facial/biométrico.
- No busca información íntima o sexual de personas.
- La API requiere una clave propia y puede generar cargos por uso. No es parte de ChatGPT Plus/Pro y no se incluye ninguna clave.
- No publiques la clave en el navegador, HTML, repositorio público ni APK. Debe permanecer en el servidor.
- El proyecto no está desplegado en internet ni genera automáticamente un APK firmado.

CÓMO PROBAR EN TU COMPUTADORA
1. Instala Node.js 18 o posterior.
2. Entra a la carpeta server.
3. Copia .env.example como .env y agrega tu clave API.
4. Ejecuta: npm install
5. Ejecuta: npm start
6. Abre http://localhost:3000

PARA USAR DESDE ANDROID
Despliega web + server en un hosting HTTPS que soporte Node.js y variables de entorno.
Luego abre la URL en Chrome Android y usa el menú para “Añadir a pantalla principal”.
Para APK nativo, se puede envolver la web ya desplegada con Capacitor/Android Studio.

FUENTES TÉCNICAS
OpenAI Responses API e imágenes/visión:
https://developers.openai.com/api/docs/guides/images-vision
https://developers.openai.com/api/reference/responses/overview

ESTADO REAL
El código de integración está preparado. El análisis en vivo solo funciona después de configurar la clave y desplegar/ejecutar el servidor.
