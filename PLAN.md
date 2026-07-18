# Plan operativo

## Estado general

**Versión documental vigente:** 0.2  
**Avance global estimado:** 22 %  
**Estado:** infraestructura documental completada; recursos multimedia y primer capítulo editorial pendientes.

## Bloques de trabajo

| ID | Bloque | Estado | Avance |
|---|---|---:|---:|
| B01 | Crear repositorio | Cerrado | 100 % |
| B02 | Configurar GitHub Pages | Cerrado | 100 % |
| B03 | Definir estructura del libro | Cerrado | 100 % |
| B04 | Estructurar itinerario | Cerrado | 100 % |
| B05 | Estructurar recomendaciones de compras | Cerrado | 100 % |
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

## Bloque actual

### B07 — Recursos multimedia

**Objetivo:** incorporar los recursos originales y publicar una primera galería funcional de Atenas.

#### Entradas conocidas

- Tres fotografías nocturnas de Atenas:
  - Acrópolis iluminada;
  - panorama con el Licabeto;
  - segunda vista nocturna de la Acrópolis.
- PDF `Guia_compras_Grecia_6_paginas(1).pdf`.
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
- [ ] Incorporar el PDF de compras o una versión web equivalente.
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
- enlaces cruzados.

## Riesgos y dependencias

1. **Ficheros binarios no disponibles en el repositorio:** las fotografías y el PDF deben estar accesibles en una sesión con capacidad de subida binaria.
2. **Metadatos incompletos:** fecha, coordenadas y autoría deberán confirmarse o marcarse como pendientes.
3. **Estilos dispersos:** cualquier página nueva debe utilizar la hoja CSS común.
4. **Enlaces rotos:** los cambios de nombres o carpetas requieren verificación en GitHub Pages.

## Regla de actualización

El Plan se actualiza cuando cambie:

- el estado de un bloque;
- el porcentaje de avance;
- la prioridad;
- una dependencia;
- el siguiente hito.

Las razones de las decisiones no se documentan aquí, sino en `BITACORA.md`.
