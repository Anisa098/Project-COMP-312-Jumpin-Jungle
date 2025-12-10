# Jumpin' Jungle Game
An interactive Jumpin' Jungle Game built with JavaScript, HTML, and CSS. Let's come together to contribute or play!
## Presentation


# Mission Statement

Our mission for this project:
- Create an open-source project that shows an interactive and engaging theme
- Looked at the components of Icy Tower to transform a nature aesthetic and rebranded to Jumpin’ Jungle
- Strengthen our skills with code, GitHub, and collaboration
- Updated the assets of the game and realigned the structure
- We practiced real open-source contribution by testing and documenting our findings

# Overview of Improvements Made

Within this project, we began by forking the original Icy Tower open-source game. The goal when looking through the games layout was navigating how to redesign the game to Jumpin' Jungle. This entailed to use to restructure the layout of the game's login page, homepage, instructions, new game, game scores, and other graphical aspects. The following was done for the changes completed:

## Visuals
- Rebranded the entire UI to a nature theme
- Planned out what new characters can match the theme
  Steps for redesigning characters:
  1. Agreed upon what insects would be the characters
  2. Drew out the characters by hand on a platform called Notability
     - Characters: Ladybug, Bumblebee, and a Butterfly
  3. Integrated the new graphics into the game accordingly to the HTML and CSS code
- Updated the homepage layout, login form, and color palette

## Gameplay Levels
In the game, the user is given three different levels for Beginner, Advanced, and Champion. These are on a range from easy to hard. In this feature, we ensure that our improvements follow through each level, especially with our characters. Also, the user is provided with instructions that associate with our modernized game of what three steps they should take to play.

# Testing Procedure
For the testing, Anisa manually tested it to make sure that our changes did not break paths or the gameplay.

## Team Contributions
Anisa was the main developer. She did the following:
1. Designed the new Jumpin Jungle logo and badge
2. Created and integrated all of the new characters (Ladybug, Butterfly, Bumblebee)
3. Updated the homepage, score pages, instructions, login, title, and character selections
4. Fixed all broken paths for images, CSS, and JavaScript
5. Reorganized the repo for the file structure and improved all documentation
6. Resolved the multiple Git merge conflicts and learned to manage asset integration
7. Updated the instructions page with the associated screenshots

Sydney was also a developer. She did the following:
1. Helped with the layout of the game
2. Gave ideas on the theme and direction of the possible characters
3. Assisted with updating the layout and the font colors
4. Worked on visual improvements, like adding a background for our board.

We both did the following together;
1. Selected the Jumpin' Jungle theme
2. Collaborated on weekly reports that Anisa sent over every Friday
3. Performed manual testing and debugging
4. Worked on rebranding and asset planning


## Results from Testing
![image](https://github.com/Anisa098/Project-COMP-312-Jumpin-Jungle/blob/main/image/Commits.png)
![image](https://github.com/Anisa098/Project-COMP-312-Jumpin-Jungle/blob/main/image/Contributors.png)
### Homepage 
- **ACTION** -> Open 'home-page.html'
- **Expected Result** -> Jumpin Jungle Logo, login button, login form, and navigation links display correctly.
### Registration and Login
- **ACTION** -> Register a new player and log in with a valid email.
- **Expected Result** -> Form accepts the valid email and takes them back to the homepage to welcome them into the game!
### Main Page
- **ACTION** -> When you click on the logo on the home page, you will see three sections with instructions, a new game, and game scores.
- **Expected Result** -> When you click on the badge after logging in, you will get to the main page.
### Character Selection 
- **ACTION** -> When you open 'characters.html', you will be given the option to choose Ladybug, Butterfly, or Bumblebee.
- **Expected Result** -> All three characters are displayed correctly and the selected character is passed into the game.
### Gameplay
- **ACTION** -> Start a new game at each difficulty level (Beginner, Advanced, Champion).
- **Expected Result** -> Background loads, platforms move at the correct speed for the levels, and the selected character appears and can jump between platforms.
### Score Page
- **ACTION** -> Finish a game and view the scores page.
- **Expected Result** -> "High Score" and "Your Score" sections update correctly and show the latest scores.
### Navigation 
- **ACTION** -> Use all navigation buttons, like in the upper right corner, where there is a home icon and an arrow. These features allow the user to go to the Homepage, Instructions, New Game, and Back to the screen they were on before. 
- **Expected Result** -> Each button leads to the correct pathway with no broken links.



# Installation
1. Clone the repository to your local machine:
git clone [https://github.com/Anisa098/Project-COMP-312-Jumpin-Jungle.git]
3. **Open** `Home-page.html` in your preferred web browser.
4. **Register** for the game, enter your name and a valid email and password, and proceed.
5. Choose new game
6. Choose your favorite character

![image](https://github.com/Anisa098/Project-COMP-312-Icy-Tower/blob/main/image/InstructionsCharacters.png) 

6. Choose your level.
The level influences the speed at which the tower blocks are moving and the distance between every two blocks.

![image](https://github.com/Anisa098/Project-COMP-312-Icy-Tower/blob/main/image/GameLevels.png) 

7. Start playing!!!
This is the instructions for the game, you can find them also in the project itself

![image](https://github.com/Anisa098/Project-COMP-312-Icy-Tower/blob/main/image/InstructionsForReadME.png)

### If you find this project helpful or interesting, please give it a <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/5263c3c4-c0f7-4fea-9901-ea084be83615/d9izh8z-bc267973-93af-48ee-a6a6-4ee6c9225bd1.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzUyNjNjM2M0LWMwZjctNGZlYS05OTAxLWVhMDg0YmU4MzYxNVwvZDlpemg4ei1iYzI2Nzk3My05M2FmLTQ4ZWUtYTZhNi00ZWU2YzkyMjViZDEuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.EXdtHcY0K3_YAE6xErW8kOB7M5LqSo9eBgkjhdOgd9s" width="50px">. It means a lot to us!

## Project Structure
The Jumpin' Jungle project is structured as follows:

```graphql
./Jumpin-Jungle/*
  ├─ css/     - # Contains the CSS files for styling the game interface.
  |
  ├─ html/    - # Contains the HTML files for the game.
  |  └─ tower.html - # The actual game interface
  |
  ├─ images/  - # Contains all the images for the project.
  |
  ├─ js/      - # Contains the JavaScript files that power the game logic.
  |
  ├─ CODE_OF_CONDUCT.md
  ├─ LICENSE
  └─ README.md
```

- Note: every html file has css file and js file with its name, they power it and style it, the html files have links for theirs

## Contributing
We welcome contributions from the community to help improve the Jumpin' Jungle project as it expands over the Icy Tower. If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
3. Make your changes and ensure they are working properly.
4. Commit your changes:
5. Push your changes to your forked repository:
6. Open a pull request on the main repository, describing your changes and explaining why they are valuable.

Please ensure that your contributions adhere to our [Code of Conduct](CODE_OF_CONDUCT.md).

## Contributers
Thank you to:

<a href="https://github.com/chavi362/Icy-Tower/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=chavi362/Icy-Tower" />
</a>

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
If you have any questions, suggestions, or issues regarding the Icy Tower Game, please feel free to reach out to us through the [Issues](https://github.com/chavi362/Icy-Tower/issues) section of this repository.

Enjoy the game!
