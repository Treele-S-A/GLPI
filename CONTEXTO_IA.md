# Contexto para IA — GLPI (Central de Suporte)

Mapa de todos os sistemas: `C:\GitHub\Desenvolvimento\MAPA_SISTEMAS.md`.

## Onde paramos

- **28/10/2026:** página de entrada no ar (última mudança em 06/10/2026). O GLPI em si roda na nuvem do fornecedor.
- **Próximo passo:** nenhuma tarefa em aberto.

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
