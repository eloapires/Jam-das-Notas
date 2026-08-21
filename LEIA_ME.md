# Jam das Notas

Página única (HTML estático) pra Eloá e Manu darem nota de 0 a 10 nas músicas da jam. Visual escuro/moderno com logo da geleia, sons e confete ao adicionar nota.

## Arquivo
- `index.html` — página inteira (sem build, sem dependências)

## Onde está publicado
Cloudflare Pages/Workers: `jam-das-notas.eloapiresoliveira.workers.dev`

## Como atualizar o site publicado
1. Editar `index.html` aqui nesta pasta
2. Ir em dash.cloudflare.com → Workers & Pages → projeto `jam-das-notas`
3. Criar um novo deployment e subir o `index.html` atualizado

## Sincronização em tempo real
Usa o Supabase (projeto "calendario-medicamental", tabela `jam_notas`) como banco por trás. Toda nota adicionada/editada aparece em tempo real pra quem estiver com a página aberta, sem precisar de login.
