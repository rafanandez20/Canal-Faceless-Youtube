# Prompt Maestro — Generación de Imágenes

**Herramienta:** Google Labs Flow con modelo Nano Banana 2
**Referencia de estilo:** Imagen 1 del guion_01 (stickman entre farmacia y cajón de ibuprofeno)
**Estado:** Prompt canónico. No modificar sin consenso.

---

## CÓMO USAR

1. Abrir Google Labs Flow con modelo Nano Banana 2
2. Subir la imagen 1 del guion_01 como referencia de estilo
3. Identificar el TIPO de imagen en `imagenes_guion_01.md` (TEXTO / ICONO / ESCENA)
4. Copiar el prompt correspondiente a ese tipo (ver abajo)
5. Sustituir `[DESCRIPCIÓN]` por la columna "Descripción visual" de la fila correspondiente
6. Generar

---

## PROMPT TIPO: TEXTO

Usar para imágenes donde el protagonista es una frase o palabra en pantalla.

```
Using the attached reference image as the exact visual style to replicate, generate this image:

[DESCRIPCIÓN]

IMAGE TYPE: clean text card.

COMPOSITION RULES:
- Pure white background
- Large bold text, centered
- Simple sans-serif font
- Text occupies 40-60% of the image width
- If there is a small stickman or icon, it is tiny and placed in a corner only
- No decoration, no borders, no frames
- Lots of empty white space around the text

VISUAL STYLE (identical to reference):
- Thick black lines for any drawn element
- Flat soft colors if any color is used
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
- Fondo blanco o muy minimalista
- Sin escenario elaborado, solo los elementos mínimos que den contexto
- El elemento principal ocupa el 50-70% del encuadre
- Si hay texto en el entorno (cartel, etiqueta), una sola palabra en español

ESTILO VISUAL (mantener igual que la referencia):
- Stickman con cabeza redonda blanca, ojos grandes simples, manos negras redondas
- Líneas negras gruesas
- Expresión facial que comunique la emoción de la escena
- Colores planos y suaves, pocos colores
- Aspecto de dibujo rápido hecho a mano
- Intencionalmente simple y ligeramente ridículo

TEXTO EN IMAGEN:
- Solo si es un cartel o etiqueta que forma parte del entorno visual
- Una palabra máximo, en español/castellano
- Sin subtítulos, sin captions, sin frases del guion

NO incluir:
- Más de un personaje principal
- Fondos detallados
- Múltiples objetos
- Composiciones tipo cómic o infografía
- Texto en inglés

Single clean icon scene, one focal element, minimal composition.
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
- Mucho espacio vacío, fondos minimalistas
- Los elementos secundarios son simples y reducidos al mínimo
- Si hay texto en el entorno (cartel, letrero), máximo 1-2 palabras en español

ESTILO VISUAL (mantener igual que la referencia):
- Stickman con cabeza redonda blanca, ojos grandes simples, manos negras redondas
- Líneas negras gruesas en todos los elementos
- Expresiones faciales que comuniquen la emoción de la escena
- Colores planos y suaves, paleta reducida
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
- Estética Pixar, anime o meme

Single clean narrative scene, minimal composition, no comic panel layout.
```

---

## Referencia rápida

| Tipo | Cuándo usarlo | Protagonista |
|------|---------------|--------------|
| TEXTO | Frases de impacto, palabras sueltas, listas | La palabra o frase |
| ICONO | Un stickman haciendo algo, un objeto, un símbolo | Un único elemento |
| ESCENA | Momentos narrativos, revelaciones, contexto | 2-3 elementos con jerarquía |
