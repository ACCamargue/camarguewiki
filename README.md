# Camarguewiki: com publicar-la a GitHub Pages

1. Crea un repositori nou a GitHub (per exemple `camarguewiki`) i puja-hi tot el contingut d'aquesta carpeta (`index.html`, `data/`, `img/`).
2. Al repositori: Settings → Pages → Source: "Deploy from a branch" → branch `main`, carpeta `/ (root)` → Save.
3. Al cap d'1-2 minuts la web estarà a `https://EL-TEU-USUARI.github.io/camarguewiki/`.

## Articles
Cada article és una fila del Sheets (publicat com a CSV). Columnes:
`id, categoria_ca, categoria_cam, titol_ca, subtitol_ca, text_ca, titol_cam, subtitol_cam, text_cam, foto`

Google triga uns minuts a refrescar el Sheets publicat.

## Fotos
- Opció A (Drive): puja la foto a la carpeta Wiki, comparteix-la com a "Qualsevol persona amb l'enllaç" i enganxa l'enllaç de la foto a la columna `foto` de l'article.
- Opció B (GitHub): puja la foto a la carpeta `img/` amb el nom de l'ID (`1.png`).
- Foto de portada: posa-la a `img/inici.jpg` o canvia `HOME_IMAGE` a dalt de `index.html`.

## Format del text
Una línia curta sola en un paràgraf, sense punt final = títol de secció (si va just darrere d'un altre títol, subtítol).
`## Títol` també funciona. Llistes amb `- `. Taules: files amb `|` entre columnes (la primera fila és la capçalera). `**negreta**`, `*cursiva*` i enllaços a altres articles amb `[[id]]` o `[[id|text]]`.
