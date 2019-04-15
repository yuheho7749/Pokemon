# Pokemon
APCS Group Final Project for Mr. Carr (Year: 2019).
This is a open world strategy role playing game designed for personal use. Any similarities in design features and mechanics to other existing games are purely coincidences.
* Warning - This game is still in the early stages of development. Many graphics, mechanics, or features are not yet available. We also plan to convert the files into a .jar file for easy access in the final release.
* IMPORTANT - This project belong solely to the authors listed below. We welcome you to test our project and provide feedback in the "Issues" page. However, you may not distribute or reproduce all or in part of this project without our permission.
## Prerequisites
* Requires Java JDK version 8 or above
* For Java JDK 9, there is a minor visual bug due to some unknown reason (Game mechanics are functional)
* For Java JDK 11, make sure to have JavaFX installed
## Getting Started
* Windows:
1. Download and unzip the "Pokemon" zip file
2. Navigate inside the "Pokemon" folder (You should see a "Compile_And_Run.bat" file)
3. Double click the "Compile_And_Run.bat" file
4. The application should launch with default settings automatically
* Mac:
1. Download and unzip the Pokemon zip file
2. Navigate inside the "Pokemon" folder (You should see a "Compile_And_Run.bat" file)
3. Open "Compile_And_Run.bat" inside a text editor (Do not double click)
4. Copy the contents inside the "Compile_And_Run.bat" file
5. Open the terminal
6. Navigate the terminal directory to inside the "Pokemon" folder
7. Paste the contents of "Compile_And_Run.bat" in the terminal and press enter
8. The application should launch with default settings
* For custom settings when running the application [in the terminal/command prompt] (Intended for Development)
0. Compile files: "`javac -d bin src/main/*.java src/character/*.java src/map/*.java src/item/*.java src/move/*.java src/pokemon/*.java src/tile/*.java src/building/*.java src/battlemap/*.java`"
1. Default launch: "java -cp bin main.Pokemon"
2. Custom launch: "java -cp bin main.Pokemon pre:[boolean] fps:[int] scl:[int] hbx:[boolean] vis:[boolean] col:[boolean]"
## Game Controls
* ESCAPE - Force closes the program
* WASD - Movement controls (arrow keys also work)
* J - Selection button
* K - Deselection/back button
## Authors
* Joseph Ng - Initial Work and Project Contributor
* Alex Guan - Project Contributor
* John Liu - Project Contributor
* Natthapat Chianchitlert (aka Mathew) - Project Contributor
## Acknowledgments
* Course Instructor - Mr. Jeron Carr
* Inspired by Nintendo Pokemon Game (Please don't sue me. This is only a fan made project for personal uses)
