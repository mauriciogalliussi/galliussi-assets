# galliussi-assets

Piezas gráficas y videos de **Galliussi Seguros**, servidos por URL para que la API de Meta pueda leerlos al publicar en Instagram y Facebook.

## Por qué este repositorio es público

Es a propósito. La API de Instagram **no recibe archivos: recibe una URL** y baja la imagen desde ahí. Para eso tiene que ser alcanzable públicamente.

Son avisos: material que ya está destinado a que lo vea todo el mundo.

## Lo que NO está acá y nunca va a estar

Planes, presupuestos, análisis de competencia, auditorías, plantillas de trabajo y —sobre todo— **datos de clientes**. Todo eso vive en un repositorio **privado** aparte.

El `.gitignore` de este repo funciona por **lista blanca**: ignora todo y permite solo `.jpg`, `.mp4` y tres archivos de control.

## Estructura

| Carpeta | Qué tiene | Formato |
|---|---|---|
| `feed/` | piezas de feed | JPEG 1080×1080 |
| `historias/` | historias | JPEG 1080×1920 |
| `carruseles/` | carruseles, numerados en orden | JPEG 1080×1080 |
| `portadas/` | portadas de destacadas | JPEG |
| `reels/` | reels | MP4 1080×1920 |

`manifiesto.json` lista cada pieza con sus dimensiones, su peso y si cumple las validaciones de Instagram (ratio entre 4:5 y 1.91:1 para feed, menos de 8 MB).

---
Galliussi Seguros · N° de matrícula SSN 64.707 · Neuquén
