# cub3D
### RayCasting Game
![](cub3D.gif)

### To compile:
```sh
make
```

### To start:
```sh
./cub3D map.cub
```

### Also you are able to make screenshot. Just write:
```sh
./cub3D map.cub --save
```

where map.cub is an argument which includes the ways to textures, map and colors.
Map must be closed (1).

For example:

### Valid map:

111 

101

111 

### Invalid map:

1  1

101

111

**Therefore all 0, player and sprites must be locked by 1.**

### Playing Process
 -  Movements:
WSAD
 -  Shots:
Mouse click
 -  To turn off/turn on the music use button "q"
 -  Quit ECS or X button
