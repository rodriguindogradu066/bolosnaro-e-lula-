# 🏁 Corrida Lula × Bolsonaro

Jogo de corrida por turnos feito em HTML/CSS/JavaScript puro (um único arquivo, `index.html`).
Lula e Bolsonaro dão **um passo por vez** até a linha de chegada, e no meio do caminho tem obstáculos.

## Como jogar
- **Contra o computador**: escolha seu corredor e jogue com os botões (ou Espaço = passo, P = pular).
- **2 jogadores**: no mesmo aparelho, revezando a vez. Lula: tecla `A` (passo) / `S` (pular) · Bolsonaro: tecla `L` (passo) / `K` (pular).
- Em cada vez você escolhe:
  - 👣 **Dar um passo**: anda 1 casa.
  - 🦘 **Pular**: anda 2 casas (passa por cima de um obstáculo), mas tem 35% de chance de cair e ficar no lugar.

## Obstáculos
| Casa | Efeito |
|---|---|
| 🍌 Banana | escorrega e volta 2 casas |
| 🪨 Pedra | tropeça e volta 1 casa |
| 🕳️ Buraco | perde a próxima vez |
| ⚡ Turbo | avança +2 casas |

Os obstáculos mudam a cada corrida e são iguais nas duas raias, então a corrida é justa.

## Colocar o site no ar (GitHub Pages)
1. No GitHub, abra o repositório → **Settings** → **Pages**.
2. Em *Source*, escolha **Deploy from a branch**, selecione o branch e a pasta `/ (root)` e salve.
3. Em alguns minutos o jogo fica disponível em `https://<seu-usuario>.github.io/<nome-do-repositorio>/`.

Para jogar no computador sem internet, é só abrir o `index.html` no navegador.
