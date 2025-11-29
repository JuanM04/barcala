# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Los headers, footers, epígrafes y notas al pie ahora son más pequeños (9pt).
- Normalización de párrafos: sangría más pequeña y se eliminó el espacio entre párrafos. Además, se achicó el interlineado.
- Las figuras ahora tienen un margen respecto a los párrafos de 16pt.
- Se cambió el formato de los epígrafes y el título de las tablas ahora está en la parte superior.
- Se normalizó el formato de las listas y ahora utilizan paréntesis en lugar de puntos (`1)`, `a)`, `i)`).
- Enlaces de color azul, configurado en la plantilla para quitar fácilmente.
- Citas de ecuaciones tipo IEEE, configurado en la plantilla para quitar fácilmente.

## [0.2.0] - 2025-10-27

### Changed

- Se actualizó la versión mínima de Typst a 0.14.0
- Se renombraron los campos `titulo` y `titulo-descriptivo`
- _Character-level justification_ por defecto
- Utilizar [libra](https://typst.app/universe/package/libra) para centrar el título.

## [0.1.5] - 2025-10-09

### Changed

- Logos más permisivos.

## [0.1.4] - 2025-09-07

### Changed

- Se agregó la opción de pasar logos personalizados para `institucion` y `unidad-academica` como `str` o `bytes` usando `read` (#1).
- Se cambió `fancy-units` por `zero` para manejar unidades.

## [0.1.3] - 2025-08-06

### Changed

- El parámetro `titulo` del informe ahora es opcional. Si no se especifica, se usa el título descriptivo.

### Fixed

- Un resumen igual a `none` ahora no genera un error.
- Errores de ortografía en la plantilla.

## [0.1.2] - 2025-05-12

### Fixed

- Thumbnail de la template en Typst Universe.
- Se corrigió el header cuando el nombre de la materia es muy largo.

## [0.1.1] - 2025-04-10

### Changed

- Template con `fancy-units`, `lilaq` y `physica`.
- Template con bibliografía de ejemplo.

### Fixed

- Typos en la documentación.

## [0.1.0] - 2025-04-07

### Added

- Primera versión del paquete `@preview/barcala`.
- Primera versión del template de Typst.
- Documentación general.

[unreleased]: https://github.com/JuanM04/barcala/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/JuanM04/barcala/compare/v0.1.5...v0.2.0
[0.1.5]: https://github.com/JuanM04/barcala/compare/v0.1.4...v0.1.5
[0.1.4]: https://github.com/JuanM04/barcala/compare/v0.1.3...v0.1.4
[0.1.3]: https://github.com/JuanM04/barcala/compare/v0.1.2...v0.1.3
[0.1.2]: https://github.com/JuanM04/barcala/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/JuanM04/barcala/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/JuanM04/barcala/releases/tag/v0.1.0