# Azul-Game

## Description
Project made ad part of University study.
This project's main goal was to create a fully functional implementation of a board game "[Azul](https://www.youtube.com/watch?v=7ygt6qM5WdY)".

Game can be played by 2-4 players.\
Game can be played by running a server app, which starts a server on port specified in properties.\
Players can then connect to the server and register or login to an existing account.\
After connecting to the server a lobby can be created with randomly generated 5 digit-join code. \
If unfished the state of the game can be saved on the server and resumed by the host if the same players re-enter the lobby.

## Technologies
All written in Java, with network features using java.net API\
Graphical User Interface based on JavaFX 

## Screenshots
Main menu

![start](https://user-images.githubusercontent.com/92323233/224170476-79a72fb0-7c16-4efb-acf2-a182c5bf8fb4.png "Main menu")

Connecting

![connect](https://user-images.githubusercontent.com/92323233/224170715-25a125c4-f74d-41ff-b0b6-63826b3ce644.png "Connecting")

Login Screen

![login](https://user-images.githubusercontent.com/92323233/224170798-c93beac1-a1d3-4c21-97a0-4665a30ea687.png "Login Screen")

Game Connection Screen

![host](https://user-images.githubusercontent.com/92323233/224170876-aaf329cf-5db3-4981-ac2b-5fcc2712efe7.png "Game Connection Screen")

Main Board View

![game](https://user-images.githubusercontent.com/92323233/224171059-1aed527f-4064-4b01-ab74-7a7f19d146d6.png "Board View")

Board View After Few Rounds

![game1](https://user-images.githubusercontent.com/92323233/224171167-e6761f92-9abc-4d34-b4c1-6958e2512ef2.png "Board View")




## How to start
* Clone the repository
* Run the server localy by running Server.java (default port 4000 can be changed in server.properties)
* Run game app by runnig Azul.java
* Connect to the server

## Credits
* Jakub Ossowski ([GitHub](https://github.com/bilevcik))
* Miłosz Kutyła ([GitHub](https://github.com/mkutyla))
* Aleksandra Michalska
* Patryk Ogonowski
