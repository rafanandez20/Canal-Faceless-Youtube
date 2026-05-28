# Configuración de Voz — ElevenLabs
## Canal: [Nombre del canal]
**Última actualización:** 28 de mayo de 2026

---

## Objetivo de la voz

Sonar como alguien que te cuenta algo que le parece fascinante en una conversación íntima.
**NO** como locutor de documental. **NO** como presentador de noticias. **NO** como narrador de audiolibro.

La referencia de tono es: un amigo inteligente que acaba de descubrir algo que le voló la cabeza y te lo está contando de noche, sentado frente a ti.

---

## Voz seleccionada

| Campo | Valor |
|---|---|
| **Plataforma** | ElevenLabs |
| **Tipo de voz** | Voz única propia — creada con Voice Design el 28-05-2026 |
| **ID de voz** | [Rellenar desde ElevenLabs > My Voices] |
| **Idioma** | Español de España (castellano) |
| **Género** | Masculino |
| **Tono base** | Cálido, rico, ligeramente ronco. Maduro sin ser viejo. Envolvente. |

---

## Configuración de parámetros

### Panel de ajustes en ElevenLabs

> ⚠️ **ACTUALIZACIÓN 27-05-2026:** Ajustes revisados para corregir voz monótona y lenta. Problema reportado por viewers: "se duermen" y ritmo muy lento.

| Parámetro | Valor anterior | Valor nuevo | Por qué el cambio |
|---|---|---|---|
| **Speed** | (no configurado) | **1.10 – 1.15** | +10-15% de velocidad. Es el cambio más impactante para el ritmo percibido. |
| **Stability** | 0.35 – 0.45 | **0.25 – 0.35** | Más baja = más variación prosódica natural entre frases. |
| **Similarity Boost** | 0.80 – 0.85 | **0.75 – 0.80** | Ligeramente más bajo para dar más margen de expresividad. |
| **Style** | 0.20 – 0.30 | **0.45 – 0.55** | Este era el problema principal. Subir el Style añade energía y dinamismo. |
| **Speaker Boost** | ON | **ON** | Sin cambio. |

**Modelo recomendado:** Cambiar a **Eleven Multilingual v2.5** o **Eleven Flash v2.5** — tienen prosody más natural y responden mejor al Speed.

> ⚠️ **Importante:** Probar primero con Speed 1.10. Si sigue sonando lento, subir a 1.15. No superar 1.20 — se pierde la articulación en consonantes del castellano.

### Versión APROBADA (28-05-2026) — usar a partir del Video 02

| Parámetro | Valor |
|---|---|
| Voz | Voz única creada con Voice Design (28-05-2026) |
| Speed | **1.11** |
| Stability | **0.30** (30%) |
| Similarity Boost | **0.50** (50%) |
| Style | **0.50** (50%) |
| Speaker Boost | — (confirmar si aparece en interfaz) |
| Modelo | **Eleven Multilingual v2** |

> ⚠️ **Cambio importante respecto a la config anterior:** Similarity bajada de 0.75 → 0.50. Esto da MUCHA más libertad expresiva a la voz, ideal para los guiones frenéticos. **Riesgo:** posible inconsistencia entre fragmentos generados por separado. Generar el vídeo entero de una sola pasada si es posible.

### Consideraciones específicas con Similarity 0.50

- **Cierres reflexivos**: el último bloque del vídeo (filosófico, calmado) puede quedarse demasiado rápido con Speed 1.11. Generar el cierre por separado con Speed 1.00-1.05 si suena demasiado plano de ritmo.
- **Frases de impacto aisladas** (ej: "Coincidían." en V02): si suenan demasiado neutras, añadir `...` o reescribir con contexto adicional para forzar entonación.
- **Palabras raras / nombres propios**: si la pronunciación falla, escribirlas fonéticamente entre guiones (`Sha-ni-dar`, `acu-presión`).
- **Inhalaciones o suspiros inventados**: con Style alto + Similarity bajo a veces ElevenLabs inserta sonidos de respiración donde no toca. Regenerar el fragmento si pasa.

---

## Reglas de puntuación en el guion

