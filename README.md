# ```eof

---

## 📸 Guia Simples: Como Colocar Suas Fotos sem Erro (Via GitHub)

A forma mais profissional e segura de colocar as fotos de vocês no site (evitando usar links de sites de terceiros que expiram ou param de funcionar) é subir as imagens diretamente no seu próprio repositório do GitHub. É muito simples:

### Passo 1: Prepare as suas fotos no computador
1. Escolha a **foto principal** do casal e renomeie o arquivo para: `principal.jpg`.
2. Escolha até 3 fotos marcantes para a linha do tempo e renomeie para: `historia1.jpg`, `historia2.jpg` e `historia3.jpg`.
*(Dica: Se as fotos estiverem em formato `.png`, você pode mudar a extensão do código de `.jpg` para `.png` ou converter as fotos para `.jpg`).*

### Passo 2: Crie a pasta no seu GitHub
1. Abra o seu repositório do GitHub na internet (aquele onde você colocou o `index.html`).
2. Clique no botão **"Add file"** > **"Create new file"**.
3. No campo onde você digita o nome do arquivo, escreva exatamente: `fotos/` (com a barra no final). 
4. Ao digitar a barra `/`, o GitHub entende automaticamente que é para criar uma pasta chamada **fotos**.
5. Crie um arquivo temporário qualquer dentro dela (pode escrever `readme.txt` no nome e salvar) só para fixar a pasta.

### Passo 3: Faça o Upload das Fotos
1. Entre na pasta **fotos** que você acabou de criar no GitHub.
2. Clique em **"Add file"** > **"Upload files"**.
3. Arraste as suas imagens (`principal.jpg`, `historia1.jpg`, etc.) diretamente para lá e clique em salvar mudanças ("Commit changes").

**Prontinho!** O código que montei acima já está programado para procurar a foto principal e as fotos da linha do tempo dentro dessa pasta `fotos/`. Se por acaso alguma foto não carregar, ou se você decidir não colocar fotos na linha do tempo, a programação vai detectar o erro e esconder o "quadro" da foto automaticamente, mantendo o design lindo e limpo!

### 🔗 Onde colocar o seu link do Spotify:
* Na **linha 198** do código, mude o texto `SUA_PLAYLIST_DO_SPOTIFY_AQUI` para o link real da playlist que você montou.

Seu site está completo, ultra-romântico, rápido de carregar no celular e totalmente sob seu controle. Se precisar de ajuda para alterar qualquer detalhe da receita ou quiser mais alguma ideia, estou aqui!