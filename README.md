# TimeMind — protótipo instalável

## O que funciona
- Criar tarefas com horário e prioridade.
- Marcar tarefas como concluídas e excluir tarefas.
- Filtrar tarefas por status.
- Acompanhar o progresso do dia.
- Temporizador de concentração de 25 minutos.
- Salvar tarefas no próprio navegador (localStorage).
- Instalação como PWA e funcionamento offline depois da primeira abertura.

## Como testar no computador
Abra `index.html` no navegador para testar as funções. Para instalar como PWA, é necessário publicar a pasta em um endereço HTTPS (ou usar localhost).

## Como colocar online gratuitamente pelo GitHub Pages
1. Crie uma conta no GitHub, se ainda não tiver.
2. Crie um repositório novo chamado `timemind`.
3. Envie todos os arquivos desta pasta, mantendo a estrutura (principalmente `manifest.json`, `sw.js` e a pasta `icons`).
4. No repositório, entre em **Settings → Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**.
6. Escolha a branch `main` e a pasta `/ (root)`, depois clique em **Save**.
7. Aguarde o GitHub mostrar o endereço publicado. Abra esse endereço no Chrome do celular.

## Como instalar no Android
1. Abra o endereço HTTPS publicado no Chrome do Android.
2. Toque no menu de três pontinhos.
3. Escolha **Instalar app** ou **Adicionar à tela inicial**.
4. Confirme. O ícone TimeMind aparecerá na tela inicial e o app abrirá em janela própria.

## Observações
- Este é um protótipo local: os dados ficam salvos apenas naquele navegador/dispositivo.
- Não há conta, sincronização entre aparelhos ou notificações push nesta versão.
- O modo concentração usa um temporizador de 25 minutos; ele não bloqueia outros aplicativos.
- Para uma versão pública real, configure domínio, política de privacidade e backend seguro.
