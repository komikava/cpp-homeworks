# Quadrilateral Hierarchy Program

This program calculates the perimeter and area of quadrilaterals based on their vertices. It uses inheritance to model different types of quadrilaterals.

## Classes

- **Point**: Represents a point with x and y coordinates.
- **Quadrilateral**: Abstract class with methods `perimeter()`, `area()`, and `display()`.
- **Trapezoid**: Derived from `Quadrilateral` to calculate the perimeter and area of a trapezoid.
- **IsoscelesTrapezoid**: Derived from `Trapezoid` for isosceles trapezoids with overridden display method.

## Usage

1. Enter the coordinates of the quadrilateral's vertices.
2. The program calculates and displays the perimeter and area.

### Example Output:

Isosceles Trapezoid: Vertices: (0,0) (4,3) (6,3) (2,0) Perimeter: 12.16 Area: 12

Trapezoid: Vertices: (1,1) (3,4) (7,4) (8,1) Perimeter: 12.28 Area: 9
