# VoxelBlock
A WebGL 2.0 / GLSL voxel-based raytracing game engine which implements a virtually infinite and procedurally generated world of blocks.

Playable in-browser at the following link: [VoxelBlock - rayfts](https://rayfts.go.ro/public/mc_clone/voxel_raycast.html).

## Controls
- **WASD**: move
- **Left Click + Mouse drag**: look around
- **Spacebar**: jump
- **Caps Lock**: Destroy Block
- **Right Click**: Place held block
- **1 to 6**: Change held block
  - **1**: Textured grass block
  - **2**: Bright red block (good for visualizing reflections and refractions)
  - **3**: Glass block
  - **4**: Tinted glass block
  - **5**: Mirror block
  - **6**: Tinted mirror block
- **F**: toggle flight mode
  - **Shift**: descend while in flight mode
  - **Space**: ascend while in flight mode

## Options
- **Render-distance (chunks)** - changes the number of chunks that are loaded at a time.
- **Render-distance (grid hits)** - changes the draw distance in number of blocks.
- **Bounce Limit** - changes how many times light is allowed to bounce off surfaces.
