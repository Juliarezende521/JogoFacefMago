

# 🧙‍♂️ Wizard Survival - Projeto de Jogo com Banco de Dados

Bem-vindo ao repositório do projeto **Wizard Survival**, um jogo de tiro desenvolvido como trabalho de faculdade. O jogador assume o papel de um **mago** que precisa sobreviver aos ataques de **duendes** e **dragões**. O jogo foi criado na plataforma **Construct 3**, e conta com integração a um **banco de dados SQL** para armazenar o **ranking dos jogadores**.

## 🎮 Sobre o Jogo

- **Gênero:** Tiro / Sobrevivência
- **Protagonista:** Mago com habilidades mágicas. (tiros a distancia)
- **Inimigos:** Duendes e Dragões (ataques à distância com chamas)
- **Objetivo:** Sobreviver o máximo possível e alcançar a maior pontuação
- **Plataforma de desenvolvimento:** Construct 3

## 🕹️ Como Jogar

Você pode jogar **Wizard Survival** diretamente pelo link abaixo:

👉 **[Clique aqui para jogar Wizard Survival](https://juliarezendefacef.itch.io/jogomagofacef)**


- **Movimentação:** Use as teclas **W, A, S, D** ou as **setas direcionais** para mover o mago.
- **Ataque:** Pressione lado esquerdo do mouse na tela (versão mobile) para lançar magias.
- **Objetivo:** 
  - Elimine os **duendes** e **dragões** antes que cheguem perto de você.
  - **Duendes** atacam de perto, então mantenha distância.
  - **Dragões** lançam **chamas à distância**, que o mago precisa **desviar** com movimentos rápidos.
- **Pontuação:** Você ganha pontos a cada inimigo derrotado e ao sobreviver mais tempo.

## 🧱 Funcionalidades

- Sistema de movimentação e combate do mago
- Ataques com animações e efeitos visuais
- Sistema de pontuação baseado em sobrevivência e inimigos derrotados
- Integração com banco de dados SQL para registrar e exibir o ranking dos jogadores
- Interface com tabela de classificação dinâmica

## 💾 Banco de Dados

- **Tipo:** SQL (Firewall)
- **Uso:** Armazenamento de pontuação e nomes dos jogadores
- **Funções implementadas:**
  - Consulta do Ranking de jogadores
  - Ordenação por pontuação

## 🖼️ Prints da Aplicação e Banco de Dados


<img width="1146" alt="Captura de Tela 2025-04-30 às 22 54 34" src="https://github.com/user-attachments/assets/657e1c8b-718e-436e-86f7-de08732ad496" />
<img width="1180" alt="Captura de Tela 2025-04-30 às 22 54 18" src="https://github.com/user-attachments/assets/1544bfcc-989b-4465-b693-41ae13807c1c" />


## 🧙‍♂️ Tabela de Sprites do Jogo

| Sprite               | Imagem                                 | Tipo                   | Função e Comportamento                                                                 |
|----------------------|-----------------------------------------|-------------------------|----------------------------------------------------------------------------------------|
| **Mago Principal**   |![Mago](./sprites/mago.png)| Personagem Jogável      | Controlado pelo jogador. Lança magias para derrotar inimigos. Movimenta-se livremente. |
| **Duende Inimigo**   | ![Duende](./sprites/duende.png)         | Inimigo (corpo a corpo) | Aproxima-se rapidamente. Se encostar no mago, causa morte.                             |
| **Dragão**           | ![Dragão](./sprites/dragao.png)         | Inimigo (ranged + melee)| Lança chamas à distância e causa dano ao encostar no mago.                             |
| **Magia do Mago**    | ![Magia](./sprites/magia.png)           | Projétil do Jogador     | Disparada pelo mago. Elimina inimigos ao colidir com eles.                             |
| **Chama do Dragão**  | ![Chama](./sprites/chama.png)           | Projétil do Inimigo     | Lançada pelo dragão. Se atingir o mago, causa dano ou morte imediata.                  |
| **Efeito de Impacto**| ![Efeito](./sprites/efeito.png)         | Efeito Visual           | Aparece no momento em que a magia acerta um inimigo, indicando o impacto.              |

Este projeto foi desenvolvido como parte de um trabalho acadêmico e não está aberto para contribuições externas no momento. Sugestões e feedbacks são bem-vindos 

## Por Julia 





