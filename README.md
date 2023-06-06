# house-of-bird
# Project README

This project contains classes and functionalities related to managing bird information, cages, and bird rooms. It provides a set of classes that represent different types of birds, cages, and bird rooms. The main purpose of this project is to create and manage bird-related objects.

## Classes

### Bird

The `Bird` class represents a generic bird. It has the following attributes:

- `ID`: A string representing the bird's ID.
- `btype`: A string representing the bird's type.
- `birth`: A string representing the bird's birth date.
- `colors`: A list of strings representing the bird's colors.
- `foodtype`: A string representing the bird's food type.
- `volume`: An integer representing the bird's volume.

The `Bird` class provides methods to validate and retrieve information about the bird, such as age, ID, type, colors, food type, and volume. It also provides comparison methods to compare birds based on their type and color count.

### Finch

The `Finch` class is a subclass of `Bird` and represents a specific type of bird called a finch. It inherits the attributes and methods from the `Bird` class and adds a `nest_building` method.

The `nest_building` method returns a list representing the bird's nest, where each element represents a part of the nest.

### Parrot

The `Parrot` class is a subclass of `Bird` and represents a specific type of bird called a parrot. It inherits the attributes and methods from the `Bird` class and adds a `find_nestbox` method.

The `find_nestbox` method returns a list representing the parrot's nest box, where each element represents a row of the nest box.

### Zebrafinch

The `Zebrafinch` class is a subclass of `Finch` and represents a specific type of finch called a zebra finch. It inherits the attributes and methods from the `Finch` class and adds a `jump` method.

The `jump` method returns a string representing the zebra finch's jumping behavior.

### Gouldianfinch

The `Gouldianfinch` class is a subclass of `Finch` and represents a specific type of finch called a Gouldian finch. It inherits the attributes and methods from the `Finch` class and adds a `sing` method.

The `sing` method returns a string representing the Gouldian finch's singing behavior along with its singing strength.

### Budgerigar

The `Budgerigar` class is a subclass of `Parrot` and represents a specific type of parrot called a budgerigar. It inherits the attributes and methods from the `Parrot` class and adds a `tweet` method.

The `tweet` method returns a string representing the budgerigar's tweeting behavior along with its tweeting strength.

### Lovebird

The `Lovebird` class is a subclass of `Parrot` and represents a specific type of parrot called a lovebird. It inherits the attributes and methods from the `Parrot` class and adds a `kiss` method.

The `kiss` method returns a string representing the lovebird's kissing behavior.

### Cage

The `Cage` class represents a bird cage. It has the following attributes:

- `ID`: A string representing the cage's ID.
- `length`: An integer representing the cage's length.
- `depth`: An integer representing the cage's depth.
- `height`: An integer representing the cage's height.
- `color`: A string representing the cage's color.
- `bird_clob`: A list of bird objects representing the birds in the cage.
- `array

### BirdRoom
The BirdRoom class represents a room that can hold multiple bird cages. It has the following attributes:

ID: A string representing the bird room's ID.
length: An integer representing the bird room's length.
depth: An integer representing the bird room's depth.
height: An integer representing the bird room's height.
cages: A list of Cage objects representing the cages in the bird room.
The BirdRoom class provides methods to add and remove cages from the bird room, as well as to retrieve information about the bird room and its cages. It also provides methods to find cages based on their ID and to calculate the total volume occupied by the birds in the room.
