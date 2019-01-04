# Birch Stairs

TextId: birch_stairs

MinId: 4965

MaxId: 5044

Hardness: 2

Resistance: 3


Num States: 80

# States
```
Name: facing
Type: direction
Num Values: 4
Values:
    NORTH
    EAST
    SOUTH
    WEST

Name: half
Type: enum
Num Values: 2
Values:
    TOP
    BOTTOM

Name: shape
Type: enum
Num Values: 5
Values:
    STRAIGHT
    INNER_LEFT
    INNER_RIGHT
    OUTER_LEFT
    OUTER_RIGHT

Name: waterlogged
Type: bool
Num Values: 2
```