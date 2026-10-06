# Nova Camada · Alltak RevestFácil · Haus Decor 2027

Esta é uma apresentação comercial interativa, em HTML, da **proposta de stand da Alltak RevestFácil para a Haus Decor Show 2027**. Ela vai de 22 a 26 de fevereiro de 2027, no São Paulo Expo, e foi produzida pela 75LAB. O projeto arquitetônico é da 3DBG.

O texto completo do conceito criativo está em [CONCEITO.md](CONCEITO.md).

## Roteiro (15 telas)

1. **Capa**
2. **A feira:** Haus Decor Show, edição 2027 e números de 2025.
3. **Edição 2025:** Harmonize | Revela.
4. **Edição 2026:** Casa em Movimento.
5. **2027, o salto:** comparativo 2025 → 2026 → 2027.
6. **Conceito:** Nova Camada.
7. **Manifesto**
8. **Pilares do conceito**
9. **Visão geral e planta:** os pontos numerados levam a cada atributo.
10. **Testeira e balcão**
11. **Expositores giratórios e vitrine curva**
12. **Ateliê Nova Camada**
13. **Lounge e volume:** estoque, copa e parede Alltak.
14. **Próximos passos**
15. **Encerramento**

## Estrutura

```
docs/                 versão publicada no GitHub Pages (branch main, pasta /docs)
  index.html          apresentação completa (HTML, CSS e JS sem dependências; fontes via Google Fonts)
  assets/img/brand    marcas RevestFácil e 75LAB
  assets/img/stand    renders do stand (3DBG) e recortes de detalhe
  assets/img/edicoes  imagens das edições 2025 e 2026
CONCEITO.md           texto do conceito criativo, manifesto, pilares e mensagens
serve.ps1             servidor local opcional (http://localhost:8766/docs/)
```

## Uso

**Navegação**
- `←` `→`, espaço, PageUp/PageDown, roda do mouse, swipe ou os botões do rodapé.
- `M` abre os capítulos.
- `Home` e `End` vão para o início e o fim.

**Interação**
- Clique nas imagens para ampliar.
- Nos slides de visão geral e planta, os pontos numerados levam ao detalhe de cada atributo.

**Outros recursos**
- Deep link: `#s9` abre a tela 9.
- Em telas de até 820 px, a apresentação vira rolagem vertical.

## Fontes dos dados

- **Haus Decor:**
  - hausdecorshow.com.br (sobre o evento, visitantes).
  - Relatório pós-show 2025 da NürnbergMesse Brasil.
  - nm-brasil.com.br/calendario.
  - Os números de visitação são publicados somados aos da Expo Revestir.
- **Edições Alltak 2025 e 2026:** briefings, decks e atas internas da 75LAB.

## Atenção

O repositório é público, então o conteúdo pode ser acessado por qualquer pessoa que tenha o link.
