# Bitácora del proyecto

La Bitácora es la memoria razonada de *Tras las huellas del mundo griego*. Resume las iteraciones de trabajo y conserva las decisiones relevantes junto con su motivación.

No sustituye al Plan ni a la Constitución:

- la **Constitución** define las reglas estables;
- el **Plan** indica qué se hará y en qué estado se encuentra;
- la **Bitácora** explica qué se hizo, qué se decidió y por qué.

## Formato de las entradas

Cada sesión relevante deberá registrar:

- versión;
- fecha;
- objetivo;
- trabajo realizado;
- decisiones adoptadas;
- motivación;
- alternativas descartadas, cuando sean relevantes;
- problemas encontrados y resolución;
- commits asociados;
- estado resultante;
- próximos pasos.

---

## Versión 0.2 — Infraestructura documental

**Fecha:** 2026-07-19

### Objetivo

Preparar el repositorio para trabajar a través de múltiples hilos sin depender del tamaño del contexto conversacional.

### Trabajo realizado

- Se establece `README.md` como puerta de entrada.
- Se amplía `CONSTITUCION.md` como documento fundacional.
- Se crea `BITACORA.md` como memoria de las iteraciones.
- Se crea `ESTILO.md` para mantener la coherencia editorial y visual.
- Se crea `PLAN.md` para controlar avance, bloques y próximos pasos.
- Se fija un sistema de versionado mayor y menor.
- Se confirma que el repositorio no utilizará `.gitignore`.

### Decisiones adoptadas

1. Separar la normativa estable de la memoria de trabajo.
2. Mantener una única hoja de estilo aplicable a todos los capítulos.
3. Registrar en la Bitácora no solo las decisiones, sino también su razón.
4. Considerar una ciudad o hito editorial cerrado como versión mayor.
5. Considerar las incorporaciones relevantes de una jornada o sesión como versión menor.
6. Usar el repositorio como memoria oficial frente al contexto de los chats.

### Motivación

Los hilos tienen un contexto limitado y el proyecto crecerá en textos, fotografías, mapas y decisiones. La documentación rectora permite reiniciar el trabajo desde cualquier conversación, conservar coherencia y evitar reconstruir decisiones ya tomadas.

### Alternativas descartadas

- Integrar Constitución y Bitácora en un único documento: se descarta porque mezclaría reglas permanentes con decisiones evolutivas.
- Guardar toda la documentación dentro de una carpeta secundaria: se descarta por ahora para que los documentos rectores sean visibles desde la raíz.
- Añadir `.gitignore`: se descarta porque no existen secretos y se busca un repositorio autocontenido.

### Resultado

El repositorio dispone de una estructura documental suficiente para continuar el proyecto de manera distribuida entre hilos y sesiones.

### Commits asociados

- `fcadbcd23fa0a3e4fb85dfa7cc63f78768c2c441` — creación inicial de la Constitución.
- `d5ff3e5a1cb8f94bc701e3890452c44618e98cfc` — ampliación de la Constitución.
- `16d065af3020042a09f45a25b70ccc2abbb11c8b` — creación del README.
- Los commits de Bitácora, Estilo y Plan completan este bloque documental.

### Próximos pasos

1. Cerrar el bloque de recursos multimedia.
2. Incorporar las fotografías originales de Atenas.
3. Crear y publicar la galería de Atenas.
4. Actualizar la Bitácora y el Plan al terminar el bloque.

---

## Plantilla para futuras entradas

```markdown
## Versión X.Y — Título

**Fecha:** AAAA-MM-DD

### Objetivo

### Trabajo realizado

### Decisiones adoptadas

### Motivación

### Alternativas descartadas

### Problemas y resolución

### Resultado

### Commits asociados

### Próximos pasos
```
