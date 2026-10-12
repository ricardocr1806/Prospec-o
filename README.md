# Prospecção

Ferramenta simples para organizar a prospecção de clientes.

## O que tem aqui

- **`index.html`**: mini CRM de leads, que roda direto no navegador, sem instalar nada.
  - Cadastro de leads (nome, empresa, cidade, WhatsApp, e-mail, Instagram, origem, valor e notas)
  - Funil de status: Novo → Contatado → Respondeu → Reunião → Proposta → Fechado / Perdido
  - Data do próximo contato, com destaque para os follow-ups de hoje e os atrasados
  - Botões que abrem o WhatsApp, o e-mail e o Instagram do lead
  - Busca, filtro por status e total já fechado em R$
  - Exportar e importar CSV (abre no Excel e no Google Sheets)
- **`leads-modelo.csv`**: modelo de planilha para importar leads em massa.
- **`scripts/mensagens.md`**: modelos de mensagens de primeiro contato, follow-up e respostas a objeções.

## Como usar

1. Baixe o repositório e abra o `index.html` no navegador. Também dá para publicar de graça no GitHub Pages ou no Cloudflare Pages.
2. Clique em **+ Lead** para cadastrar, ou em **Importar CSV** para trazer uma lista pronta (use o `leads-modelo.csv` como base).
3. Use **Avançar ▸** para mover o lead no funil.
4. Faça **Exportar CSV** de vez em quando como backup.

> ⚠️ Os dados ficam salvos só no navegador em que você usa (localStorage). Eles não vão para o GitHub nem para nenhum servidor. Se você limpar os dados do navegador, os leads somem, então exporte o CSV com frequência.
