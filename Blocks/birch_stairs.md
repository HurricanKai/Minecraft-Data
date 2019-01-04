# Birch Stairs\n
TextId: birch_stairs\n
MinId: 4965\n
MaxId: 5044\n
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