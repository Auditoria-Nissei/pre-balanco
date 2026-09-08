# Pré-Balanço Gerencial — V2

Protótipo para GitHub Pages.

## O que esta V2 faz
- Painel do auditor para cadastrar filial, data do balanço, horário limite e gestor.
- Geração de código/link individual para o gestor.
- Preenchimento progressivo durante a semana.
- Bloqueio da finalização antes do dia do balanço.
- Bloqueio da finalização após o horário limite.
- Parte sistêmica e organização física.
- Campos de observação, chamado e evidência.
- Declaração final e registro de data/hora de envio.

## Limitação importante
Esta V2 é um protótipo estático: os dados são guardados no `localStorage` do navegador e os arquivos enviados não são transmitidos para um banco. Para operação real multiusuário, a próxima versão deve usar autenticação + banco + armazenamento de arquivos (ex.: Supabase/Firebase).

## Publicar no GitHub Pages
1. Crie um repositório.
2. Envie `index.html`.
3. Settings > Pages.
4. Source: Deploy from a branch.
5. Branch: `main` e folder `/ (root)`.
