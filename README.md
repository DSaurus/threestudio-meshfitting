# threestudio-meshfitting
A simple extension of threestudio, which enables using neural representation to fit a 3D mesh.

# Installation
```
cd custom
git clone https://github.com/DSaurus/threestudio-meshfitting.git
```

# Quick Start
```
python launch.py --config custom/threestudio-meshfitting/configs/mesh-fitting.yaml --train system.geometry.shape_init="mesh:custom/threestudio-meshfitting/assets/a_Bulbasaur.obj" system.guidance.geometry.shape_init="mesh:custom/threestudio-meshfitting/assets/a_Bulbasaur.obj"
```
