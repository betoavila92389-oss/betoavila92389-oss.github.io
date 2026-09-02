# Sitio de las aplicaciones de la Escuela Primaria María G. de Ortiz No. 2571

Páginas de presentación, **política de privacidad** y **descargas** de las aplicaciones
Android de uso interno de la dirección del plantel (Meoqui, Chihuahua).

| Aplicación | Páginas |
|---|---|
| **Gestor Escolar** | `/` · [descargas](descargas.html) · [historial](historial.html) · [privacidad](privacidad.html) |
| **Sello Digital 2571** | [`/sello/`](sello/) · [descargas](sello/descargas.html) · [historial](sello/historial.html) · [privacidad](sello/privacidad.html) |

Existen porque Google Cloud las exige para publicar el consentimiento de OAuth: las apps
respaldan en Google Drive con el permiso `drive.file` y, sin una página principal y una
política de privacidad publicadas, el permiso de la cuenta caduca cada siete días.

Cada app publica además un `version.json` con la última versión y un `historial.json` con
todas. Las apps consultan ese archivo para avisar solas cuando hay una versión nueva; los
APK van en las *releases* de este repositorio, con la etiqueta `v<versión>-<build>` para
Gestor Escolar y `sello-v<versión>-<build>` para Sello Digital.

Aquí no hay ningún dato de la escuela: son páginas estáticas.
