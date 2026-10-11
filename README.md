# Nexa Lab — Banco de ideias

Site estático pronto para publicar na Vercel. Sem dependências, instalação, banco de dados ou variáveis de ambiente.

## Arquivos
- `index.html`: aplicação completa (HTML, CSS e JavaScript).
- `vercel.json`: configuração opcional da Vercel.

## Publicar
1. Crie um repositório no GitHub e envie os arquivos da pasta (mantenha `index.html` na raiz do repositório).
2. Abra https://vercel.com/new e importe esse repositório.
3. Escolha **Framework Preset: Other** (ou **No Framework**, se aparecer), **Root Directory: .**, deixe os comandos de build em branco e clique em **Deploy**.

Se usar Vercel CLI localmente na pasta, execute `npx vercel --prod` e siga o assistente.

## Como funciona o salvamento
As ideias são guardadas em `localStorage` no navegador de cada dispositivo, para o domínio publicado. Não são sincronizadas entre celular/computador e podem desaparecer se os dados do navegador forem apagados ou o domínio for trocado.
