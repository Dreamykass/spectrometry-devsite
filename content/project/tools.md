+++
title = "Tools and libraries used"
date = 2021-03-21
weight = 500
+++

## Languages
- rust - main/native
- rhai - scripting language

## Environment
- github - version control
- jetbrains clion - main IDE
- visual studio code - secondary IDE
- visual studio - cpu/memory profiling
- optick - cpu profiling (?)
- renderdoc - gpu profiling
- rust-analyzer - static analysis / language server
- tiled - level/scene editor

## Rust libraries
(that I directly depend on)  

#### Graphics, windowing, gui:
- winit - windowing, input
- wgpu - graphics
- wgpu_glyph - text
- iced - gui (?)
- imgui - dev/debug gui
- imgui-wgpu - imgui integration
- imgui-winit-support - imgui integration
- image - image processing
- shaderc - shader compilation

#### Architecture:
- rapier - physics
- laminar/quinn - networking (?)
- crossbeam - channels
- cgmath - math

#### Data:
- hecs - entity component system
- serde - serialization interface
- ron - serialization format (human-readable)
- bincode - serialization format (binary)
- bytemuck - data/bytes manipulation

#### Instrumentation, configuration:
- log - logging facade
- fern - logger framework
- profiling - profiling abstraction
- puffin - integrated profiler
- puffin-imgui - profiler imgui integration
- structopt - argument parsing
- toml - configuration format/parsing

#### Other:
- rand - randomness
- chrono - time
  
That's about it.

