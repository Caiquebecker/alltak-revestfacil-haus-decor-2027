# Nova Camada · Alltak RevestFácil · Haus Decor 2027

Esta é uma apresentação comercial interativa, em HTML, da **proposta de stand da Alltak RevestFácil para a Haus Decor Show 2027**. Ela vai de 22 a 26 de fevereiro de 2027, no São Paulo Expo, e foi produzida pela 75LAB. O projeto arquitetônico é da 3DBG.

O texto completo do conceito criativo está em [CONCEITO.md](CONCEITO.md).

## Roteiro (18 telas)

1. **Capa**: "Lançamento de RevestFácil", sem revelar o conceito
2. **Haus Decor Show:** uma feira de design, não de balcão.
3. **Como foi nos últimos anos** (2023–2027)
4. **Números da feira:** público, mídia e expositores.
5. **Inspiração:** galeria de stands de 2026.
6. **Tendências** do Book 2026
7. **Público**, com destaque para o público feminino.
8. **2025:** a estreia em 15 dias.
9. **2026:** problemas resolvidos e o ponto de atenção do RP.
10. **O desafio:** lançar RevestFácil numa feira de design.
11. **Manifesto**, sem nome nem imagem.
12. **KV:** arte "Vida em novas camadas" (assets/img/kv/kv-nova-camada.webp).
13. **Vistas do stand**
14. **Planta** e setorização.
15. **Diferenciais do stand**
16. **Experiência em AR:** visualizador 3D, QR code e link.
17. **Cronograma de execução**, por data, de 07/10/2026 ao relatório pós-feira.
18. **Encerramento**

As fotos de stands de outras marcas vêm da galeria oficial da Haus Decor Show 2026 (© NürnbergMesse Brasil). Elas são exibidas direto do site da feira, com crédito.

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
- Deep link: `#s16` abre a tela 16 (AR).
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
