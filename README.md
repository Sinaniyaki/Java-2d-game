# Dead City: Chronicles
> A 2D post-apocalyptic game built with Java.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Dead City: Chronicles is a 2D survival game set in a post-apocalyptic world. I took some elements from the walking dead tv show like the soundtrack and name of the character. you navigate through the desolate cityscape, facing challenges and finding keys.

## Features
- Immersive 2D graphics
- Challenging gameplay
- Inventory system for collecting and using survival items.

## Installation

Before running Dead City: Chronicles, ensure you have [Maven](https://maven.apache.org/) installed on your system. Follow these steps to set up the game:

1. Open your terminal or command prompt.
2. Navigate to the `dead-city` directory where you've cloned the repository:
   ```shell
   cd dead-city```
   
Run the following command to clean the project and install dependencies:

```mvn clean install```

Once the build is complete and successful, you can run the game using:

```mvn exec:java -D"exec.mainClass=com.group22.Main"```