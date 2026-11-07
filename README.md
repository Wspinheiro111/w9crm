# W9 CRM — W9 Sistemas

CRM comercial próprio para gestão de clientes, contatos, oportunidades, agenda e comunicação manual via WhatsApp.

> **Status: desenvolvimento / não usar com dados reais.** O código do MVP ainda está sendo validado. Este repositório foi inicializado como destino da implementação; a importação do código da rodada 6 está pendente. Nenhum deploy público está autorizado.

## Objetivos do MVP

- Cadastro de empresas, CTGs e contatos, sem duplicações;
- Agenda e retornos comerciais com acompanhamento;
- Funil de oportunidades por produto W9;
- Botão que abre WhatsApp manualmente (não envia mensagens);
- Importação assistida de CSV com revisão e tratamento de duplicidades;
- Isolamento de dados, autenticação e auditoria.

## Segurança e operação

- **Não inserir** neste repositório arquivos `.env`, senhas, tokens, arquivos de clientes, dados comerciais reais, dumps, backups ou logs sensíveis.
- Não reutilizar banco, credenciais, contas de serviço ou ambientes de Tchê Vendas ou GestãoCTG.
- Não executar migrations em produção.
- Validar compilação, PostgreSQL descartável, isolamento, autenticação e fluxo E2E antes de qualquer implantação.
- O código publicado aqui não constitui autorização para um serviço online ou para processamento de dados reais.

## Próxima etapa

Importar a versão local da sexta rodada para uma branch de desenvolvimento, revisar o diff e abrir PR em modo rascunho. O projeto só será liberado para uso real após testes integrados, segurança e backup/restauração.

---
W9 Sistemas — projeto em desenvolvimento.
