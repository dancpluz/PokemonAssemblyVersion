<picture>
  <img src="https://user-images.githubusercontent.com/64702639/222986019-f645f57e-ac03-4276-9da3-345a3dd31d1a.png" width="30%"/>
</picture>

# 📚 About

<picture>
  <img src="https://user-images.githubusercontent.com/64702639/222988967-26dee8af-943d-47c0-b9a8-7f3fb0f3835c.gif" align="right" width="400"/>
</picture>

Group project made in University of Brasília, for the course "Organização e Arquitetura de Computadores" (Computer Architecture & Organization), in which we learned about machine language assembly RISC-V, types of CPU, datapaths and many hardware in-depth concepts. The project proposal was to recreate the Game Boy Advance game Pokemón FireRed with assembly RISC-V. We used [RARS](https://github.com/TheThirdOne/rars) and VSCode to program, and [FPGRARS](https://github.com/LeoRiether/FPGRARS) to execute the game. Also, we adapted the game so it could run in an FPGA DE1-SoC kit, there were many limitations with functions and storage, but we worked around it. Making a game with assembly language is not practical at all, but it gave us a good understanding of how the hardware works and many programming concepts, how to handle problem-solving situations and manage teamwork. 

You can find the more descriptive report, in scientific article model, only in Portuguese [here](Grupo7_Trabalho.pdf).

## 🎮 Game

<picture>
  <img src="https://user-images.githubusercontent.com/64702639/222989664-66eee7dd-ae6a-4f79-86bf-90c4768f1055.gif" align="right" width="400"/>
</picture>

- Story with dialog boxes
- Soundtrack
- Usable items and money system
- Different types and battle moves
- 6 unique pokemons
- Map and structures you can enter
- Battles with AI pokemons
- Battle scenes with action menu
- Player movement
- Interactive NPCs
- Pause menu
- Special terrains with random pokemon generation

## 🖼 Design

<picture>
  <img src="https://user-images.githubusercontent.com/64702639/223018760-caef73ec-f7e2-4851-9ff2-0d638a586b07.png" align="right" width="200"/>
</picture>

We designed almost every aspect of the game based on our university culture, pokemons are inspired from animals that we find in campus, with a lot of references and inside jokes. A lot of game design concepts we brought from the original game itself, like the battles, the maps, and gave a bit of our own twist. The story is about a freshman who finds himself trapped in the city of OACapulco and the only way to escape is to defeat the bus driver in a pokemon battle, to do this, he enlists the help of Professor Lamar to instruct him and give him his pokemon to battle, then the freshman must venture around the city chasing wild pokemons until he can buy the ticket and fight the bus driver.

## 🛠 Built With

<a href="https://github.com/topics/riscv">
  <img src="https://raw.githubusercontent.com/github/explore/592cc967e9ebbc60f2a532f577efa072f4bfccaa/topics/riscv/riscv.png" width="100"/>
</a>

## 👥 Group

- **[Vinícius](https://github.com/Vini-ara):** Game logic, objects, print sprites
- **[Gustavo](https://github.com/GMTonnera):** Battles, AI, gameplay
- **[Daniel](https://github.com/dancpluz):** Sprites, maps, and story design, report
- **[Lucas](https://github.com/Amaralfaria):** Audio and map implementation
- **Jasiel:** Report

## 🤝 Contributions 

- **Prof. Lamar:** Teacher who taught us and proposed the project
- **Monitores:** Teacher assistants that helped us so much, thanks to Thiago Tomás, Eduardo Freire, Ruan Petrus, and others that helped too

## 👨‍💻 How to Play

> Java is a prerequisite to run

1. Download the repo
2. Open the ```/src``` folder
3. Drag the file ```main.s``` to the executable ```fpgrars.exe```

or

1. Clone the repo
2. Open the ```/src``` folder
3. Run ```fpgrars main.s```

### Keybinds

- W = walk up
- A = walk left
- S = walk down
- D = walk right
- Z = interact
