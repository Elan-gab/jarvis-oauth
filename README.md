# Jarvis

Jarvis é um assistente pessoal via WhatsApp que, com **autorização explícita** do usuário, acessa o **Google Calendar** para criar e consultar eventos e tarefas a pedido.

## Sobre este projeto

Jarvis **não** é um produto comercial aberto ao público. A integração OAuth com o Google existe para permitir que o operador do bot use a **própria conta Google** de forma controlada e transparente, conforme exigido pela política de dados do Google.

## Dados acessados

O bot acessa **apenas** os dados que o usuário autorizar na tela de consentimento OAuth — neste fluxo, escopos relacionados ao **Google Calendar** (criar, listar e atualizar eventos conforme os pedidos feitos no WhatsApp).

Não solicitamos acesso a Gmail, Drive ou outros serviços Google neste fluxo.

## Política de Privacidade

Consulte [PRIVACY.md](PRIVACY.md) neste repositório.

URL canônica: https://github.com/Elan-gab/jarvis-oauth/blob/main/PRIVACY.md

## Contato

Para dúvidas, solicitações ou pedidos relacionados a privacidade, abra uma **Issue** em:

https://github.com/Elan-gab/jarvis-oauth/issues

## Como revogar o acesso

Você pode revogar a autorização a qualquer momento em:

**Conta Google → Segurança → Conexões com apps de terceiros**

Ou diretamente em: https://myaccount.google.com/permissions
