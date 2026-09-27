# Protótipo — Plataforma de Entregas (Roches)

Protótipo estático (HTML5 + CSS + JavaScript puro, sem back-end) do sistema de marketplace de entregas: clientes finais compram de lojistas parceiros, motoboys entregam, administração gerencia atendentes e motoboys.

## Arquivos

- `index.html` — página inicial com links para os três fluxos abaixo.
- `cliente.html` — cadastro, login, busca de lojas/produtos, carrinho (multi-loja), checkout e acompanhamento do pedido, além do painel do lojista.
- `admin.html` — login do administrador master: cadastro de atendentes e motoboys, atribuição de motoboys aos pedidos.
- `motoboys.html` — login do motoboy e lista de entregas atribuídas (coletas nas lojas + destino do cliente).

## Usuários de demonstração

Qualquer senha funciona. Cada página guarda seus próprios dados de exemplo em memória (não há back-end nem sincronização entre as páginas nesta fase).

| Página | Usuário |
|---|---|
| `cliente.html` | `cliente-final` (área do cliente) ou `lojista` (área do lojista) |
| `admin.html` | `master` |
| `motoboys.html` | `motoboy` |

## Como publicar com o GitHub Pages

1. Crie um repositório novo no GitHub (pode ser público ou privado — GitHub Pages funciona nos dois casos em contas normais e em contas Pro/organização; em contas gratuitas, repositórios **privados** precisam de plano pago para Pages, então se quiser gratuito, deixe o repositório **público**).
2. Na página do repositório recém-criado, clique em **Add file → Upload files**.
3. Arraste os 4 arquivos desta pasta (`index.html`, `cliente.html`, `admin.html`, `motoboys.html`, e este `README.md`) para a área de upload e clique em **Commit changes**.
4. Vá em **Settings → Pages** (menu lateral esquerdo).
5. Em **Build and deployment → Source**, selecione **Deploy from a branch**.
6. Em **Branch**, selecione `main` (ou `master`) e a pasta `/ (root)`, depois **Save**.
7. Aguarde cerca de 1 minuto e recarregue a página de Settings → Pages: vai aparecer um link do tipo `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.
8. Acesse esse link — a página inicial (`index.html`) vai carregar automaticamente com os três cartões de acesso.

Pronto: esse link pode ser aberto em qualquer navegador, computador ou celular, sem precisar do Claude.
