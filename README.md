# Notas del corte 2 · CTD

Página estática para que cada estudiante consulte sus notas con su código estudiantil.

- `index.html`: la página.
- `data.json`: un registro cifrado (AES-GCM) por estudiante. La clave se deriva del código, así que el archivo no se puede leer de una vez.

El archivo de datos se genera fuera de este repositorio, con `_privado/construir_notas.py`.
