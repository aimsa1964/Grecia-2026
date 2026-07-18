# Constitución del proyecto

## 1. Identidad

**Título:** *Tras las huellas del mundo griego*  
**Subtítulo:** *Viaje por la cuna de Occidente*

Este repositorio alberga una publicación digital de carácter histórico, cultural y visual sobre un viaje por Grecia y otros enclaves del mundo griego.

## 2. Propósito

El proyecto no es un blog ni un simple diario de viaje. Su objetivo es construir una obra editorial digital, rigurosa, visualmente cuidada y navegable, que combine:

- contexto histórico y arqueológico;
- geografía y cronología;
- arquitectura, mitología y personajes;
- fotografías propias comentadas;
- mapas, itinerarios y recursos prácticos;
- bibliografía y fuentes verificables.

## 3. Alcance editorial

La estructura principal prevista es:

1. Introducción
2. Atenas
3. Acrópolis
4. Ágora
5. Museo
6. Mykonos
7. Éfeso
8. Patmos
9. Rodas
10. Creta
11. Santorini
12. Anexos y recursos

Cada capítulo podrá contener, según proceda:

- introducción;
- geografía;
- historia;
- cronología;
- personajes;
- arquitectura;
- mitología;
- curiosidades;
- comentarios de fotografías;
- bibliografía.

## 4. Principios de calidad

1. **Rigor:** no se incorporarán afirmaciones históricas o arqueológicas dudosas sin advertencia o fuente.
2. **Coherencia:** todos los capítulos compartirán estructura, navegación y tratamiento visual.
3. **Valor editorial:** las fotografías forman parte del discurso y no son mera decoración.
4. **Trazabilidad:** las decisiones relevantes deben quedar registradas en la Bitácora.
5. **Autosuficiencia:** el repositorio debe permitir comprender y continuar el proyecto sin consultar conversaciones externas.
6. **Pragmatismo:** se priorizarán soluciones simples, mantenibles y proporcionadas al valor que aportan.

## 5. Documentos rectores

Los documentos oficiales del proyecto son:

- [`README.md`](README.md): puerta de entrada al repositorio.
- [`CONSTITUCION.md`](CONSTITUCION.md): propósito, alcance y reglas permanentes.
- [`BITACORA.md`](BITACORA.md): memoria razonada de las iteraciones y decisiones.
- [`ESTILO.md`](ESTILO.md): normas editoriales y visuales.
- [`PLAN.md`](PLAN.md): estado operativo, bloques y próximos pasos.

En caso de contradicción, prevalece este orden:

1. Constitución
2. Estilo
3. Decisiones más recientes de la Bitácora
4. Plan
5. Implementación existente

## 6. Regla de continuidad entre hilos

Antes de iniciar trabajo en un hilo nuevo se deberá revisar:

1. esta Constitución;
2. la Hoja de Estilo;
3. la última entrada de la Bitácora;
4. el estado vigente del Plan.

Estos documentos constituyen la memoria oficial del proyecto y prevalecen sobre recuerdos parciales del contexto conversacional.

## 7. Método de trabajo

El trabajo se organiza por bloques verificables:

1. definir el objetivo;
2. revisar entradas y dependencias;
3. desarrollar;
4. validar;
5. actualizar Bitácora y Plan cuando corresponda;
6. realizar un commit descriptivo;
7. comunicar el cierre del bloque y el siguiente paso.

Ninguna sesión relevante se considera cerrada hasta que la Bitácora recoja el trabajo realizado, las decisiones adoptadas y su justificación.

## 8. Versionado

Se utilizará una versión editorial `M.m`:

- **Versión mayor (`M.0`)**: cierre de una ciudad, capítulo principal o hito editorial equivalente.
- **Versión menor (`M.m`)**: incorporación diaria o sesión relevante que modifique contenido, estructura, recursos o decisiones.

Ejemplo:

- `2.0`: Atenas finalizada.
- `2.1`: nueva galería fotográfica.
- `2.2`: cronología y bibliografía revisadas.
- `2.3`: incorporación de recursos o ajustes relevantes del día.

La versión no se incrementará por correcciones triviales sin impacto editorial.

## 9. Gestión de recursos

- Los nombres de archivo serán estables, descriptivos y sin ambigüedad.
- No se moverán ni renombrarán recursos sin actualizar todos sus enlaces.
- Las imágenes y documentos deberán conservar metadatos editoriales suficientes para identificarlos.
- Los datos estructurados se almacenarán preferentemente en formatos abiertos y legibles.
- No se utilizará `.gitignore`: el proyecto no contiene secretos y pretende ser autocontenido.

## 10. Gestión de cambios

Todo cambio significativo debe cumplir al menos una de estas condiciones:

- mejorar el contenido;
- corregir un error;
- aumentar la coherencia;
- facilitar la continuidad del proyecto;
- reducir deuda técnica o editorial real.

No se realizarán rediseños amplios sin una mejora clara y proporcional.

## 11. Criterio de cierre

Un bloque se considera cerrado cuando:

- la salida existe y es accesible;
- los enlaces afectados funcionan;
- el contenido respeta la Hoja de Estilo;
- la Bitácora recoge las decisiones relevantes;
- el Plan refleja el nuevo estado;
- existe un commit identificable.

---

Esta Constitución es estable. Solo deberá modificarse cuando cambien la naturaleza, los principios o la metodología general del proyecto.