# Pet&Happy — aplicativo Pet Shop

Protótipo PWA estático, feito para funcionar no GitHub Pages.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Envie **todos os arquivos e pastas deste ZIP**, mantendo a pasta `assets`.
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione `main` e `/ (root)` e salve.
6. Aguarde a publicação e abra o endereço do Pages no celular.

## O que já funciona
- Navegação entre Início, Categorias, Serviços, Carrinho e Perfil.
- Busca e filtros de produtos.
- Adicionar/remover produtos e alterar quantidades.
- Carrinho persistente com `localStorage`.
- Simulação de finalização de compra.
- Atendimento/chat com respostas simuladas.
- Agendamento de serviços em janela modal.
- Perfil e configurações simuladas.
- Tela de unidades/localização.
- PWA com manifesto e Service Worker.
- Interação especial: ao tocar/clicar na tela fora dos controles, um cachorro ou gato aparece e reage à posição do toque; ao mover o dedo/mouse, ele acompanha a direção.
- Layout responsivo e otimizado para celular.

## Observação
Este é um protótipo frontend. Para produção, conecte autenticação, banco de dados, estoque, pagamentos, pedidos, notificações e atendimento real a um backend/Firebase.
