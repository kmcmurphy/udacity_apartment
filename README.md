# Udacity Apartment Starter Project

This is the build for project 2. 

## Project Retrospective
I tried various lower light map resolution settings and wasn’t happy with the results. Tried cranking it up to 500 and increasing the size to 2048 and got the smoother shadows and less light bleed than at the lower settings - while still outputting 60fps. Final settings we as stated in the project specifications at the 80 texel resolution. 

Overall, the project took about 12 hours to complete. Much of this time was spent waiting for light maps to render. I enjoyed seeing how the different settings could radically change the feel of the scene. I feel that architectural renderings have a big future in VR for immersing clients into environments before a building is ever started. I did get hung up in trying to make the globe spin, only to find one item I had turned on that was causing the globe to spin on scene load. I also had to create a shader to allow both sides of the plant leaves (front/back) to render two-sided. Once that was fixed, it worked fine.

## Credits
- Dining table, chairs: [Chalet Style Furniture](https://assetstore.unity.com/packages/3d/props/furniture/chalet-style-furniture-31966)
- Couch, TV table, bookshelf and vase: [Big Furniture Pack](https://assetstore.unity.com/packages/3d/props/furniture/big-furniture-pack-7717)
- TV: [Wall TV Set](https://assetstore.unity.com/packages/3d/props/electronics/wall-tvset-8468)
- Plant: [Small Plants](https://assetstore.unity.com/packages/3d/vegetation/plants/small-plants-6930)
- Ceiling lights: [Free PBR Lights](https://assetstore.unity.com/packages/3d/props/interior/free-pbr-lamps-70181)
- Tile backsplash textures: [Bricks'n'Tiles](http://www.bricksntiles.com/textures/) 

## Software Versions
- Unity: Version 2017.1.0f3 Personal
- GVR: Version: 1.60.0 (auto-installed with Unity)
