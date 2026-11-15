# Pílulas de IA para designers · AI pills for designers

Um lugar para reunir e compartilhar o que eu aprendo sobre IA, design engineering e front-end, pensando em designers e pessoas de produto. Aqui ficam guias e artigos, em português e em inglês.

*A place to gather and share what I learn about AI, design engineering and front-end, for designers and product people. It holds guides and articles, in Portuguese and English.*

## Guias

Para fazer junto: passo a passo, prompts para copiar, checklists e erros comuns. São atualizados quando a ferramenta muda.

| Guia | Tema | Idiomas |
|---|---|---|
| Engenharia de prompts para designers | O que é, como o modelo lê um prompt, por que importa para designers e os 5 elementos de um bom prompt | [Português](guias/engenharia-de-prompts/pt.md) · [English](guias/engenharia-de-prompts/en.md) |
| Agentes e modelos do Claude | Chat × workflow × agente, como o agente atua no LLM, o que muda no prompt e como escolher entre Fable, Opus, Sonnet e Haiku | [Português](guias/agentes-e-modelos/pt.md) · [English](guias/agentes-e-modelos/en.md) |
| Vídeo de marca em motion com IA | Do briefing ao MP4: estratégia (arco e objeto-herói), design system, música na batida e conferência de quadros | [Português](guias/video-motion-com-ia/pt.md) · [English](guias/video-motion-com-ia/en.md) |
| Reel de Design Engineer com tipografia cinética | Reel de 14s em 7 cenas na batida, design e código lado a lado, música sem voz, versões 9:16 e 16:9 | [Português](guias/reel-design-engineer/pt.md) · [English](guias/reel-design-engineer/en.md) |
| Protótipo como prompt | Teste A/B dos code layers do Figma com e sem conexões de protótipo, valores fixos × variáveis e checklist para revisar código gerado | [Português](guias/prototipo-como-prompt/pt.md) · [English](guias/prototipo-como-prompt/en.md) |
| Variáveis do Figma e CSS variables | O que são CSS variables, como saber se o código gerado usou os tokens do design system, exemplos de × para e onde conferir (Figma, código e navegador) | [Português](guias/variaveis-figma-e-css/pt.md) · [English](guias/variaveis-figma-e-css/en.md) |

## Artigos

O que eu penso sobre um tema: opinião, reflexão ou o que tirei de uma palestra, vídeo ou leitura. Ficam com a data em que foram escritos. Também estão no meu site, em [isabelayukari.com](https://isabelayukari.com/pt/escritos).

| Artigo | Tema | Idiomas |
|---|---|---|
| Do artefato ao PR: como a Meaghan Choi desenha o Claude Code | O podcast Dive Club com a design lead do Claude Code: forma antes da tela, artefato como protótipo e registro de decisão, do protótipo ao PR e o papel do designer | [Português](artigos/do-artefato-ao-pr/pt.md) · [English](artigos/do-artefato-ao-pr/en.md) |

## Organização

```
guias/
  tema/
    pt.md        # guia em português
    en.md        # versão em inglês
artigos/
  titulo-curto/
    pt.md        # artigo em português
    en.md        # versão em inglês
```

Um modelo que sirva para quem lê (um prompt base, um checklist) fica dentro do guia ou do artigo que explica por que ele é assim, nunca solto numa pasta.

Cada texto começa com um cabeçalho curto que o site usa para montar a lista:

```yaml
---
data: 2026-11-11          # quando foi publicado
temas: [figma, design-to-code]
rascunho: true            # opcional, só para revisar localmente: o texto não vai para o site
fonte:                    # opcional, para artigos sobre o conteúdo de outra pessoa
  titulo: Designing Claude Code (and what's coming next)
  quem: Meaghan Choi
  onde: Podcast Dive Club, com Michael Riddering (Ridd)
  link: https://www.youtube.com/watch?v=jEEbjiC4JE0
linkedin: https://...     # opcional, o post em que o texto foi compartilhado
---
```

O título vem do `#` e o resumo vem da primeira citação (`>`), então não precisam ser repetidos no cabeçalho.

Só entra aqui conteúdo pronto para compartilhar. Rascunhos ficam fora deste repositório.

## Licença

Os textos estão sob [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.pt_BR): pode compartilhar e adaptar, citando a fonte.
