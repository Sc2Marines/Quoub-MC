# Quoub-MC
A repo for handling my personal Datapack.

75% complete

## Setup (as a player)

**[Pick the latest release](https://github.com/Sc2Marines/Quoub-MC/releases/):**

I strongly recommend you to pick the 1.19.2.client.zip.

**Download and install Java 17 LTS:**

[Windows](https://adoptium.net/temurin/releases/?package=jdk&version=17&os=windows&arch=x64)

[Linux](https://adoptium.net/temurin/releases/?package=jdk&version=17&os=linux&arch=x64)
or OpenJDK through your package manager
```$ apt install openjdk-17-jdk```

If you don't want to take all the JDK, you can just download the JRE (JDK contains a JRE).

**Download PrismLauncher and install it:**

[Windows](https://prismlauncher.org/download/windows/)

[Linux](https://prismlauncher.org/download/)

**Add your (beurk) Microsoft's account to the launcher:**

**Import the downloaded zip (the one you have chosen on GitHub):**

"Add an instance" > "Import" > "Browse" > "Ok"

**Edit the settings of the previously imported instance:**

"Edit" > "Settings" > "Auto-detect..." > "17.0.x" > "Ok"

**Launch the instance:**

"Launch"

**Join the server:**

Normally a server is already present in the `multiplayer` section, edit it and check that it matches the given server's address.
```
public.pierrick.fr.eu.org:25565
```

## List of all things to configure (you can make a request to the owner to add some or remove some) (as a server admin).

### Server

- [X] Configure message cipher.
- [X] Configure Plasmo Voice https://plasmovoice.com/docs/server/installing/.
- [X] Configure the Discord presence bot.
- [X] Falling tree.
- [X] All other mods.
- [X] Test if Plasmo Voice is supported by Ambient Sound (if not, maybe change for Simple Voice Chat).

### Client

- [X] Read and configure client https://github.com/Aizistral-Studios/No-Chat-Reports/wiki/Configuration-Files.
- [X] Configure all other mods.

### Known bugs

#### Mod config

While clicking on these mods in the mod list, the game crashes:

- Choice Theorem's Overhauled Village.
- Epic Dungeon.
- Server Core.
- Distant Horizon.
- Longer Chat History.
