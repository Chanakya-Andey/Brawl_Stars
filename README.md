# Brawl Stars Analysis

![Screenshot 2022-07-08 at 15 08 15](https://user-images.githubusercontent.com/81629418/177964197-f592ca03-31e3-450b-b2d8-e92ec62da75b.png)

## Introduction
Brawl Stars is a multiplayer online battle arena and third-person hero shooter video game developed and published by the Finnish video game company Supercell. It was released worldwide on December 12, 2018, on iOS and Android. The game features various game modes, each with a different objective. Players can choose from a selection of Brawlers, which are characters that can be controlled with on-screen joysticks in a game match.
## Gameplay
In Brawl Stars, players battle against other players or AI opponents in multiple game modes. Players can choose between characters called Brawlers that they have unlocked through Boxes, the Brawl Pass, the Trophy Road, or purchased through the Shop to use in battles.

Brawl Stars has a variety of different game modes that players can choose from, each one having a different objective. Players can invite friends to play with them up to the maximum team size of the game mode.

In addition, it is possible to purchase skins with Gems or Star Points, or unlock them through the Brawl Pass, which will alter the appearance, animations, and/or sounds of Brawlers

![Screenshot 2022-07-08 at 15 02 29](https://user-images.githubusercontent.com/81629418/177963275-4fc946da-a506-4c41-9676-78457ea5e204.png)

## Report
The Notebook file contains the detailed automated report showing us the most optimal brawler to increase the rank and power accordingly to have faster progress in the game.

## Visualisations
### Scatter Plot 1
The below scatter plot is an interactive plotly plotted using number of Trophies of each brawler on y-axis and their Power on x-axis. This plot depicts the position of each brawler relative to each other in the overall picture.
- The Points in the plot depicts each Brawler colored in the order of their priority factor (Trophies / Power).
- The green line is a logarithmic curve depicting the ideal position of all Brawlers as the maximum number of Trophies a Brawler can achieve is saturated as we go up the trophy road.
- The red line is a logarithmic curve fitting the Brawlers in the plot.

![scatter_plot_1](https://user-images.githubusercontent.com/81629418/177963795-33f7ddf3-1a7e-4dc6-b0d9-5aa124cf66a5.png)

### Barh Plot
The below horizontal bar plot depicts the Brawlers' number of trophies relative to each other ordered in increasing priority factor.
This plot helps us play the Brawlers according to priority order.
- The red bars depicts the brawlers with priority factor less than 1.
- The green bars depicts the brawlers with priority factor green than 1.
- The blue bars depicts the brawlers with priority factor equal to 1.

![barh_plot_1](https://user-images.githubusercontent.com/81629418/177967435-0b9d5aac-3389-406f-8f25-527889c26e68.png)

### Scatter Plot 2
The below scatter plot helps us understand the distribution of number of trophies across all Brawlers.
We should try bring the red line and green line as close as possible to bring balance among Brawler and optimize the progress speed.

![scatter_plot](https://user-images.githubusercontent.com/81629418/177980834-522bfd2d-d5ca-43d3-8edd-7bcb14d2292b.png)
