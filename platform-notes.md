# Notas por plataforma

Ultima revisao: 2026-06-01

## DEV Community

O editor usa frontmatter estilo Jekyll. Campos relevantes:

- `title`.
- `published`.
- `tags`: maximo de 4 tags, separadas por virgula.
- `canonical_url`: URL canonica do conteudo.
- `cover_image`: opcional.

Fonte oficial: https://dev.to/p/editor_guide/

## Hashnode

Para publicacao via GitHub, Hashnode usa frontmatter em Markdown. Campos relevantes:

- `title`.
- `slug`.
- `tags`.
- `publication`.
- `canonical`.
- `seoTitle`.
- `seoDescription`.
- `saveAsDraft`.

Fonte oficial: https://docs.hashnode.com/blogs/blog-dashboard/github/frontmatter-breakdown

## Medium

Medium permite importar uma historia publicada em outro lugar e adicionar canonical automaticamente pela ferramenta de importacao. Tambem permite configurar canonical manualmente.

Fontes oficiais:

- https://help.medium.com/hc/en-us/articles/214550207-Importing-a-post-to-Medium
- https://help.medium.com/hc/en-us/articles/360033930293-Set-a-canonical-link

## Politica interna XMACNA

Publicar com canonical. Se a plataforma nao permitir canonical ou se houver duvida, manter como rascunho ate revisao humana.
