# Controle de Produção SK

Aplicação web estática para controle de produção industrial, integrada ao Supabase.

## Publicação no Cloudflare Pages

- Framework preset: None
- Build command: em branco
- Build output directory: `/` (raiz do repositório; se a interface pedir `.` use `.`)

No Cloudflare, abra Workers & Pages → Create → Pages → Connect to Git, conecte o GitHub, selecione `controle-producao-sk` e clique em Save and Deploy.

## Supabase

Projeto: `nawvgoprbhdhdtqgbjuf` (São Paulo). A aplicação usa a chave publicável no navegador. Nunca publique `service_role` ou chaves secretas no HTML.

O acesso exige usuário criado pelo administrador em Supabase → Authentication → Users.