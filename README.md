<div align="center">
  <img src="[https://i.imgur.com/SeuBannerAqui.png](https://pvpq.net/assets/rank_10-DF4HTS_B.png)" alt="WoW PvP Rank Verifier" width="600px" />

  <h1>WoW PvP Rank Verifier Bot</h1>

  <p>
    <strong>O bot definitivo para servidores WoW PvP competitivos.</strong><br>
    Verifica ranks reais via Battle.net OAuth e atribui cargos automáticos — Gladiator, Legend, Rank 1, 2700+ e mais.
  </p>

  <p>
    <img src="https://img.shields.io/badge/Node.js-20.x-339933?logo=nodedotjs&logoColor=white" alt="Node.js" />
    <img src="https://img.shields.io/badge/Discord.js-v14-5865F2?logo=discord&logoColor=white" alt="Discord.js" />
    <img src="https://img.shields.io/badge/Blizzard_API-Active-00AEEF?logo=blizzard&logoColor=white" alt="Blizzard API" />
    <img src="https://img.shields.io/badge/Hosted_on-Railway-131313?logo=railway&logoColor=white" alt="Railway" />
    <img src="https://img.shields.io/badge/Private-🔒-red?style=flat&logo=lock&logoColor=white" alt="Private" />
  </p>

  <br />

  [![Discord](https://img.shields.io/discord/SEU_INVITE?color=5865F2&label=Servidor&logo=discord&logoColor=white&style=for-the-badge)](https://discord.gg/SEU_INVITE_AQUI)

</div>

## O que ele faz?

- Conecta sua conta Battle.net via OAuth seguro
- Puxa ratings (2v2, 3v3, Shuffle), achievements e títulos atuais
- Atribui cargos automáticos com hierarquia real do WoW PvP:
  - **Rank 1** / **R1 Legend** (top 0.1%)
  - **2700 3v3** (legacy achievement + rating atual)
  - **Gladiator** / **Legend** (Achievements + títulos de season)
  - **Elite** (≥2400), **Duelist** (≥2100), **Rival**, **Challenger**, **Combatant**
  - **Unranked** como fallback
- Remove cargos antigos automaticamente
- Interface simples: botão "Verificar" → link privado → cargo na hora
- Mensagem de confirmação clean e privada

Ideal para ladders, guilds PvP, torneios, servidores hardcore WoW.

## Preview

<div align="center">
  <img src="https://i.imgur.com/SuaImagemBotaoAqui.png" alt="Botão Verificar" width="400" />
  <br><br>
  <img src="https://i.imgur.com/SuaImagemMensagemAqui.png" alt="Mensagem de sucesso" width="500" />
  <br><br>
  <img src="https://i.imgur.com/SuaImagemCargosAqui.png" alt="Cargos atribuídos" width="600" />
</div>

## Por que o código é privado?

- **Segurança**: Tokens Discord + Blizzard Client ID/Secret nunca expostos.
- **Exclusividade**: Implementação otimizada e testada no meu servidor principal.
- **Proteção**: Evita cópias maliciosas ou abuso na API Blizzard.

O conceito é simples e replicável — mas essa versão é exclusiva e blindada.

## Tecnologias

- Node.js + Express
- discord.js v14
- passport-bnet (OAuth2 Blizzard)
- Railway (deploy automático e escalável)
- Axios para chamadas à API Blizzard

## Quer algo parecido no seu servidor?

1. Crie um app no [develop.battle.net](https://develop.battle.net/)
2. Configure OAuth2 com scope `wow.profile`
3. Hospede em Railway / Vercel / Render / Fly.io
4. Crie os cargos com nomes exatos (Gladiator, 2700 3v3, Rank 1...)
5. Poste o botão com um comando admin

Se precisar de ajuda ou quiser trocar ideia sobre PvP bots, me chama:

- **Discord**: @fabricioqroz2
- **X**: [@fabricioqroz2](https://x.com/fabricioqroz2)

Feito com ❤️ para a comunidade WoW PvP competitiva.

<div align="center">
  <br />
  <sub>Última atualização: Fevereiro 2026</sub>
  <br />
  <img src="https://img.shields.io/badge/Made%20with-Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
</div>
