# Skill de edición · Lobo de Wall Street

Edita reels en el estilo de Jordan Belfort: él a cámara (celular casual o estudio), subtítulo blanco bold, frase clave amarilla que se escribe
letra a letra, objetos 3D y cifras sobre la cabeza, lista numerada, fotos insertadas, clips de película y tarjeta de perfil «Follow».
Entrenada con los 20 videos de este repositorio (392 escenas; los videos 2, 3 y 4 son anuncios de «Tone» y quedaron fuera del estilo).

## Instalar
1. Descarga `lobo-de-wall-street-editing.zip` (botón **Download raw file**).
2. **Claude:** Ajustes → Capacidades → Skills → *Subir skill*. **Claude Code:** descomprime en `~/.claude/skills/lobo-de-wall-street-editing/`.
   **ChatGPT / Gemini:** sube el zip al chat y escribe «Lee EMPIEZA_AQUI.md y sigue SKILL.md».
3. Sube tu clip: «Edita este video con la skill lobo-de-wall-street-editing».

## Qué trae
`SKILL.md`, `REGLAS_GENERALES.md`, `docs/` (RULEBOOK, EDIT_LOGIC, FORMATOS, Katana, Edit Studio), `library/` (392 ejemplos con hoja de fotogramas),
`references/` (desglose por video), `system/` (motor de render, subtítulos, sonido, panel A/B/C), `plugins/edit-studio/`. Ejemplo en `ejemplo/`.
