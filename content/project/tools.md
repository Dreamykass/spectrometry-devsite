+++
title = "Tools and libraries used"
date = 2021-03-21
weight = 500
+++

## Languages
- main/native - Rust - <https://www.rust-lang.org/>  
  Star of the show.
  [Why Rust?](../../blog/why-rust)
- scripting - Rhai - <https://github.com/rhaiscript/rhai>  
  Why Rhai?

## Environment
- version control - GitHub - (private repo)
- main IDE - JetBrains CLion - <https://www.jetbrains.com/clion/>  
  Rust.
- secondary IDE - Visual Studio Code - <https://code.visualstudio.com/>  
  Opens quickly, lots of extensions.
- profiling - Visual Studio - <https://visualstudio.microsoft.com/vs/community/>  
  It's cool.
- static analysis / language server - rust-analyzer - <https://github.com/rust-analyzer/rust-analyzer>

## Rust libraries
(main ones that I directly depend on)  

#### Graphics, windowing, gui:
- `winit` - windowing, input
- `wgpu` - graphics
  Why wgpu?
- `wgpu_glyph` - text
- `iced` - gui (?)
- `imgui` - gui
- `imgui-wgpu` - imgui integration
- `imgui-winit-support` - imgui integration
- `image` - image processing
- `shaderc` - shader compilation

#### Architecture:
- rapier - physics
- laminar/quinn - networking (?)
- crossbeam - channels
- cgmath - math

#### Data:
- bytemuck - 
- serde - 
- serde... - 
- bincode - 

#### Other:
- logging facade - log
- logger - fern
- structopt - 
- rand - 
- chrono - time
  
That's about it.

