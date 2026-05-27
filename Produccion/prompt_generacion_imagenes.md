# Prompt Maestro — Generación de Imágenes

**Herramienta:** Google Labs Flow con modelo Nano Banana 2
**Referencia de estilo:** Imagen 1 del guion_01 (stickman entre farmacia y cajón de ibuprofeno)
**Estado:** Prompt canónico. No modificar sin consenso.
**Última actualización:** 27 de mayo de 2026 — nuevas reglas de color y fondo.

---

## REGLAS GLOBALES DE COLOR Y FONDO ⚠️ OBLIGATORIAS EN TODOS LOS VIDEOS

Estas reglas se aplican a TODAS las imágenes del canal sin excepción. Incluirlas siempre en cualquier prompt.

### Regla de color
- **Máximo 5 colores por escena** (contando el negro de los contornos y el color del fondo)
- Colores **planos y sólidos** — sin gradientes, sin sombras, sin texturas
- Estilo **"dibujo coloreado vago"**: el color puede salirse ligeramente de los contornos, como coloreado a mano con rotuladores con prisa — no perfectamente rellenado

### Regla de fondo
El fondo de cada imagen debe reflejar el contexto del momento del guion. Nunca fondo blanco puro excepto en tarjetas TEXTO puras.

| Contexto del guion | Fondo | Suelo/Detalle |
|---|---|---|
| Exterior de día | Azul cielo suave | Verde suave (hierba) |
| Exterior de noche | Azul oscuro / índigo | Marrón oscuro |
| Interior (casa, habitación) | Amarillo suave / beige | Suelo beige o marrón claro |
| Cueva / prehistoria | Marrón tierra / naranja oscuro | Tierra, piedra gris |
| Laboratorio / ciencia | Gris muy claro / blanco roto | Detalles azul suave |
| Peligro / drama / tensión | Rojo muy suave o naranja suave | — |
| Agua / océano / río | Azul medio | Azul más oscuro abajo |
| Médico / farmacia | Blanco roto | Detalles verde claro |

### Texto de referencia para incluir en todos los prompts de color
```
COLOR AND BACKGROUND RULES (mandatory):
- Maximum 5 flat solid colors total in the scene (including black outlines and background)
- No gradients, no shadows, no textures — flat solid fills only
- Coloring style: slightly rough, like hand-colored with markers in a hurry (color may slightly overflow contour lines)
- Background: [DESCRIBIR EL CONTEXTO DEL GUION — ej: "soft blue sky with light green ground" / "dark indigo night sky" / "warm beige interior wall"]
- Simple colored background based on the script context, not white
```

---

## CÓMO USAR

1. Abrir Google Labs Flow con modelo Nano Banana 2
2. Subir la imagen 1 del guion_01 como referencia de estilo
3. Identificar el TIPO de imagen (TEXTO / ICONO / ESCENA)
4. Copiar el prompt correspondiente a ese tipo (ver abajo)
5. Sustituir `[DESCRIPCIÓN]` por la descripción visual de la imagen
6. Sustituir `[CONTEXTO DE FONDO]` con el contexto del guion para esa imagen
7. Generar

---

## PROMPT TIPO: TEXTO

Usar para imágenes donde el protagonista es una frase o palabra en pantalla.

```
Using the attached reference image as the exact visual style to replicate, generate this image:

[DESCRIPCIÓN]

IMAGE TYPE: clean text card.

COMPOSITION RULES:
- Simple flat-colored background (very light, low saturation) — NOT pure white
- Large bold text, centered, dark color for contrast
- Simple sans-serif font
- Text occupies 40-60% of the image width
- If there is a small stickman or icon, it is tiny and placed in a corner only
- No decoration, no borders, no frames
- Background color: [CONTEXTO DE FONDO — ej: "very light warm beige" / "very pale blue"]

COLOR AND BACKGROUND RULES (mandatory):
- Maximum 5 flat solid colors total in the scene (including black outlines and background)
- No gradients, no shadows, no textures — flat solid fills only
- Coloring style: slightly rough, like hand-colored with markers in a hurry (color may slightly overflow contour lines)
- Background: simple flat light color that matches the script context — NOT white

VISUAL STYLE (identical to reference):
- Thick black lines for any drawn element
- Flat solid colors only
- Simple educational animation look
- Intentionally simple and slightly ridiculous

⚠️ CRITICAL TEXT RULES — READ CAREFULLY:
The text to display is written below between triple asterisks.
You MUST reproduce it EXACTLY as written.
Do NOT translate it. Do NOT replace any word. Do NOT modify spelling.
The text is in Spanish. Reproduce it letter by letter.
If a word looks like an English word, it is NOT English — it is Spanish. Do not translate it.
Reproducing the exact text is the most important rule in this prompt.

***[AQUÍ PEGA EL TEXTO EXACTO QUE DEBE APARECER EN LA IMAGEN]***

The text between the triple asterisks above is the ONLY text allowed in the image.
Do not add any other words, subtitles, captions, or labels.
Do NOT include quotation marks of any kind (" " ' ' « ») around the text or anywhere in the image.

DO NOT include:
- Multiple characters
- Elaborate backgrounds
- Comic or infographic layouts
- English text of any kind
- Any word not present in the triple asterisks above

Single clean text card, minimal composition.
```

