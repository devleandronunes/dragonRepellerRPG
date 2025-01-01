# Dragon Repeller RPG (In English|Em Inglês)

## WebSite: https://devleandronunes.github.io/dragonRepellerRPG/

## Overview
Dragon Repeller is a text-based RPG game where players embark on a journey to defeat a dragon threatening their town. Players can earn gold, buy weapons, fight monsters, and ultimately challenge the dragon.

## Features
- Dynamic gameplay with multiple locations: town square, store, cave, and combat scenes.
- Inventory system with purchasable and breakable weapons.
- Varied enemies, each with unique health and levels.
- A hidden "easter egg" mini-game for extra fun.

## Gameplay Mechanics

### Player Stats
- **XP**: Experience points gained by defeating monsters.
- **Health**: Player’s health decreases during fights; the game ends if it reaches 0.
- **Gold**: Earned by defeating monsters and used to purchase items.
- **Weapons**: Start with a stick and upgrade to powerful weapons like a sword.

### Locations
1. **Town Square**: Starting point of the game. Choose your next action.
2. **Store**: Buy health or upgrade your weapon.
3. **Cave**: Fight various monsters to gain XP and gold.
4. **Combat Scene**: Engage in battles with monsters.
5. **Victory/Defeat Scenes**: Celebrate victory or restart after defeat.
6. **Easter Egg**: A mini-game with random number guessing.

### Monsters
- **Slime**: Low-level monster with 15 health.
- **Fanged Beast**: Mid-level monster with 60 health.
- **Dragon**: High-level boss with 300 health.

### Weapons
- **Stick**: Starting weapon with 5 power.
- **Dagger**: Medium weapon with 30 power.
- **Claw Hammer**: Strong weapon with 50 power.
- **Sword**: Ultimate weapon with 100 power.

## How to Play
1. **Start the Game**: Open the `index.html` file in your browser.
2. **Navigate Locations**: Use buttons to move between locations.
3. **Combat**: Fight monsters to earn XP and gold.
4. **Upgrade**: Buy health and better weapons in the store.
5. **Defeat the Dragon**: Win the game by defeating the dragon in combat.

## Code Structure
- **HTML**: The main structure of the game interface.
- **CSS**: Styling for game elements.
- **JavaScript**: Core logic, including:
  - `update(location)`: Updates the game state based on location.
  - `buyHealth()`: Allows players to purchase health.
  - `buyWeapon()`: Lets players upgrade their weapons.
  - `fight()`: Handles combat mechanics.
  - `easterEgg()`: Initiates the hidden mini-game.

### Example Gameplay
#### Starting Stats:
- XP: 0
- Health: 100
- Gold: 50
- Inventory: ["stick"]

#### Sample Actions:
1. Go to the store and buy health.
2. Enter the cave and fight a slime.
3. Upgrade your weapon to a dagger.
4. Challenge the dragon and win!

## How to Run
1. Clone the repository or download the project files.
2. Open the `index.html` file in a web browser.
3. Start playing by interacting with the buttons.

## License
This project is licensed under the MIT License.

----------------------------------------------------------------------------------------------------------------------------------------------------

# RPG - Dragon Repeller (Em Português|In Portuguese)

## Visão Geral
Dragon Repeller é um RPG simples desenvolvido em JavaScript que desafia os jogadores a explorar diferentes áreas, enfrentar monstros e, finalmente, derrotar um dragão para salvar a cidade. Os jogadores podem acumular experiência, ouro, melhorar suas armas e administrar a saúde durante o jogo.

---

## Recursos
- Explorar diferentes locais como a praça da cidade, loja e caverna.
- Comprar itens como saúde e armas.
- Enfrentar monstros como slime, fera com presas e um poderoso dragão.
- Jogar um minijogo secreto de "easter egg".
- Possibilidade de vencer o dragão ou perder a saúde completamente.

---

## Estrutura do Projeto

### Arquivos
- **index.html**: Contém o layout da interface do usuário.
- **styles.css**: Define o estilo do jogo.
- **script.js**: Contém toda a lógica do jogo.

---

## Funcionamento

### Variáveis Principais
- `xp`: Experiência acumulada pelo jogador.
- `health`: Saúde do jogador.
- `gold`: Ouro do jogador.
- `inventory`: Inventário do jogador, contendo armas.
- `currentWeapon`: Representa a arma atual.

### Locais
Os locais são definidos em um array `locations` e incluem:
- **Praça da Cidade**: Ponto inicial do jogo.
- **Loja**: Comprar itens e armas.
- **Caverna**: Enfrentar monstros para ganhar experiência e ouro.
- **Combate**: Enfrentar monstros em combate.
- **Vitória/Derrota**: Resultados do jogo.

### Monstros
Os monstros estão definidos no array `monsters` e incluem:
- Slime: Nível 2.
- Fera com Presas: Nível 8.
- Dragão: Nível 20.

---

## Como Jogar
1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em um navegador.
3. Utilize os botões na tela para:
   - Comprar itens na loja.
   - Enfrentar monstros na caverna.
   - Derrotar o dragão para vencer o jogo.

### Controles
- **Botões**: Três botões principais permitem ao jogador navegar e interagir com o jogo.
- **Estatísticas**: Mostram experiência, saúde e ouro.
- **Combate**: Escolha entre atacar, desviar ou fugir.

---

## Funcionalidades das Funções

### Locais
- `goTown()`: Vai para a praça da cidade.
- `goStore()`: Acessa a loja.
- `goCave()`: Entra na caverna.

### Combate
- `fightSlime()`, `fightBeast()`, `fightDragon()`: Inicializam combates com monstros.
- `attack()`: Realiza um ataque no combate.
- `dodge()`: Tenta desviar de ataques.

### Gerenciamento de Recursos
- `buyHealth()`: Compra saúde.
- `buyWeapon()`: Compra uma arma.
- `sellWeapon()`: Vende uma arma.

### Eventos de Jogo
- `defeatMonster()`: Ganha experiência e ouro ao derrotar monstros.
- `lose()`: Encerramento do jogo ao perder toda a saúde.
- `winGame()`: Encerramento do jogo ao derrotar o dragão.

### Easter Egg
- `easterEgg()`, `pick()`: Acessa um minijogo secreto onde é possível ganhar ou perder recursos.

---

## Exemplo de Jogabilidade
Ao iniciar o jogo, o jogador tem 100 de saúde, 50 de ouro e uma arma inicial ("stick"). Eles podem:
1. Comprar saúde ou armas na loja.
2. Explorar a caverna para enfrentar monstros.
3. Acumular recursos e preparar-se para lutar contra o dragão.

### Possíveis Resultados:
- **Vitória**: Derrotar o dragão.
- **Derrota**: Perder toda a saúde.

---

## Licença
Este projeto é licenciado sob a Licença MIT.
