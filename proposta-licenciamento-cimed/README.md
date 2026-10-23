# Proposta de Licenciamento CIMED

Página estática de uma única imagem para apresentar a proposta comercial aprovada da Tampa Batoque Híbrida CIMED. O conteúdo publicado fica na pasta `public/`.

## Imagem aprovada

O arquivo original aprovado está em `public/images/proposta-licenciamento-cimed.png`, copiado sem alterações. A página exibe a imagem inteira, mantendo sua proporção em telas grandes e pequenas.

## Desenvolvimento local

Sirva a pasta `public/` com qualquer servidor estático. Não há etapa de compilação.

## Publicação

O site público está em <https://proposta-licenciamento-cimed.netlify.app/>. O Netlify está conectado a este repositório e publica automaticamente as atualizações da branch `main`, usando `public/` como diretório publicado.

A conexão usa uma deploy key somente leitura e um webhook de `push` apontando para o build hook do Netlify. As chaves de deploy estavam desabilitadas na política da organização `TampaCIMED` e foram reabilitadas para restabelecer a publicação automática.
