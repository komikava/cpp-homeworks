#Geometry Figure Operations

This program implements geometric operations for a square, including translation, rotation, and scaling.

## Functions

- **Move along the X-axis**: Moves the figure along the X-axis.
- **Move in arbitrary direction**: Moves the figure by a specified amount along both X and Y axes.
- **Rotate**: Rotates the figure by a given angle (in radians).
- **Scale**: Scales the figure by a specified factor.

## `Point` Class
Represents a point with coordinates.

#### Methods:
- `void print() const`: Prints the point's coordinates.

## `GeometryFigure` Class
Represents a geometric figure (square) using four points.

#### Methods:
- `void moveX(double deltaX)`: Moves the figure along the X-axis.
- `void move(double deltaX, double deltaY)`: Moves the figure in an arbitrary direction.
- `void rotate(double angle)`: Rotates the figure.
- `void scale(double factor)`: Scales the figure.
- `void print() const`: Prints the coordinates of the figure.

## Example
Input the coordinates of four points for a square and try the operations for movement, rotation, and scaling.