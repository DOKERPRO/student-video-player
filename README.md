# VideoNotes Player

Reproductor de escritorio de video con anotaciones sincronizadas desarrollado en Python, PySide6 y libVLC.

## Versión en preparación: v4

Incluye notas con marcas de tiempo, miniaturas, playlists, subtítulos externos, capturas, repetición A–B, búsqueda por categoría, reanudación de reproducción e importación de carpetas.

**Estado de esta publicación:** la subida del código fuente completo está pendiente. Por ahora este repositorio contiene la documentación inicial, el archivo de dependencias y las reglas para excluir archivos locales. No ejecutar el proyecto desde GitHub hasta incorporar la carpeta `app/` y `main.py`.

## Requisitos

- Windows 10/11
- Python 3.10+
- VLC Media Player de 64 bits

## Instalación (cuando se publique el código fuente)

```bat
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python main.py
```

## Privacidad

No se incluyen vídeos personales, anotaciones privadas, archivos SQLite, capturas ni entornos virtuales.

## Licencia

Sin licencia declarada por el momento.