ElevenLabs lee la puntuación tal como está escrita. Estas reglas garantizan que la voz suene natural sin retocar el audio manualmente.

### Pausas

> ⚠️ **REGLA NUEVA:** Reducir drásticamente el uso de `...` y párrafos en blanco separados. Cada pausa larga mata el ritmo. Reservarlas solo para 1-2 momentos de máximo impacto por video.

| Efecto deseado | Cómo escribirlo en el guion |
|---|---|
| Pausa cortísima (énfasis) | Coma `,` |
| Pausa normal (cambio de idea) | Punto `.` |
| Pausa dramática (usar con moderación) | `...` — máximo 3-4 veces por video |
| Pausa de impacto máximo (1 vez por video) | Frase sola en su párrafo. Una sola. |
| ~~Punto + línea en blanco~~ | **Eliminado del uso habitual** — ralentiza demasiado |

### Énfasis y tono

| Efecto deseado | Cómo escribirlo |
|---|---|
| Énfasis fuerte en palabra | MAYÚSCULAS en esa palabra |
| Pregunta retórica | Terminar con `?` (ElevenLabs sube el tono) |
| Tono bajando (cierre reflexivo) | Frase corta + punto final |
| Aceleración narrativa | Frases muy cortas seguidas sin pausas largas |
| Desaceleración (momento clave) | Frase + pausa + frase corta de impacto |

### Ejemplo de puntuación aplicada

```
Esta noche, cuando el sol se ponga, vas a encender una luz.

No vas a pensarlo ni un segundo.

Pero durante el 99,9% de la historia humana... esa opción no existía.

Cuando oscurecía, el mundo se apagaba.

COMPLETAMENTE.
```

---

## Tono por sección del video

Cada video tiene tres fases emocionales. La voz debe reflejarlas:

| Sección | Minuto aprox. | Tono de voz | Ritmo |
|---|---|---|---|
| **Hook** (gancho) | 0:00 – 0:45 | Íntimo pero con energía. Como revelando algo urgente. | **Rápido-medio**, solo 1-2 pausas dramáticas |
| **Desarrollo** (ciencia) | 0:45 – 6:00 | Curioso, energético, casi emocionado. | **Rápido**, sin pausas innecesarias |
| **Cierre** (reflexión) | 6:00 – fin | Calmado, filosófico. El único momento que puede ser lento. | Medio-lento, con 1-2 pausas al final |

---

## Checklist antes de exportar cada audio

- [ ] Voz generada con los parámetros de la tabla "Versión aprobada"
- [ ] Escuchar completo antes de exportar — detectar palabras que soenen raras
- [ ] Si una frase suena mal: reescribir la puntuación (no regenerar igual)
- [ ] Volumen normalizado a -14 LUFS (estándar YouTube)
- [ ] Sin clipping en ningún momento
- [ ] Silencio al inicio y al final del audio (0.5 segundos)

---

## Texto de prueba para selección de voz

Usar este fragmento exacto para comparar candidatas. Es representativo del tono, ritmo y puntuación del canal:

```
Esta noche, cuando el sol se ponga, vas a encender una luz.

No vas a pensarlo ni un segundo.

Pero durante el 99,9% de la historia humana... esa opción no existía.

Cuando oscurecía, el mundo se apagaba.

COMPLETAMENTE.

¿Qué hacían tus ancestros?

La respuesta cambia todo lo que crees saber sobre el sueño.
```

---

## Historial de cambios

| Fecha | Cambio | Motivo |
|---|---|---|
| 20 mayo 2026 | Creación del documento | Setup inicial del canal |
| 27 mayo 2026 | Speed +10-15%, Style 0.20→0.45, Stability 0.35→0.25, reglas de puntuación revisadas, tabla de ritmo por sección actualizada | Feedback de viewers: voz monótona y ritmo muy lento |
| 28 mayo 2026 | Valores definitivos: Speed 1.11, Stab 0.30, Sim 0.50, Style 0.50, Multilingual v2. Bajada de Similarity 0.75→0.50 para máxima expresividad. | Validación post-pruebas. Aplicar desde V02. |
