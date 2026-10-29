# Dell Pro — Sala de imprensa

Página estática da sala de imprensa para o lançamento da linha Dell Pro no Brasil.

## Estrutura

* `index.html` — página principal leve.
* `assets/` — imagens WebP e PDFs separados.
* `.nojekyll` — habilita publicação direta pelo GitHub Pages.

A separação mantém cada arquivo abaixo do limite de upload de 25 MB. O botão de download das imagens continua funcionando e gera um ZIP no navegador, com as imagens sobre fundo branco para evitar transparência.

## Publicar no GitHub Pages

1. Envie `index.html`, a pasta `assets/` e `.nojekyll` para a raiz do repositório.
2. Em **Settings > Pages**, selecione **Deploy from a branch**.
3. Escolha a branch principal e a pasta `/ (root)`.
4. Salve e aguarde a geração do endereço público.

Não é necessário instalar dependências ou executar um build.
