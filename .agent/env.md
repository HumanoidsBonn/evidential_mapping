# Environment

This repository is an umbrella repository containing three Git submodules.
It has no shared Python environment or root build command.

- Initialize: `git submodule update --init --recursive`
- EvidMTL environment and commands: see `evidmtl/README.md` and
  `evidmtl/environment.yml`.
- EvidKimera ROS/catkin setup: see `evidkimera/README.md`.
- Voxblox ROS/catkin setup: see `voxblox/README.md`.

Component dependencies are intentionally not installed by the umbrella
repository.
