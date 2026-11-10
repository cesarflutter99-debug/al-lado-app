# Al Lado

Marketplace geolocalizado para conectar con comercios, servicios y anuncios de tu comunidad.

## Descarga

Descarga la última versión de la app:

**[Descargar Al Lado (APK)](https://github.com/cesarflutter99-debug/al-lado-app/releases/latest/download/al-lado.apk)**

O visita la [página de releases](https://github.com/cesarflutter99-debug/al-lado-app/releases) para ver todas las versiones disponibles.

## Instalación

1. Descarga el archivo `al-lado.apk`.
2. En tu dispositivo Android, permite la instalación de aplicaciones de fuentes desconocidas (Configuración → Seguridad → Fuentes desconocidas).
3. Abre el archivo APK descargado e instala la aplicación.

## Requisitos

- Android 6.0 (API 23) o superior.
- Conexión a internet para el primer uso.

## Notas

- Esta es una versión beta (pre-release). Puede contener errores.
- La app requiere permisos de ubicación, cámara y notificaciones para funcionar correctamente.

---

## Procedimiento para futuras versiones

Para publicar una nueva versión de la app, sigue estos pasos:

1. **El APK se llama SIEMPRE exactamente `al-lado.apk`.** No uses otro nombre.
2. **Cada versión nueva es un release nuevo con tag nuevo** (v0.9.0-beta.2, v0.9.1, etc.), **sin marca de pre-release** y **como latest**.
3. **El APK va solo como archivo adjunto del release**, nunca dentro del repositorio.
4. **Comando para crear el release:**
   ```
   gh release create TAG al-lado.apk --title "TÍTULO" --notes "NOTAS" --latest
   ```
   Ejemplo:
   ```
   gh release create v0.9.1 al-lado.apk --title "Al Lado 0.9.1" --notes "Correcciones de bugs" --latest
   ```

> **Importante:** No subas keystores, claves, `.env` ni ningún otro archivo al repositorio. Solo el README y el APK como asset del release.

---

*Al Lado — Marketplace geolocalizado*