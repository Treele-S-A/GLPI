# Contexto para IA — GLPI (Central de Suporte)

Mapa de todos os sistemas: `C:\GitHub\Desenvolvimento\MAPA_SISTEMAS.md`.

## Onde paramos

- **30/10/2026:** capa repaginada no padrão visual do RH, com foto gerada de TI na obra, fundo integral, cartão central, animação da logo e favicon laranja do GLPI. Links de acesso e recuperação preservados. Publicação autorizada pelo usuário. Próximo passo: conferir a página em produção em desktop e celular.
- **28/10/2026:** página de entrada no ar (última mudança em 06/10/2026). O GLPI em si roda na nuvem do fornecedor.

## O que é
Página de entrada da **Central de Suporte da Treèle** ("Central de Suporte | Treèle"). O GLPI em si roda na nuvem
do fornecedor: **https://treele.us5.glpi-network.cloud** (login SSO Microsoft pelo plugin `oauthsso`, recuperação
de senha da Microsoft e do GLPI). Este repositório só tem a página que leva até lá.

## Onde está
- Produção: **https://glpi.treele.com.br** (Vercel `glpi`, time `treele2`). GitHub `Treele-S-A/GLPI`, branch `main`.
- Conteúdo: `index.html` (página única) e `assets/`.

## Cuidados
- Chamados, usuários e configurações ficam no GLPI na nuvem, não aqui.
- O Portal Treèle e o Supram apontam para `glpi.treele.com.br` como "Ajuda / abrir chamado".

## Histórico

Uma linha por trabalho, a mais recente no fim: `AAAA-MM-DD · pessoa · IA usada · o que mudou · commit`.

- 2026-10-28 · TI (titreele) · Claude Code · criado este `CONTEXTO_IA.md`, `CLAUDE.md` e `AGENTS.md` com as regras obrigatórias de registro · (este commit)
- 2026-10-30 · TI · Codex · capa local, imagem de TI/obras e logo animada; links GLPI preservados · sem commit a pedido do usuário
- 2026-10-30 · TI · Codex · login local ajustado ao cartão central sobre foto integral do RH · sem commit a pedido do usuário
- 2026-10-30 · TI · Codex · favicon do GLPI e CHANGELOG.md local · sem commit a pedido do usuário
- 2026-10-30 · TI · Codex · favicon do GLPI recolorido em laranja e ícone do Portal alinhado · sem commit a pedido do usuário
- 2026-10-30 · TI · Codex · capa e favicon do GLPI publicados após autorização · (este commit)
