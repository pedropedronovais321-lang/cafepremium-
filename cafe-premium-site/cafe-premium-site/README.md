# Café Premium — site

Site estático (HTML, CSS e JS puros), sem build e sem dependências.

## Estrutura

```
index.html      página do site
assets/         logo, croissant e fotos
vercel.json     configurações da Vercel (cache das imagens)
```

## Como subir no GitHub

1. Crie um repositório novo em github.com (ex.: `cafe-premium`).
2. Clique em **Add file → Upload files** e envie **o conteúdo desta pasta** (`index.html`, `assets/`, `vercel.json`, etc.). O `index.html` precisa ficar na raiz do repositório.
3. Clique em **Commit changes**.

## Como publicar na Vercel

1. Entre em vercel.com e clique em **Add New → Project**.
2. Importe o repositório do GitHub.
3. Em **Framework Preset** deixe **Other**. Não precisa de Build Command nem de Output Directory.
4. Clique em **Deploy**.

## Como ligar o seu domínio

1. No projeto da Vercel, abra **Settings → Domains** e adicione o domínio.
2. A Vercel mostra quais registros DNS criar. Crie esses registros no lugar onde o domínio foi registrado (Registro.br, GoDaddy, etc.). Use os valores exatos que a Vercel indicar.
3. Aguarde a propagação do DNS (de alguns minutos a algumas horas). O HTTPS é ativado automaticamente.

## Como editar

Os textos, preços, endereço e links ficam no `index.html`. Depois de salvar a alteração no GitHub, a Vercel publica a nova versão sozinha.
