# Zookeeper

Welcome to the Zookeeper project! This Node.js application provides a simple, interactive way to check in on various animal habitats from the comfort of your own terminal. Whether you want to see a camel sunbathing, a lion roaring, or even a curious goose, this script acts as your virtual zoo tour.

## Features

- View ASCII art representations of animals in their habitats.
- Interactive prompt to select the animal habitat you wish to view.
- Easy navigation between animal habitats.
- Option to exit the program at any time.

## Requirements

- [Node.js](https://nodejs.org/)

## Installation

This application is written in TypeScript, so you'll need Node.js installed on your computer to run it. If you don't have Node.js installed, you can download it from [nodejs.org](https://nodejs.org/).

To install this project, follow these steps:

1. Clone the repository to your local machine:

```
git clone https://github.com/SonikSeven/zookeeper-typescript.git
```

2. Navigate to the cloned repository:

```
cd zookeeper-typescript
```

3. Install the required dependencies:

```
npm install
```

## How to Run

To run the program, follow these steps:

1. Open a terminal and navigate to the directory where the script is located.
2. Run the following command:

```
npx ts-node index.ts
```

## How to Use

Follow the on-screen instructions. You will be prompted to enter the number corresponding to the habitat you wish to view. Available options are:

- `0` - Camel
- `1` - Lion
- `2` - Deer
- `3` - Goose
- `4` - Bat
- `5` - Rabbit

Enter `exit` at any prompt to leave the zoo and end the program.

## Example

```plaintext
Please enter the number of the habitat you would like to view: 1
```

The lion habitat ASCII art will be displayed.

## License

This project is licensed under the [MIT License](LICENSE.txt).
