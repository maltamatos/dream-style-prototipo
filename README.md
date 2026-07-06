# Dream Style — Protótipo Jogável

Projeto autoral de simulação de moda focado em sistemas de reputação, personalização de assets 3D assistida por IA e gestão de inventário social.

🎮 **[Jogue o protótipo aqui](https://maltamatos.github.io/dream-style-prototipo/)**

---

## Sobre o projeto

Dream Style acompanha **Dream**, uma personagem reservada, elegante e de poucas palavras, que navega eventos sociais decidindo como se apresentar e como responder a quem a observa. O jogo conecta três sistemas centrais: **escolha de look**, **diálogo com NPCs** e **reputação**.

Este repositório contém um protótipo jogável em HTML/CSS/JS, criado para validar o game loop antes da produção de assets 3D e sistemas mais completos.

## Game Loop

| Ação do Jogador | Resultado no Jogo |
|---|---|
| Escolher look para o evento | Ajusta a percepção social (elegância/autoridade) e desbloqueia reações de NPCs |
| Conversar com Mecânica de Socialização (opções de diálogo) | Aumenta afinidade, abre convites e oportunidades em novos eventos |
| Cumprir um objetivo do evento (ex.: causar boa impressão) | Ganha reputação, moeda/itens e libera novos looks/locais |
| Economia do Jogo | Melhora atributos do look e cria combinações para diferentes ocasiões |
| Decidir como responder a críticas/elogios | Impacta personalidade percebida e consequências em relações futuras |

## Personagem — Dream

Reservada, fala pouco, com elegância e firmeza. Algumas falas que definem sua voz:

> "Prefiro deixar o resultado falar por si."
> "Eu não disputo atenção — eu escolho onde estar."
> "Não preciso explicar. Basta observar."

## O que o protótipo já simula

- Escolha entre 3 looks (Alfaiataria, Social, Noite), cada um com uma leitura social diferente
- Diálogos com NPCs usando as falas originais da personagem
- Sistema de reputação que reage às escolhas do jogador
- Uma pequena economia (moedas ganhas em diálogo, gastas em acessórios entre eventos)
- Dois eventos em sequência (Gala de Lançamento → After-party), com desfecho final variável

## Rodando localmente

Não é necessário instalar nada:

1. Baixe o arquivo `index.html`
2. Abra com dois cliques no navegador

## Roadmap / próximos passos

- [ ] Substituir os placeholders de cor pelos renders 3D reais dos looks
- [ ] Expandir a economia do jogo (mais itens, moeda persistente entre sessões)
- [ ] Adicionar mais eventos e ramificações de diálogo
- [ ] Migrar para uma engine (Godot/Unity) ou Ren'Py, dependendo do rumo do projeto

---

*Projeto de portfólio — estudante de jogos digitais, com foco em roteiro e design de personagens.*
