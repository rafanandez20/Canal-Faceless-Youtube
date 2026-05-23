# Miniaturas del Canal — Guía de Estilo y Prompt Maestro

**Herramienta:** Google Labs Flow con modelo Nano Banana 2
**Referencia visual:** Miniatura vídeo 1 (neandertal en cueva con planta + pastilla)
**Estado:** Estilo validado. Usar siempre este documento como base.

---

## Resultado de referencia

Miniatura vídeo 1: `¿Ya tenían ibuprofeno?`
- Neandertal stickman en cueva con fuego, sosteniendo planta medicinal
- Pastilla moderna flotando junto a la abertura de la cueva
- Cielo nocturno azul oscuro con luna creciente
- Texto amarillo con contorno negro en la parte superior
- Resultado: **aprobado, calidad excelente**

---

## Diferencia importante: miniaturas ≠ imágenes del vídeo

Las imágenes del vídeo usan estilo ultra-simple, fondo blanco, sin color.
Las **miniaturas son diferentes**: tienen ambiente, colores y más detalle para maximizar CTR.

| | Imágenes del vídeo | Miniaturas |
|---|---|---|
| Fondo | Blanco liso | Cave/ambiente con color |
| Stickman | Ultra-simple | Con pelo, barba, ropa |
| Colores | Solo negro + algún plano | Paleta completa |
| Texto | En español con triple asterisco | En español con triple asterisco |
| Objetivo | Narrar el guion | Generar clicks |

---

## Paleta de colores canónica

| Elemento | Color |
|---|---|
| Paredes de cueva | Marrón terracota oscuro (#7a3b1e y variantes) |
| Suelo de cueva | Marrón más claro (#a0522d) |
| Fuego | Naranja (#ff6600) y amarillo (#ffcc00) |
| Cielo nocturno | Azul oscuro profundo (#0a1628) |
| Stickman | Cabeza blanca, contornos negros gruesos |
| Pelo/barba | Marrón oscuro (#3d1c02) |
| Ropa de pieles | Marrón con manchas (aspecto de piel de animal) |
| Objeto moderno | Blanco/azul claro con ligero glow |
| Texto | Amarillo brillante (#ffee00) con contorno negro grueso |

---

## Anatomía de cada miniatura

Todas las miniaturas del canal siguen esta estructura:

1. **Ambiente prehistórico** (cueva, fuego, cielo nocturno) — da contexto instantáneo
2. **Stickman neandertal** (izquierda o centro) — el personaje del canal
3. **Objeto del tema** (planta, hueso, herramienta...) — lo que sostiene o muestra
4. **Contraste moderno** (pastilla, teléfono, símbolo actual) — el giro del vídeo
5. **Texto pregunta/afirmación** (arriba, amarillo) — el hook de click

---

## Estilo del stickman en miniaturas

A diferencia del stickman ultra-simple de los vídeos, el de la miniatura tiene:
- Cabeza redonda grande, blanca, contorno negro grueso
- **Pelo** volumoso y despeinado (líneas oscuras densas sobre la cabeza)
- **Barba** dibujada (marrón/oscura, aspecto tosco)
- **Ropa de pieles**: forma irregular marrón con manchas, aspecto de animal
- Extremidades de palito (finas, negras)
- Expresión siempre exagerada: sorpresa, orgullo, confusión o miedo
- Los ojos son grandes, ligeramente caídos (expresivo pero simple)

---

## Prompt maestro (copiar y adaptar)

```
Using the attached reference image as the exact visual style to replicate, generate this image:

[DESCRIPCIÓN DE LA ESCENA ESPECÍFICA DEL VÍDEO]

IMAGE TYPE: YouTube thumbnail — colored cave environment scene, maximum CTR impact.

COMPOSITION RULES:
- Cave interior fills the background: warm dark brown rocky walls with simple rough line texture
- Stickman neandertal [posición: left/center], [acción]
- Small campfire at the bottom center: orange and yellow flat flames
- Cave opening [posición: right/top-right]: dark blue night sky, simple crescent moon
- [Objeto moderno o contraste]: white/blue, slight glow, [posición]
- Text at the VERY TOP of the image, large and bold
- Wide horizontal composition (16:9)

COLOR PALETTE:
- Cave walls: warm dark brown and terracotta (#7a3b1e)
- Cave floor: lighter brown (#a0522d)
- Fire: bright orange (#ff6600) and yellow (#ffcc00)
- Night sky: deep dark blue (#0a1628)
- Stickman head: white with thick black outline
- Hair and beard: dark brown, messy
- Animal skin clothing: brown with spots/patches
- Modern object: white with blue tint, soft glow
- Text: bright yellow (#ffee00) with thick black outline

STICKMAN STYLE:
- Large round white head with thick black outline
- Big expressive eyes, slightly droopy — surprised or proud expression
- Voluminous messy dark hair on top of head
- Simple dark beard drawn on the lower face
- Animal skin outfit: irregular brown shape with spot markings
- Thin stick arms and legs, small round black hands
- Flat 2D cartoon look, hand-drawn aesthetic
- More detailed than the video images but still intentionally simple and slightly ridiculous

TEXT RULES:
The text to display is written below between triple asterisks.
You MUST reproduce it EXACTLY as written. Do NOT translate it.
It is in Spanish. Reproduce it letter by letter.
Large, bold, bright yellow (#ffee00), thick black outline, placed at the VERY TOP of the image.

***[TEXTO DE LA MINIATURA EN ESPAÑOL]***

DO NOT include:
- White or black flat backgrounds
- Any text other than the one between triple asterisks
- Multiple stickmen (only one neandertal protagonist)
- Realistic anatomy, 3D render, anime, or Pixar style
- Quotation marks of any kind around the text

Cave YouTube thumbnail: warm brown cave, campfire center-bottom, neandertal stickman [posición], [objeto contraste], dark blue night sky, bright yellow Spanish text top.
```

---

## Checklist antes de generar

- [ ] ¿Tengo la imagen de referencia (miniatura vídeo 1) para subir a Flow?
- [ ] ¿El texto entre `***` está en español y sin comillas?
- [ ] ¿La descripción de escena incluye posición del stickman, objeto y contraste moderno?
- [ ] ¿El texto del hook es una pregunta o afirmación corta (máx 5 palabras)?

---

## Registro de miniaturas generadas

| Vídeo | Texto miniatura | Escena | Estado |
|---|---|---|---|
| #01 — Dolor prehistórico | `¿Ya tenían ibuprofeno?` | Neandertal en cueva con planta medicinal + pastilla flotante | ✓ Aprobada |
