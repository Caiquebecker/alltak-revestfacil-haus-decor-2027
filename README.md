# Nova Camada · Alltak RevestFácil · Haus Decor 2027

Esta é uma apresentação comercial interativa, em HTML, da **proposta de stand da Alltak RevestFácil para a Haus Decor Show 2027**. Ela vai de 22 a 26 de fevereiro de 2027, no São Paulo Expo, e foi produzida pela 75LAB. O projeto arquitetônico é da 3DBG.

O texto completo do conceito criativo está em [CONCEITO.md](CONCEITO.md).

## Roteiro (15 telas)

1. **Capa**, sem revelar o conceito
2. **A feira:** feira de design, como foi de 2023 a 2027.
3. **Inspiração:** galeria de stands de 2026 e tendências.
4. **Público**, com destaque para o público feminino.
5. **2025:** a estreia em 15 dias.
6. **2026:** problemas resolvidos e o ponto de atenção do RP.
7. **O desafio:** lançar o RevestFácil numa feira de design.
8. **Manifesto**, sem nome nem imagem.
9. **KV Nova Camada:** duas opções lado a lado.
10. **Vistas do stand:** perspectiva, frontal e lateral.
11. **Planta** e setorização.
12. **Experiência em AR:** visualizador 3D incorporado, QR code e link (projetos.75lab.com.br/ar/alltak-stand-revest-facil).
13. **Diferenciais do stand**
14. **Cronograma de execução**
15. **Encerramento**

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
- Deep link: `#s12` abre a tela 12 (AR).
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
