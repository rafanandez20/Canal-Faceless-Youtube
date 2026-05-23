# Configuración del Canal de YouTube — Kronyt
**Última actualización:** 23 de mayo de 2026
**Canal de referencia replicado:** Zenn (@Zenn0009)

---

## DECISIONES DE IDENTIDAD VISUAL

### Por qué NO copiamos la imagen de Zenn
Zenn usa silueta oscura sobre fondo rojo. Copiarla exactamente supone dos riesgos:
1. Cualquier espectador que haya visto Zenn lo identificará como copia directa.
2. Se pierde la ventaja diferencial de Kronyt: el stickman como identidad visual propia.

### Lógica adoptada
- **Formato de los vídeos:** replicar a Zenn al 100% (estructura, hooks, duración, temas).
- **Identidad visual del canal:** misma energía (anónimo, minimalista, misterioso) pero ejecución propia.
- **El stickman es la marca de Kronyt.** En los vídeos de Zenn también hay stickman, pero su canal no lo usa como identidad. Nosotros sí.

---

## NOMBRE DEL CANAL

**Nombre actual:** Kronyt *(provisional — puede cambiar)*

**Regla para el nombre:** Una palabra, sin describir el contenido, pronunciable en cualquier idioma. El nombre no debe anclar el canal a ningún nicho concreto.

Otras opciones valoradas: Axon, Ordo, Yermo, Aión.

---

## 1. IMAGEN DE PERFIL DEL CANAL

**Especificaciones técnicas:**
- Tamaño: 800×800 px mínimo
- Formato: PNG con fondo negro sólido (NO transparente — YouTube rellena los transparentes de blanco y destruye el contraste)
- YouTube lo recorta en círculo al mostrarlo
- Debe ser reconocible a 32×32 px

**Prompt:**
```
flat 2D cartoon stickman, centered in a perfect square frame, solid black background, white character. A single bold stickman with a large round head, thick white outlines, big circular eyes with small black pupils, small straight mouth, stick limbs. The character is standing upright looking directly forward, slightly tilted head. One single large white question mark to the right of the character, same thickness as the stickman outlines. Nothing else. No accessories, no scenario, no historical references, no text. Extremely high contrast: pure white on pure black. The design must be fully readable and recognizable at 32x32 pixels. Icon-level simplicity. Bold, clean, memorable.

Negative prompt: realistic, 3D, cinematic, Pixar, anime, gradients, shadows, color fills, multiple characters, background elements, text, letters, numbers, weapons, clothing, accessories, gray tones, low contrast, detailed textures
```

---

## 2. BANNER DEL CANAL

**Especificaciones técnicas:**
- Tamaño total: 2560×1440 px
- Zona segura visible en todos los dispositivos: 1546×423 px (franja central)
- Los laterales se cortan en móvil y tablet — todo lo importante va en el centro
- Formato: PNG o JPG

**Composición esperada:**
```
| [negro vacío]   [stickman ?]   KRONYT                    [negro vacío] |
|                                Una pregunta nueva cada semana           |
```

**Prompt:**
```
wide horizontal banner, solid black background, flat 2D cartoon style. Centered composition within the middle 1546x423 pixel safe zone. On the left side of center: a small bold white stickman character (same style as profile — large round head, thick white outlines, big circular eyes, small straight mouth) standing upright with one large white question mark floating beside it. On the right side of center: the word "Kronyt" in large bold clean white sans-serif block letters, and directly below it in much smaller white text: "Una pregunta nueva cada semana". All elements white on pure black. Minimalist, high contrast, no decorative elements, no borders, no gradients, no color, no background texture. The far left and far right edges of the banner are empty black space. Everything important is in the horizontal center strip.

Negative prompt: realistic, 3D, cinematic, colorful, gradients, decorative borders, complex backgrounds, multiple characters, historical scenes, textures, gray tones, low contrast, Pixar, anime
```

---

## 3. DESCRIPCIÓN DEL CANAL

**Dónde se pega:** YouTube Studio → Personalización → Información básica → Descripción

**Límite:** 1000 caracteres. Esta versión tiene ~985.

**Texto listo para copiar y pegar:**
```
¿Qué hacían los humanos prehistóricos cuando algo les dolía? ¿Por qué tu cerebro no puede recordar tus primeros años? ¿Y si los neandertales no eran inferiores, solo diferentes? ¿Qué pasa realmente cuando morimos?

Cada semana, una pregunta sobre los orígenes humanos. Datos reales, estudios académicos verificados, sin inventar y sin más de 10 minutos. Animaciones simples. Ciencia que engancha.

→ Prehistoria y evolución humana: qué comían, cómo vivían, cómo morían
→ Experimentos científicos que cambiaron lo que sabemos del ser humano
→ Misterios de la mente y el cerebro
→ Preguntas que llevan miles de años sin respuesta y que la ciencia por fin está respondiendo

Si alguna vez te has preguntado de dónde venimos y cómo llegamos hasta aquí, este canal es para ti.

🔔 Suscríbete — un video nuevo cada semana.

#HumanosPrehistóricos #Prehistoria #EvoluciónHumana #Neandertales #CienciaCuriosa #CienciaEnEspañol #DivulgaciónCientífica #OrigenDelHombre #MisteriosCientíficos
```

**Nota SEO:** Los primeros 100-150 caracteres son los únicos que aparecen en los resultados de búsqueda de YouTube sin que el usuario haga clic. Están optimizados con las keywords más importantes del nicho.

---

## 4. KEYWORDS DEL CANAL

**Dónde se meten:** YouTube Studio → (icono engranaje abajo izquierda) Configuración → Canal → Información básica → campo "Palabras clave"

**Estas keywords son invisibles para el usuario.** Solo las usa el algoritmo de YouTube para clasificar el canal. Límite: 500 caracteres.

**Texto listo para copiar y pegar:**
```
humanos prehistóricos, evolución humana, origen del hombre, prehistoria, neandertales, ciencia curiosa, curiosidades científicas, divulgación científica, historia de la humanidad, misterios científicos, experimentos científicos, mente humana, cerebro humano, ciencia en español, animación educativa, curiosidades históricas, homo sapiens, arqueología, antropología
```

---

## NOTAS PARA FUTURAS ACTUALIZACIONES

- Si el nombre del canal cambia de Kronyt, hay que actualizar: el texto del prompt del banner y el banner generado. La descripción y las keywords no dependen del nombre.
- Los hashtags de la descripción se revisan cada 3-6 meses según qué términos están subiendo en búsquedas de YouTube España/Latinoamérica.
- Las keywords del canal se pueden ampliar conforme se publiquen más vídeos y se identifiquen nuevos términos de búsqueda con VidIQ o TubeBuddy.
