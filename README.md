<img src="https://github.com/matejstastny/pokemon/blob/main/assets/icon.png?raw=true" alt="Project icon" width="20%" align="right">

# Pokemon Game

A terminal text-based Java game where you can create and manage your own Pokemon.

## Features

- Create your own account with password protection (AES encrypted) so no one can access your Pokemon.
- Choose a starter Pokemon and give it a custom name.
- Evolve your Pokemon.
- Save your Pokemon and resume your session next time you launch the game.
- Unlimited save slots - manage multiple Pokemon per account.

## Pokemon Evolution Lines

| Starter   | Evolutions       | Element  |
| --------- | ---------------- | -------- |
| Pichu     | Pikachu → Raichu | Electric |
| Eevee     | Flareon          | Fire     |
| Bulbasaur | —                | Seed     |
| Mew       | Mewtwo           | Normal   |

## Commands

Once inside the game, use these commands:

| Command          | Description                          |
| ---------------- | ------------------------------------ |
| `stats`          | Show your Pokemon's stats            |
| `ability 1`      | Use your Pokemon's first ability     |
| `ability 2`      | Use your Pokemon's second ability    |
| `image`          | Display your Pokemon's ASCII art     |
| `evolve`         | Evolve your Pokemon                  |
| `save pokemon`   | Save your current Pokemon            |
| `new pokemon`    | Create a new Pokemon (saves current) |
| `swich pokemon`  | Switch to another saved Pokemon      |
| `delete pokemon` | Delete current Pokemon               |
| `delete account` | Delete your account                  |
| `exit`           | Exit (with optional save)            |

## Installation

Download the `.jar` package from the [latest release](https://github.com/matejstastny/pokemon/releases/latest) and run it with this command:

```bash
java -jar pokemon.jar
```

## Building from Source

Requires Java 8 or higher.

1. Clone the repository:

```bash
git clone https://github.com/matejstastny/pokemon.git
cd pokemon
```

2. Build and run:

**macOS / Linux:**

```bash
sh build.sh
java -jar ./build/pokemon.jar
```

**Windows:**

```bat
call build.bat
java -jar build\pokemon.jar
```

## Credits

- Characters from the Pokemon franchise by Nintendo
- ASCII art sourced from [emojicombos.com](https://emojicombos.com/pokemon-dot-art)
