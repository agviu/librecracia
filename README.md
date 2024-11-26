# Librecracia

## ¿Cómo crear el libro?
Este libro está escrito utilizando (mdBook)[https://rust-lang.github.io/mdBook/]. Necesitas esta aplicación para construir el libro.
Instálala tal y como indican en su (documentación)[https://rust-lang.github.io/mdBook/guide/installation.html].

Una vez instalada, ejecuta esto desde el directorio donde tengas descargado el libro:
```bash
mdbook build
```

## Github Actions
Este repositorio tiene un workflow para automáticamente generar el libro cada vez que se publica una nueva versión.