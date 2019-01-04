# Jungle Stairs\n
TextId: jungle_stairs\n
MinId: 5045\n
MaxId: 5124\n
Hardness: 2\n
Resistance: 3\n

Num States: 80\n
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