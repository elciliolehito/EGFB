# EGFB – Site do Curso de Ecoturismo e Gestão de Fauna Bravia (ISPM)

## Como testar no VS Code

1. Extraia o ficheiro `egfb-site-completo.zip`
2. Abra a pasta `egfb-site` no VS Code
3. Instale a extensão **Live Server** (recomendado)
4. Clique com o botão direito em `index.html` → **Open with Live Server**

Ou simplesmente abra o `index.html` diretamente no browser (Chrome/Firefox/Edge).

## Vídeos de fundo incluídos

- **Hero (página inicial)**: `videos/wildebeest-aerial.mp4` – manada de gnu em vista aérea
- **Secção de citação (Mia Couto)**: `videos/elephants-sunset.mp4` – elefantes ao pôr do sol
- **Secção “Vida Selvagem em Movimento”**: `videos/wildebeest-dust.mp4` – gnu ao entardecer com poeira

Os vídeos estão optimizados para web (H.264, 1280px, CRF 28) e usam `autoplay muted loop playsinline` para funcionar bem em desktop e mobile.

## Estrutura

```
egfb-site/
├── index.html
├── images/
│   ├── logos...
│   └── wildlife/          ← imagens de fauna locais
├── videos/                ← 3 vídeos de fundo
├── pages/
│   ├── modulos.html
│   ├── sobre.html
│   └── jardim-botanico.html
├── css/  (vazio – Tailwind via CDN)
└── js/   (vazio por agora)
```

## Notas

- O site usa **Tailwind CSS via CDN** (precisa de internet na primeira carga).
- Para produção, pode fazer o build offline do Tailwind se quiser.
- Páginas secundárias ainda usam algumas imagens externas (Unsplash); pode substituí-las pelas imagens da pasta `wildlife`.

Bom teste!
