# Rectangle Generator

This C++ program generates a specified number of rectangles with random positions, dimensions, and orientations.


## Usage

1. Upon running the program, it will prompt you to enter the number of rectangles you want to generate.
2. Once you provide the input, the program will generate the specified number of rectangles with random properties.
3. The properties of each rectangle (x coordinate, y coordinate, length, width, and orientation) will be displayed on the console.

## Code Structure

- `rectangle` Struct: Defines a structure to represent a rectangle with properties like position (x, y), dimensions (length, width), and orientation (theta).

- `recGen` Function: Generates 'n' rectangles with random properties including position, dimensions, and orientation.

- `occlusionAngle` Function:  for calculating occlusion angle.

- `main` Function: Prompts the user for input, calls the `recGen` function to generate rectangles, and displays the properties.

