# NaviaXP

Reproductor para Android de juegos hechos con RPG Maker y Essentials.

Este repositorio es solo el canal de descarga. Cada versión se publica en
[Releases](../../releases).

---

## Descarga

Ve a [Releases](../../releases) y baja el archivo `.apk`.

| Archivo | Cuándo |
|---|---|
| `NaviaXP-<version>-universal-release.apk` | Funciona en cualquier teléfono |
| `NaviaXP-<version>-arm64-v8a-release.apk` | Si sabes que tu teléfono es de 64 bits y quieres ahorrar espacio |
| `NaviaXP-<version>-armeabi-v7a-release.apk` | Teléfonos antiguos de 32 bits |

Si no sabes cuál, baja la **universal**.

## Requisitos

- Android 6.0 o superior.
- Espacio para tus juegos. La app no trae ninguno.

## Instalación

1. Abre el `.apk` que descargaste.
2. Si es la primera vez instalando una app fuera de Google Play, Android te pedirá 
   permitir instalaciones desde el navegador o el explorador de archivos. 
   Es normal fuera de la tienda.
3. Al abrir la app, dale permiso de acceso a archivos: lo necesita para leer
   las carpetas de tus juegos.
4. Pulsa **Agregar juego** y elige la carpeta que contiene `Game.ini`. Esta siempre
   está en donde se ubica tambien el Game.exe.

### "Se recomienda analizar esta app"

Google avisa de cualquier app que no venga de su tienda y que todavía no haya
analizado con su sistema Play Protect. Puedes tocar en **Analizar app** para que la 
revise. Tambien sirve para que compruebes que lo que descargas no es peligroso.

Si quieres comprobar que el archivo es el nuestro y nadie lo ha tocado, todas
las versiones van firmadas con el mismo certificado:

```
SHA-256 del certificado:
4564a43a71174a8cc11ed0aecd1e5d986641df895d7f584197ccc171a89f29f7
```

## Idioma

La app sigue el idioma de tu teléfono: español si lo tienes en español,
inglés en cualquier otro caso. Se puede forzar en **Ajustes → Idioma**.

---

## English

Android player for games made with RPG Maker and Essentials. This repository
is the download channel only — grab the `.apk` from [Releases](../../releases).

Pick the **universal** build unless you know your device's architecture.
Requires Android 6.0 or newer. No games are included: point the app at a folder
containing `Game.ini`.

The app follows your phone's language — Spanish if your phone is in Spanish,
English otherwise. You can force one in **Settings → Language**.
