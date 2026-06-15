# Mundo da Copa 26

Site independente para acompanhar a Copa do Mundo 2026 com calendário, classificação, estádios, convocações, simulador, Draft, Escudle, blog editorial, notícias, placares em tempo real e estatísticas de partidas.

## Repositório showcase

Este repositório documenta publicamente o projeto **Mundo da Copa 26** como vitrine/case study.

O código-fonte principal não está disponível publicamente neste momento e não faz parte deste repositório.

## Site

https://www.mundodacopa.site

## Funcionalidades principais

- Home com destaques, ticker de jogos, rotas limpas e feed de notícias
- Calendário da Copa com filtros, busca e URLs compartilháveis
- Visualização dos 104 jogos do torneio
- Classificação por grupos, incluindo grupos A–L
- Guia dos 16 estádios da Copa
- Mapa interativo dos estádios
- Convocações e organização de jogadores por posição
- Histórico das seleções em Copas anteriores
- Dados por seleção: participações, títulos, melhor campanha, record geral, gols e artilheiros
- Simulador da Copa com fase de grupos e mata-mata
- Simulador respeita placares reais quando disponíveis, travando jogos já realizados
- Compartilhamento de cenários do simulador por link
- Draft Copa 2026: monte um XI com jogadores sorteados e tente vencer 8 jogos seguidos
- Reposicionamento de jogadores aptos no Draft
- Card PNG compartilhável do Draft
- Escudle: jogo diário de adivinhar escudos das seleções, com validação backend e histórico local
- Blog editorial com guias, artigos, categorias, busca e paginação
- Página de apoio ao projeto
- Atualização de placares reais via infraestrutura própria/cache
- Estatísticas de partidas em modal, incluindo placar, gols, eventos e dados do jogo quando disponíveis
- Rotas amigáveis e metadados por página para melhor experiência de compartilhamento
- Boas práticas públicas de segurança: HTTPS, headers de segurança, redirecionamento canônico e security.txt
- Estado da navegação na URL para facilitar compartilhamento
- Dark mode
- Design responsivo para desktop, tablet e mobile

## Screenshots

| Tela | Screenshot |
| --- | --- |
| Home | ![Home](assets/screenshots/home.png) |
| Calendário | ![Calendário](assets/screenshots/calendario.png) |
| Classificação | ![Classificação](assets/screenshots/classificacao.png) |
| Estádios | ![Estádios](assets/screenshots/estadios.png) |
| Histórico das seleções | ![Histórico das seleções](assets/screenshots/historico-selecoes.png) |
| Simulador | ![Simulador](assets/screenshots/simulador.png) |
| Blog | ![Blog](assets/screenshots/blog.png) |

## Tecnologias usadas

Visão em alto nível, sem detalhes sensíveis de infraestrutura:

- JavaScript, HTML e CSS
- Vite
- Leaflet para mapa interativo
- Cloudflare Pages
- Cloudflare Workers/Functions
- KV/cache para dados de placares
- Endpoints serverless para fluxos que exigem validação no servidor
- Worker agendado para atualização de placares e detalhes de partidas
- Base histórica pública da Copa do Mundo para histórico das seleções
- Playwright para testes end-to-end

## Status

Projeto em desenvolvimento ativo, com funcionalidades principais implementadas e evolução contínua de conteúdo editorial, experiência mobile, placares, jogos interativos e recursos de compartilhamento.

## Documentação

- [Visão geral do projeto](PROJECT_OVERVIEW.md)

## Disclaimer

O **Mundo da Copa 26** é um projeto independente e não possui afiliação com FIFA, confederações, seleções ou entidades oficiais.

## Código-fonte

Este repositório não contém o código-fonte principal do site, arquivos de configuração reais, secrets, dados privados, infraestrutura interna ou conteúdo operacional do projeto.
