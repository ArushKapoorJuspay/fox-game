# Fox-agotchi

A simple Tamagotchi-like game where you take care of a digital pet fox. Keep it happy, fed, and clean to watch it thrive!

## Live Demo

You can play the game here: [https://arushkapoorjuspay.github.io/fox-game/](https://arushkapoorjuspay.github.io/fox-game/)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed on your machine.

### Installation

1.  Clone the repo:
    ```sh
    git clone https://github.com/ArushKapoorJuspay/fox-game.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd fox-game
    ```
3.  Install NPM packages:
    ```sh
    npm install
    ```

### Running the Game

To start the game, run the following command. This will start a development server and open the game in your default browser.

```sh
npm run dev
```

## How to Play

The goal of the game is to keep your pet fox alive and happy. The fox has several needs that you must attend to:

-   **Feeding**: When the fox gets hungry, you must feed it by clicking the `fish` icon.
-   **Cleaning**: The fox will occasionally poop. Clean it up by clicking the `poop` icon to prevent the fox from getting sick and dying.
-   **Weather**: You can change the weather by clicking the `weather` icon. This will cycle through day, night, and rain.

The fox goes through different states:

-   **Hatching**: The game starts with an egg that hatches into a fox.
-   **Idling**: The fox is content.
-   **Sleeping**: The fox sleeps during the night.
-   **Hungry**: The fox needs to be fed.
-   **Pooping**: The fox has made a mess that needs cleaning.
-   **Celebrating**: The fox is happy after being fed or cleaned.
-   **Dead**: If you neglect the fox's needs, it will die.

## Technology Stack

-   **JavaScript**: Core game logic.
-   **HTML5/CSS3**: Structure and styling of the game.
-   **Parcel**: Web application bundler for development.
-   **ESLint/Prettier**: For code linting and formatting.