---

## PROMPT TIPO: ICONO

Usar para imágenes con un solo stickman haciendo una acción clara, o un objeto/símbolo único.

```
Usando la imagen de referencia adjunta como guía de estilo, genera esta imagen:

[DESCRIPCIÓN]

TIPO DE IMAGEN: icono simple, un único elemento visual protagonista.

REGLAS DE COMPOSICIÓN:
- Un solo personaje o un solo objeto como foco absoluto
- Centrado en la imagen con mucho espacio vacío alrededor
- Fondo coloreado simple acorde al contexto del guion (ver reglas de color abajo)
- Sin escenario elaborado, solo los elementos mínimos que den contexto
- El elemento principal ocupa el 50-70% del encuadre
- Si hay texto en el entorno (cartel, etiqueta), una sola palabra en español

REGLAS DE COLOR Y FONDO (obligatorias):
- Máximo 5 colores planos y sólidos en toda la imagen (incluyendo negro de contornos y color de fondo)
- Sin gradientes, sin sombras, sin texturas — rellenos planos únicamente
- Estilo de coloreado: ligeramente vago/descuidado, como coloreado a mano con rotuladores rápido — el color puede salirse un poco de los contornos
- Fondo: [CONTEXTO DE FONDO — ej: "cielo azul suave con suelo verde claro" / "interior cálido beige" / "noche azul oscuro"]
- El fondo refleja el entorno del momento del guion, nunca blanco puro

ESTILO VISUAL (mantener igual que la referencia):
- Stickman con cabeza redonda, ojos grandes simples, manos negras redondas
- Líneas negras gruesas
- Expresión facial que comunique la emoción de la escena
- Colores planos y sólidos, paleta máximo 5 colores
- Aspecto de dibujo rápido hecho a mano
- Intencionalmente simple y ligeramente ridículo

TEXTO EN IMAGEN:
- Solo si es un cartel o etiqueta que forma parte del entorno visual
- Una palabra máximo, en español/castellano
- Sin subtítulos, sin captions, sin frases del guion

NO incluir:
- Más de un personaje principal
- Fondos detallados o fotorrealistas
- Múltiples objetos
- Composiciones tipo cómic o infografía
- Texto en inglés
- Gradientes o sombras

Single clean icon scene, one focal element, colored contextual background.
```

---

## PROMPT TIPO: ESCENA

Usar para imágenes narrativas con contexto, varios elementos o momento ancla del guion.

```
Usando la imagen de referencia adjunta como guía de estilo, genera esta imagen:

[DESCRIPCIÓN]

TIPO DE IMAGEN: escena narrativa, momento ancla del video.

REGLAS DE COMPOSICIÓN:
- Puede haber 2-3 personajes o elementos si la escena lo requiere
- El entorno da contexto pero sin sobrecargarse
- Jerarquía visual clara: personaje principal en primer plano o centro
- Los elementos secundarios son simples y reducidos al mínimo
- Si hay texto en el entorno (cartel, letrero), máximo 1-2 palabras en español

REGLAS DE COLOR Y FONDO (obligatorias):
- Máximo 5 colores planos y sólidos en toda la imagen (incluyendo negro de contornos y color de fondo)
- Sin gradientes, sin sombras, sin texturas — rellenos planos únicamente
- Estilo de coloreado: ligeramente vago/descuidado, como coloreado a mano con rotuladores rápido — el color puede salirse un poco de los contornos
- Fondo: [CONTEXTO DE FONDO — ej: "cielo azul suave con suelo verde claro" / "cueva marrón tierra con detalles naranja" / "interior beige cálido"]
- El fondo refleja el entorno del momento del guion, dibujado de forma simple y plana

ESTILO VISUAL (mantener igual que la referencia):
- Stickman con cabeza redonda, ojos grandes simples, manos negras redondas
- Líneas negras gruesas en todos los elementos
- Expresiones faciales que comuniquen la emoción de la escena
- Colores planos y sólidos, paleta máximo 5 colores
- Aspecto de animación educativa simple, hecha a mano
- Intencionalmente simple y ligeramente ridículo
- Todos los personajes deben tener el mismo diseño de stickman que la referencia

TEXTO EN IMAGEN:
- Solo si es un cartel, letrero o etiqueta que forma parte del entorno
- Máximo 2 palabras, en español/castellano
- Sin subtítulos, sin captions, sin frases del guion

NO incluir:
- Fondos fotorrealistas o detallados
- Composiciones tipo cómic con viñetas
- Infografías o esquemas
- Más de 3 elementos principales
- Texto en inglés
- Gradientes, sombras o texturas
- Estética Pixar, anime o meme

Single clean narrative scene, colored contextual background, no comic panel layout.
```

---

## Referencia rápida

| Tipo | Cuándo usarlo | Protagonista |
|------|---------------|--------------|
| TEXTO | Frases de impacto, palabras sueltas, listas | La palabra o frase |
| ICONO | Un stickman haciendo algo, un objeto, un símbolo | Un único elemento |
| ESCENA | Momentos narrativos, revelaciones, contexto | 2-3 elementos con jerarquía |
