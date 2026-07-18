# Plan operativo

## Estado general

**Versión documental vigente:** 0.3  
**Avance global estimado:** 24 %  
**Estado:** infraestructura documental completada; guía de compras integrada en el proyecto; recursos multimedia y primer capítulo editorial pendientes.

## Bloques de trabajo

| ID | Bloque | Estado | Avance |
|---|---|---:|---:|
| B01 | Crear repositorio | Cerrado | 100 % |
| B02 | Configurar GitHub Pages | Cerrado | 100 % |
| B03 | Definir estructura del libro | Cerrado | 100 % |
| B04 | Estructurar itinerario | Cerrado | 100 % |
| B05 | Integrar la guía de compras | En curso | 35 % |
| B06 | Crear catálogo inicial de fotografías | Cerrado | 100 % |
| B07 | Incorporar recursos multimedia | En curso | 30 % |
| B08 | Desarrollar capítulo Atenas | Pendiente | 0 % |
| B09 | Completar navegación | Pendiente | 0 % |
| B10 | Consolidar microsite editorial | Pendiente | 0 % |

## Bloque documental cerrado

### D01 — Memoria y continuidad entre hilos

**Estado:** cerrado

Salidas:

- `README.md`
- `CONSTITUCION.md`
- `BITACORA.md`
- `ESTILO.md`
- `PLAN.md`

Criterio conseguido:

> El proyecto puede retomarse desde un hilo nuevo mediante la lectura de sus documentos rectores, sin depender del historial completo de conversaciones.

## Bloque integrado: guía de compras

### B05 — Integración de la guía de compras

**Objetivo:** incorporar la guía de compras como una sección estable del proyecto *Tras las huellas del mundo griego*, con identidad propia dentro del sitio, pero integrada en su navegación, estructura editorial, estilo visual y sistema de versiones.

#### Alcance funcional

- Acceso desde la portada y la navegación general.
- Secciones por destino: Atenas, Mykonos, Éfeso, Patmos, Rodas, Creta y Santorini.
- Recuperación de todas las fotografías e ilustraciones del PDF original.
- Optimización de imágenes para web y organización en `images/compras/`.
- Fichas de recuerdos con descripción, lugar de compra, precio orientativo, criterios de autenticidad y consejos de transporte.
- Galería ampliable.
- Checklist de compras.
- Enlace de descarga al PDF original.
- Diseño adaptable a móvil y escritorio con la hoja de estilo común.
- Enlaces cruzados con los capítulos de cada destino cuando existan.

#### Entradas conocidas

- PDF `Guia_compras_Grecia_6_paginas(1).pdf`.
- Contenido textual ya estructurado.
- Fotografías e ilustraciones incrustadas en el PDF, todavía pendientes de extracción e incorporación al repositorio.

#### Pendiente

- [ ] Extraer las imágenes originales del PDF.
- [ ] Revisar calidad, duplicados y correspondencia con cada destino.
- [ ] Convertir imágenes a formatos web adecuados.
- [ ] Crear la estructura `images/compras/`.
- [ ] Reconstruir `guia-compras.html` con imágenes y diseño editorial completo.
- [ ] Incorporar fichas, precios, advertencias y checklist.
- [ ] Añadir la descarga del PDF original.
- [ ] Enlazar la guía desde la portada y el menú general.
- [ ] Crear enlaces cruzados con Atenas, Mykonos, Éfeso, Patmos, Rodas, Creta y Santorini.
- [ ] Verificar visualización en móvil y escritorio.
- [ ] Comprobar la publicación en GitHub Pages.

#### Criterio de cierre

- La guía conserva íntegramente el contenido y las imágenes relevantes del PDF.
- La navegación por destinos funciona.
- Las imágenes tienen texto alternativo y pie coherente.
- El PDF original puede descargarse.
- La guía forma parte de la arquitectura del proyecto y comparte navegación y estilo.
- Existen enlaces cruzados con los capítulos de destino disponibles.
- La versión publicada funciona correctamente en GitHub Pages.

## Bloque actual

### B07 — Recursos multimedia

**Objetivo:** incorporar los recursos originales y publicar una primera galería funcional de Atenas.

#### Entradas conocidas

- Tres fotografías nocturnas de Atenas:
  - Acrópolis iluminada;
  - panorama con el Licabeto;
  - segunda vista nocturna de la Acrópolis.
- PDF `Guia_compras_Grecia_6_paginas(1).pdf` como fuente del bloque integrado B05.
- Metadatos estructurados existentes en `data/`.

#### Pendiente

- [ ] Subir los JPG originales.
- [ ] Normalizar nombres de archivo.
- [ ] Generar miniaturas si resultan necesarias.
- [ ] Completar metadatos disponibles.
- [ ] Crear galería de Atenas.
- [ ] Añadir pies históricos y fotográficos.
- [ ] Enlazar la galería desde la navegación.
- [ ] Comprobar la publicación en GitHub Pages.
- [ ] Coordinar los recursos de la guía de compras con el bloque B05.
- [ ] Actualizar la Bitácora al cerrar el bloque.

#### Criterio de cierre

- Las tres fotografías originales están versionadas.
- La galería se publica y es navegable.
- Las imágenes tienen texto alternativo y pies coherentes.
- Los enlaces funcionan en GitHub Pages.
- Bitácora y Plan quedan actualizados.

## Siguiente bloque

### B08 — Atenas

Contenido previsto:

- apertura editorial;
- geografía y contexto urbano;
- historia;
- cronología;
- Acrópolis;
- Ágora;
- Licabeto;
- Plaka;
- fotografías comentadas;
- mapas;
- curiosidades;
- bibliografía;
- enlaces cruzados con la guía de compras.

## Riesgos y dependencias

1. **Ficheros binarios no disponibles en el repositorio:** las fotografías y el PDF deben estar accesibles en una sesión con capacidad de subida binaria.
2. **Imágenes de la guía pendientes de recuperación:** la página HTML actual no se considera completa hasta extraer y reincorporar las imágenes del PDF.
3. **Metadatos incompletos:** fecha, coordenadas y autoría deberán confirmarse o marcarse como pendientes.
4. **Estilos dispersos:** cualquier página nueva debe utilizar la hoja CSS común.
5. **Enlaces rotos:** los cambios de nombres o carpetas requieren verificación en GitHub Pages.

## Regla de actualización

El Plan se actualiza cuando cambie:

- el estado de un bloque;
- el porcentaje de avance;
- la prioridad;
- una dependencia;
- el siguiente hito.

Las razones de las decisiones no se documentan aquí, sino en `BITACORA.md`.