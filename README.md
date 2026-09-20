# NutriSport Web v1.3.4

Versión web de NutriSport sincronizada con el mismo proyecto Firebase que Android.

## Inicio de sesión

- **Google permanece disponible en la web** mediante Firebase Web `signInWithPopup`.
- Correo y contraseña continúan disponibles.
- La lógica PRO y los perfiles Firestore se mantienen.
- El flujo nativo de Credential Manager se utiliza únicamente cuando la app se ejecuta como Android Capacitor.

## UX corregida

- Se eliminó el espacio blanco inferior causado por el padding global del `body`.
- El fondo de `html`, `body` y la aplicación usa el fondo real de NutriSport.
- La navegación inferior conserva su espacio funcional sin crear una franja blanca debajo.
- Favicon, PWA e icono de la web usan el mismo logo NutriSport de la aplicación: flama verde + barra.

## Firebase

La versión utiliza Firebase JS SDK 11.10.0 para mantener la misma línea de versión que el proyecto Android y el plugin `@capacitor-firebase/authentication`.
