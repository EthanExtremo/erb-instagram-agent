# ERB Instagram Agent

**Agente de marketing de Instagram da ERB Motion** — adaptação para ChatGPT do projeto [Instagram Agent Skill](https://github.com/Jakeschincariol/instagram-agent-skill), de Jake Schincariol.

> Sua ideia em movimento.

Este repositório reúne instruções reutilizáveis para planejar, criar, revisar e otimizar conteúdo de Instagram para a ERB Motion e seus clientes. A primeira versão é um pacote de prompts e skills compatível com ChatGPT; não é um aplicativo autônomo nem publica conteúdo automaticamente.

## O que vem aqui

- **13 módulos:** Reels, pesquisa de referências, legendas, carrosséis, Stories, perfil, calendário, humanização, comentários, respostas, DMs, reaproveitamento e auditoria.
- Identidade editorial da ERB Motion e regras de qualidade.
- Fluxo com aprovação humana.
- Guia de configuração de um GPT personalizado.

## Comece

1. Abra `INSTRUCTIONS.md` e copie seu conteúdo para o campo **Instruções** de um GPT personalizado.
2. Adicione `VOICE.md` e os arquivos de `skills/` como conhecimento, se disponível.
3. Consulte `docs/CHATGPT-SETUP.md` para o passo a passo.

## Módulos

| Comando | Uso |
|---|---|
| `/ig-reel` | Roteiros de Reels |
| `/ig-viral` | Pesquisa manual de referências e tendências |
| `/ig-caption` | Legendas |
| `/ig-carousel` | Carrosséis |
| `/ig-story` | Sequências de Stories |
| `/ig-profile` | Bio e posicionamento do perfil |
| `/ig-plan` | Calendário editorial |
| `/ig-human` | Revisão de naturalidade |
| `/ig-comment` | Sugestões de comentários |
| `/ig-reply` | Respostas a comentários |
| `/ig-dm` | Rascunhos de mensagens diretas |
| `/ig-repurpose` | Reaproveitamento de conteúdo |
| `/ig-audit` | Auditoria de perfil e conteúdo |

Os comandos são convenções de prompt: digite-os como texto no ChatGPT. Não são comandos nativos.

## Limites

- Não solicita senhas, códigos de autenticação ou tokens.
- Não faz login, scraping, follow/unfollow, disparo de DMs/comentários nem publicação automática.
- Não inventa métricas, resultados, depoimentos, clientes ou tendências.
- Informações atuais da plataforma devem ser verificadas em fontes recentes.
- Todo conteúdo é rascunho até aprovação humana.

## ERB Motion

Estúdio audiovisual com posicionamento jovem, contemporâneo e profissional. Atua com edição de vídeo, design gráfico e criação de conteúdo para redes sociais. A comunicação deve transmitir criatividade, clareza, consistência e valor, sem prometer resultados garantidos.

## Créditos e licença

Este projeto adapta ideias, estrutura e materiais do [Instagram Agent Skill](https://github.com/Jakeschincariol/instagram-agent-skill), de Jake Schincariol, originalmente distribuído sob licença MIT. O aviso de copyright e a licença original são preservados em `LICENSE`.

## Status

**v0.1.0 — base ChatGPT:** instruções centrais e 13 módulos documentados. Scripts auxiliares e testes automatizados não estão incluídos nesta primeira entrega.
