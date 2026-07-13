<p align="center">
  <img src="assets/Da linha ao codigo.png" alt="Da Linha ao Gráfico" width="500">
</p>

<h1 align="center">🎙️ Da Linha ao Gráfico</h1>

<p align="center">
  Um podcast sobre tecnologia da informação com foco em dados, feito com apoio de IA (Gemini) para roteirização e produção dos episódios.
</p>

---

## Sobre o projeto

Este repositório reúne os materiais de produção do podcast **Da Linha ao Gráfico**, voltado a profissionais e entusiastas da área de dados. Os episódios abordam as principais tecnologias do mercado e explicam conceitos como sistemas multi-agentes de forma leve e acessível.

## Estrutura

```
├── assets/                 # Imagens e artes do podcast
├── src/
│   └── prompts/
│       └── gemini.md       # Prompts usados para gerar título e roteiro dos episódios
└── output/
    └── podcast_ep1.mp3     # Episódios gerados
```

## Como funciona

Os prompts em [`src/prompts/gemini.md`](src/prompts/gemini.md) são usados no Gemini para:

1. **Título** — gerar sugestões de título e subtítulo para o episódio, com trocadilhos voltados ao público de dados/TI.
2. **Conteúdo** — gerar o roteiro do episódio, com linguagem coesa e envolvente para diferentes públicos.

Os episódios finais são salvos na pasta [`output/`](output/).

## Tecnologias

- **Gemini** — geração do título, roteiro e da imagem de capa do podcast.
- **ElevenLabs** — geração do áudio a partir do roteiro, usando a skill de text-to-speech.
