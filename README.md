# Nōmadia – Ejercicio 2: Vídeos

Web de viajes con un vídeo propio integrado con **Video.js**. El vídeo se puede ver con audio en español o en inglés y con subtítulos en ambos idiomas. Se trata de un ejercicio de clase para implementar fotos y videos comprimidos, ademas de subtitulos y audio.

## Cómo verlo

El vídeo usa HLS, así que la web tiene que abrirse desde un servidor (no con doble clic en el html):

La forma mas sencilla
- Con la extensión **Live Server** de VS Code, abriendo `Web/index.html`.

## Estructura

```
Web/
├── index.html
├── style.css
├── Fotos comprimidas/   fotos de los destinos
├── Audio/               locución original en castellano e inglés
├── videos/              vídeo en HLS y portada
└── subtitulos/          subtítulos WebVTT
```

## Tecnologías

HTML5, CSS, JavaScript, Video.js 8, HLS y WebVTT.
