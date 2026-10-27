CC Shop Studio MCP (Cloudflare Workers)
Ferramentas: analisar_produto, gerar_prompt_video_json, gerar_prompt_imagem, gerar_conteudo_comercial. Endpoint MCP: https://SEU-WORKER.workers.dev/mcp  ·  Termos: /terms  ·  Privacidade: /privacy
PASSO A PASSO
1) GitHub (guardar o código) — https://github.com
Crie uma conta/entre. Clique em New repository → nome cc-shop-studio-mcp → Create.
Clique em uploading an existing file e envie TODOS os arquivos desta pasta (mantendo a pasta src/). Commit.
2) Cloudflare (publicar numa URL) — https://dash.cloudflare.com
Entre na conta (a mesma do tik-tok-viral).
Menu Workers & Pages → Create → Import a repository (Connect to Git).
Autorize o GitHub e escolha cc-shop-studio-mcp.
Nome do projeto: cc-shop-studio-mcp. Build command: deixe vazio. Deploy command: npx wrangler deploy. Clique Deploy.
Ao terminar, copie a URL: https://cc-shop-studio-mcp.SEUUSUARIO.workers.dev.
Teste no navegador: abra a URL (deve mostrar "Shop Studio AI") e /terms.
3) Portal da OpenAI — https://platform.openai.com
No seu app "Loja Studio AI", vá na aba MCPs e adicione o servidor: URL = https://cc-shop-studio-mcp.SEUUSUARIO.workers.dev/mcp (sem autenticação).
Em Metadados, atualize: Site = URL base; Termos = URL base + /terms; Privacidade = URL base + /privacy (ou mantenha a do TermsFeed).
Envie o pacote de novo e clique em Enviar para revisão.
Se o portal mostrar a interface diferente, copie o texto da tela e me mande.
