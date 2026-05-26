# Estado del Proyecto — Canal Kronyt
**Última actualización:** 26 mayo 2026  
**Estado:** 🟢 Activo — Vídeo 1 publicado

---

## QUÉ ES ESTE PROYECTO

Canal de YouTube faceless (sin cara) en español, estilo divulgación científica. Animación stickman 2D, voz generada con IA, guiones escritos con IA. Sin cámara, sin locutor humano, sin estudio.

El modelo replica en español el canal angloparlante **Zenn (@Zenn0009)**, que con 11 vídeos alcanzó 119k suscriptores y un viral de 7,3 millones de vistas.

**Nicho:** Historia humana, prehistoria, evolución, experimentos científicos, misterios del cerebro.  
**Idioma:** Español de España (castellano).  
**Nombre del canal:** Kronyt *(provisional)*.

---

## POR QUÉ VALE MÁS HACERLO CON ESTE SISTEMA QUE SOLO

Antes de existir la IA, un canal así requería: guionista, locutor, editor, miniaturero, community manager y un manager que coordinara todo. Coste: 200-500 € por vídeo mínimo, con meses de aprendizaje.

Con este sistema:

| Lo que antes costaba | Lo que cuesta ahora |
|---|---|
| Guionista profesional | Claude — 18 €/mes ilimitado |
| Locutor con estudio | ElevenLabs — ~1-2 €/vídeo |
| Editor de vídeo | CapCut Pro — 23,99 €/mes o delegado a 10 €/vídeo |
| Miniaturero | Google Labs Flow — incluido en cuenta Google |
| Investigador de temas | Claude + análisis de canales de referencia |
| **Total por vídeo antes** | **200-500 €** |
| **Total por vídeo ahora** | **12-15 €** |

Pero la ventaja no es solo económica. Este sistema acumula conocimiento:

- **Cada vídeo alimenta el siguiente** — los aprendizajes quedan documentados
- **La guía es replicable** — cualquier persona que la lea puede ejecutar el proceso
- **El análisis está hecho** — se sabe qué títulos funcionan, qué duración, qué estructura, con datos reales
- **Las herramientas están configuradas** — prompts, parámetros de voz, estilo visual, todo definido
- **Los errores están anticipados** — se sabe qué no hacer antes de cometerlo (patrones que fracasan documentados con datos)

Sin este sistema, una persona sola tardaría 6-12 meses en descubrir lo que aquí está ya documentado.

---

## ESTRUCTURA DE ARCHIVOS DEL PROYECTO

```
Canal Viral Youtube/
│
├── GUIA_COMPLETA_CANAL_FACELESS.md        ← Manual completo del negocio y producción
├── ESTADO_PROYECTO.md                      ← Este archivo — resumen y log de progreso
│
├── InfoCanalAnalizado/
│   └── analisis_canal_zenn.md              ← Análisis detallado del canal de referencia
│
├── tendenciasespañol/                      ← Investigación de nichos y tendencias
│   ├── 00_resumen_ejecutivo.md
│   ├── 01_google_trends.md
│   ├── 02_canales_competencia.md
│   ├── 03_preguntas_foros.md
│   ├── 04_eventos_recientes.md
│   ├── 05_lista_20_temas.md
│   └── 99_fuentes.md
│
├── Produccion/
│   ├── 15_ideas_videos.md                  ← 15 ideas con patrones, ganchos y urgencia
│   ├── estilo_visual_stickman.md           ← Prompts y reglas de estilo visual
│   ├── voz_elevenlabs_config.md            ← Configuración completa de voz IA
│   ├── prompt_generacion_imagenes.md       ← Prompts para imágenes de los vídeos
│   ├── configuracion_canal_youtube.md      ← Nombre, banner, descripción, keywords
│   ├── miniaturas-canal.md                 ← Guía y prompt maestro de miniaturas
│   │
│   ├── Video01/                            ← Todo lo del primer vídeo
│   │   ├── guion_01_v2_dolor_prehistorico.md
│   │   ├── info-postear-videoYT.md         ← Título, descripción, tags, checklist
│   │   ├── short_video01.md                ← Todo sobre el Short del vídeo 1
│   │   ├── comentarios_video01.md          ← Respuestas a comentarios + pinned
│   │   ├── prompts_guion_01.md
│   │   ├── imagenes_guion_01.md
│   │   └── Imagenes-Video1/
│   │
│   └── guiones/                            ← Carpeta de guiones
│
└── Transcripciones/
    └── TranscripcionesZenn.md              ← Transcripciones de vídeos analizados
```

---

## QUÉ TIENE DOCUMENTADO EL PROYECTO

