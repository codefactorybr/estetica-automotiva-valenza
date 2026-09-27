# Valenza Garage — site

Site estático, sem build. `index.html` é autocontido (runtime, React, fontes, vídeo e imagens principais embutidos). As imagens de Serviços, Antes/Depois, Processo e da galeria ampliada carregam de `assets/img/`.

## Estrutura
```
index.html
vercel.json
README.md
assets/favicon.png
assets/og-image.jpg
assets/img/*.jpg, logo-v.png
```

## Vercel
Framework: Other · Build Command: vazio · Output Directory: `.`
Suba o conteúdo desta pasta na raiz do repositório (inclua `assets/img/`).

Depois do domínio definido, troque `assets/og-image.jpg` no `og:image` por URL absoluta.

Fonte editável: `Valenza Garage.dc.html` (projeto de design). Não edite `index.html` à mão; gere de novo a partir do fonte.
