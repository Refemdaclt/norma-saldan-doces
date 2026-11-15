# Norma Saldan Doces Finos: prévia do site

Prévia online do site, rodando no [WordPress Playground](https://wordpress.org/playground/) direto no navegador de quem abre.

**Link para o cliente:** https://refemdaclt.github.io/norma-saldan-doces/

- Cada pessoa que abre recebe uma cópia própria do site, que roda no navegador dela. Nada do que for feito ali fica salvo nem aparece para outras pessoas.
- O primeiro carregamento leva cerca de 1 minuto.

| Arquivo | O que é |
|---|---|
| `index.html` | Página que abre o Playground em tela cheia |
| `blueprint.json` | Instruções para o Playground: importar o `site.zip` |
| `site.zip` | Pasta `wp-content` do site (tema, plugin, Elementor, fotos e banco SQLite sem chaves de segurança) |

Para atualizar, gere o `site.zip` de novo no projeto local (`python -I scripts/gerar-playground-web.py`) e envie para este repositório.
