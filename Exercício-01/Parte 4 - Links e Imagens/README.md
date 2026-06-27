# Como corrigir uma imagem quebrada no HTML?

Se uma imagem não carregar no navegador (ficar "quebrada"), existem alguns passos sistemáticos para identificar e corrigir o problema:

1. **Verificar o Caminho do Arquivo (`src`):**
   * Certifique-se de que o caminho relativo está correto. Se a imagem está na pasta `img`, o atributo deve ser exatamente `src="img/nome-da-imagem.extensao"`.
2. **Checar a Extensão e a Grafia do Nome:**
   * O HTML é case-sensitive em sistemas Linux/macOS. Se o arquivo se chama `foto.JPG` (maiúsculo) e no código está `foto.jpg` (minúsculo), o link quebrará.
   * Certifique-se de usar a extensão correta (`.png`, `.jpg`, `.jpeg`, `.svg`, `.webp`).
3. **Validar a Existência do Arquivo:**
   * Confirme se o arquivo da imagem foi realmente movido/salvo dentro da pasta correta (`img/`) e não ficou perdido na raiz do projeto.
4. **Verificar a Acessibilidade do Link (Imagens Externas):**
   * Caso fosse uma URL externa, seria necessário verificar se o link não mudou ou se o servidor de hospedagem está fora do ar.
5. **Garantir o Uso do Atributo `alt`:**
   * Enquanto o erro é corrigido, o texto do atributo `alt` deve ser descritivo o suficiente para que o usuário entenda o que deveria estar ali, mantendo a acessibilidade da página.