### 📐 Estrategia y modelo de negocio
- Tipos de canal (evergreen, noticias, híbrido, tendencia) con ventajas y diferencias
- Cómo funciona la monetización de YouTube y el RPM
- Estrategia de escalabilidad (3-5 canales para estabilidad)
- Trust Score y cómo abrir canales nuevos con aged channels (hprofiles.com)

### 🎯 Análisis del canal de referencia (Zenn)
- Datos de rendimiento de todos sus vídeos (vistas, duración, fecha)
- Patrones de títulos que funcionan vs. los que fallan (con datos reales)
- 6 estructuras de títulos probadas (A, B, C, D, E, F) con vistas documentadas
- Errores a evitar (demostrados con datos reales del canal)
- Duración óptima de vídeo (8:00 – 8:50 min)

### 💡 Ideas de contenido
- 15 ideas completas con título, gancho de 30 segundos, fuente académica y urgencia
- Calendario sugerido de publicación para los primeros 8 vídeos
- Regla: ningún patrón repetido más de 2 veces en los primeros 15 vídeos

### 🎙️ Producción
- Prompt base para guiones con Claude
- Estructura de cada vídeo (hook → desarrollo → cierre reflexivo)
- Configuración exacta de ElevenLabs (Stability, Similarity Boost, Style, Speaker Boost)
- Reglas de puntuación en el guion para controlar la voz IA
- Mezcla de audio (volúmenes en dB por sección)
- Fuentes de música libre de derechos

### 🎨 Estilo visual
- Prompt maestro para imágenes del vídeo (estilo ultra-simple, fondo blanco)
- Prompt maestro para miniaturas (estilo cueva, con color y ambiente)
- Diferencia clara entre imágenes del vídeo y miniaturas
- Paleta de colores canónica de las miniaturas
- Personalización del stickman por época y rol

### 📺 Canal de YouTube
- Nombre, imagen de perfil, banner (con prompt)
- Descripción completa lista para copiar y pegar
- Keywords del canal (campo invisible para el algoritmo)
- Categoría correcta (Ciencia y tecnología, no Educación)
- Horario óptimo de publicación

### 📊 Publicación y SEO
- Checklist completa antes de publicar
- Estructura de descripción de cada vídeo
- Cómo usar capítulos/timestamps para SEO
- Estrategia de Shorts (cuándo publicar, cómo hacer el título, qué clip usar)
- Reglas de títulos para Shorts (sin #Shorts en título, enlace nativo al vídeo largo)

### 💬 Comunidad
- Cómo responder comentarios para maximizar engagement
- Tono correcto (cercano, no corporativo)
- Prioridad de respuestas (comentarios más largos primero)
- Ventana crítica: responder en las primeras 2 horas

---

## LOG DE PROGRESO

### ✅ Mayo 2026

| Fecha | Hito |
|---|---|
| 20 mayo 2026 | Análisis completo del canal Zenn |
| 20 mayo 2026 | 15 ideas de vídeos documentadas con patrones |
| 20 mayo 2026 | Configuración de voz ElevenLabs |
| 20 mayo 2026 | Estilo visual stickman definido |
| 23 mayo 2026 | Configuración del canal YouTube completada |
| 23 mayo 2026 | Guión vídeo #01 finalizado (v2) |
| 24 mayo 2026 | Vídeo #01 publicado en YouTube |
| 24 mayo 2026 | Miniatura vídeo #01 aprobada |
| 26 mayo 2026 | Guía completa del canal redactada |
| 26 mayo 2026 | Respuestas a comentarios vídeo #01 documentadas |
| 27 mayo 2026 | Short vídeo #01 programado para publicación (19:30h) |

---

## PRÓXIMOS PASOS

- [ ] Publicar Short vídeo #01 (27 mayo, 19:30h)
- [ ] Empezar producción vídeo #02 — *¿Y si NOSOTROS somos los neandertales?*
- [ ] Validar voz ElevenLabs definitiva y rellenar tabla de parámetros aprobados
- [ ] Subir proyecto a GitHub para acceso compartido con el equipo

---

## MÉTRICAS A SEGUIR (actualizar con cada vídeo)

| Vídeo | Vistas (7 días) | Vistas (30 días) | CTR | Retención media | Suscriptores ganados |
|---|---|---|---|---|---|
| #01 — Dolor prehistórico | — | — | — | — | — |

---

## BENCHMARKS DE REFERENCIA

| Métrica | Referencia (canal establecido) |
|---|---|
| CTR objetivo | >8% (excelente: >12%) |
| Retención media | >40% en vídeos de 8 min |
| Duración promedio de visualización | ~7:30 en vídeos de 8:30 |
| Vídeos hasta primer viral | ~78 vídeos (dato canal de referencia) |
| Ingresos canal establecido | 100-300 €/día (conservador) |
