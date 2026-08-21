# Portafolio — Mariana Caballero Beltrán

Portafolio de una sola página, en HTML/CSS/JS puro (sin frameworks, sin build).
Diseño: fondo oscuro, tipografía Space Grotesk + Inter, acentos de terminal
(JetBrains Mono) ya que el contenido es tu perfil como developer.

## Cómo verlo en tu PC (VS Code)

1. Abre la carpeta `portfolio` en VS Code (`File > Open Folder`).
2. Clic derecho sobre `index.html` → **"Open with Live Server"**
   (necesitas la extensión Live Server instalada — ver Extensions, Ctrl+Shift+X).
3. Se abre en tu navegador con recarga automática cada vez que guardas cambios.

Si no quieres instalar la extensión, también puedes simplemente hacer doble clic
en `index.html` y se abre en el navegador — solo que no tendrás recarga automática.

## Qué personalizar ya mismo

- **Sección "Projects"**: ahora mismo tiene 2 tarjetas placeholder (`empty`).
  Cuando termines el proyecto 2 (CRUD full-stack), reemplaza esa tarjeta por el
  formato de ejemplo que está comentado en el HTML (busca `<!-- Ejemplo de tarjeta -->`).
- **LinkedIn**: si creas un perfil de LinkedIn (muy recomendable para roles en EE.UU.),
  agrégalo en la sección de contacto con el mismo formato que el link de GitHub.
- **Foto**: si quieres agregar tu foto, puedo ayudarte a integrarla en el hero —
  solo dime y ajustamos el layout.

## Cómo subirlo a GitHub

Desde la terminal, dentro de la carpeta `portfolio`:

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/MarianaCabbel/portfolio.git
git push -u origin main
```

(Antes de esto, crea el repo vacío "portfolio" en github.com/new — sin README,
sin .gitignore, para que no choque con el push.)

## Cómo publicarlo gratis (Vercel)

1. Entra a vercel.com con tu cuenta de GitHub.
2. "Add New Project" → selecciona el repo `portfolio`.
3. Framework Preset: **Other** (no necesita build, es HTML plano).
4. Deploy. En ~30 segundos tienes una URL pública tipo
   `portfolio-mariana.vercel.app` que puedes poner en tu CV y LinkedIn.

Cada vez que hagas `git push`, Vercel vuelve a publicar automáticamente.
