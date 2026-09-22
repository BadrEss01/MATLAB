# MATLAB robotics visualization

> **Coursework** · Transforms and visualization exercises
>
> [Selected projects](https://github.com/BadrEss01/BadrEss#selected-projects) · [Coursework](https://github.com/BadrEss01/BadrEss/blob/main/COURSEWORK.md)

Coursework exploring robot geometry, coordinate frames and hierarchical transformations.

## Contents

- `scara robot/`: a robot visualization and animation script, revolute/prismatic transform helpers, frame plotting and geometric link primitives.
- `spaceship/`: object-hierarchy visualization examples.

## Run the robot visualization

From MATLAB, set the repository as your current folder, then run:

```matlab
cd('scara robot')
make_scara_robot
```

Keep the helper functions on the MATLAB path. The script uses MATLAB graphics functions such as `hgtransform` and `makehgtform`; Octave compatibility has not been established.

This is a visualization exercise, not a physical robot controller. MATLAB execution has not been revalidated in the current maintenance environment. Source folders are preserved so relative function lookup continues to work.

[Portfolio](https://github.com/BadrEss01/BadrEss) · [Coursework index](https://github.com/BadrEss01/BadrEss/blob/main/COURSEWORK.md)
