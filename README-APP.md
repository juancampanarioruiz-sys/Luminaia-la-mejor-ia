# Clipia Studio: web, Android, iOS y escritorio

## Instalar desde el navegador

En Android/Chrome y en PC/Chrome o Edge, abre la web publicada y usa **Instalar aplicación** si aparece el botón o la opción del navegador. En iPhone/iPad, abre la página en Safari, pulsa **Compartir** y elige **Añadir a pantalla de inicio**.

## Android / Google Play

Necesitas Node.js LTS y Android Studio con el SDK. Clona el repositorio, ejecuta `npm install`, después `npm run android:add` la primera vez y `npm run android:sync` al cambiar la web. Abre el proyecto con `npm run android:open`, prueba en emulador/dispositivo y genera un **Android App Bundle (.aab)** firmado desde Android Studio. Súbelo primero a una pista de pruebas en Google Play Console.

## iOS / App Store

Necesitas un Mac con Xcode y una cuenta de Apple Developer. Ejecuta `npm install`, luego `npm run ios:add` la primera vez y `npm run ios:open`. Configura la firma en Xcode, prueba en dispositivo y prepara la distribución en App Store Connect.

## Seguridad y límites

No guardes claves privadas ni contraseñas en GitHub. La publicación requiere cuenta de desarrollador, ficha, políticas y revisión de la tienda. La web instalable funciona en navegadores compatibles; los paquetes nativos deben compilarse y firmarse con las herramientas de cada plataforma. El editor trabaja con archivos locales y la exportación depende de las capacidades del navegador/dispositivo.
