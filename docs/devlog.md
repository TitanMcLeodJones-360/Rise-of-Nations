# Rise of Nations Development Journal

**Date:** 6/8/2026

## Topic: Variables and Functions

Today I learned about variables in C++. Variables are named locations in memory that store data. They allow a program to save information that can be used and modified later.

As an experiment, I created two integer variables:

```cpp
int x = 42;
int y = 32, z = 40;
```

I then used:

```cpp
std::cout << x + y + z;
```

The program output `113`, showing that variables can be used in calculations and expressions.

### Connection to Rise of Nations

I think variables will be extremely important for my text-based strategy game, *Rise of Nations*. Variables could store information such as:

* The country selected by the player
* Amount of oil
* Amount of metal
* Amount of food
* Population
* Military strength
* Money
* Technology level

For example:

```cpp
int oil = 100;
int metal = 50;
int population = 1000;
```

These values could change throughout the game based on player decisions and events.
## Additional Concepts Learned

### Variable Assignment and Initialization

Today I also learned about variable assignment and initialization. While these concepts are not major features of the program itself, they are important for keeping code organized and ensuring variables start with the correct values.

I explored several initialization styles, including:

```cpp
int population = 1000;      // Copy initialization
int resources(500);         // Direct initialization
int military{100};          // List initialization
```

As I continue developing *Rise of Nations*, I believe direct initialization and list initialization may be useful for setting up countries, resources, and other game data in a clear and organized manner.

### User Input with std::cin

I briefly explored user input using `std::cin`. I created a simple program that accepts input from the user and then displays it back to the screen.

```cpp
int x;
std::cin >> x;
std::cout << x;
```

Although simple, this concept will be extremely important for *Rise of Nations*. User input will eventually allow players to select countries, make diplomatic decisions, manage resources, and interact with the game world.

### Constants and Mathematical Values

I also learned about commonly used mathematical and scientific constants such as:

* Pi (π)
* Phi (φ)
* Gravity (g)

At the moment, I do not see a direct use for these values in *Rise of Nations*. However, they may become useful in future projects, particularly my calculator project, where mathematical formulas and calculations will play a larger role.


### Reflection

Today's lesson helped me understand that variables are the foundation of storing game data. Every country in *Rise of Nations* will need data associated with it, and variables provide a way to save and manipulate that information.

While today's topics were foundational, they helped me understand how programs store information, receive input from users, and organize data. These concepts will serve as building blocks for larger systems as I continue learning C++ and developing *Rise of Nations*.

I also learned that variables can participate in mathematical operations, allowing resources and statistics to increase or decrease during gameplay.

### Next Steps

* Learn more about data types (`int`, `double`, `char`, `bool`, `string`)
* Learn how user input works with `std::cin`
* Learn functions and how they organize code into reusable pieces
* Begin thinking about how countries and resources will be represented in the game
