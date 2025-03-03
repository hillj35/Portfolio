---
title: "Graphics Portfolio"
layout: splash
permalink: /graphics/
intro: 
  - title: Graphics Portfolio
ICEngine:
  - title: ICEngine
    image_path: assets/images/portfolio/ICEngineCrop.webp
    excerpt: "ICEngine is a WIP game engine built in C++ and [Vulkan](https://www.vulkan.org/). The engine currently supports building simple scenes with directional and point lighting, loading models, and basic PBR materials."
    url: https://github.com/IceCavern-Games/ICEngine
    btn_label: "Source Code"
    btn_class: "btn--light-outline btn--small"
voxel:
  - title: Voxel Renderer
    image_path: assets/images/portfolio/Voxel.png
    excerpt: "I built a simple Voxel Renderer in C++ and [OpenGL](https://www.opengl.org/). [MagicaVoxel](https://ephtracy.github.io/) models are parsed and converted to a mesh for rendering. I also use a normal based outline post-processing shader to add some stylization."
    url: https://github.com/hillj35/VoxelRenderer
    btn_label: "Source Code"
    btn_class: "btn--light-outline btn--small"
maze_corp:
  - title: First Day at Maze Corp
    image_path: assets/images/mazecorp/thumbnail.png
    excerpt: "First Day at Maze Corp was made in a week for [Brackeys Game Jam 2025.1](https://itch.io/jam/brackeys-13). My goal was to make something that visually stands out from other entries using [Unity's Scriptable Render Pipeline](https://unity.com/features/srp) to build a custom post-processing effect. You can read more about all the graphics work I did on this game [here!](/blog/maze-corp-graphics/)"
    url: https://github.com/IceCavern-Games/BrackeysGameJam2025.1
    btn_label: "Source Code"
    btn_class: "btn--light-outline btn--small"
---
{% include feature_row id="intro" type="center" %}
{% include feature_row id="maze_corp" type="left" %}
{% include feature_row id="ICEngine" type="left" %}
{% include feature_row id="voxel" type="left" %}