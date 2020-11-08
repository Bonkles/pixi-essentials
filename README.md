<p align="center">
<img src="https://i.imgur.com/apQs3EL.png" alt="Frame-1-12x" width="600"></img>
</p>

:point_right: This project is a collection of essential packages for building performant, enterprise-level applications on top of the PixiJS library. It includes several optimization plugins, frequency-domain filters, display-object libraries, and mixins on the core API.

## General :package:

| Package            | Brief |
| -----------------------------------------------| ----------------------------------------------------------------------------------------------------------------------------------------------------|
| @pixi-essentials/area-allocator | 2D area allocator for managing texture space and likes |
| @pixi-essentials/bounds | axis-aligned, oriented bounding boxes |
| @pixi-essentials/gradients | generates color-gradient textures |
| @pixi-essentials/plugin-g | (unreleased) This is a plugin containing useful geometry manipulation utilities, The package also contains various types of useful geometries |
| @pixi-essentials/shader-preprocessor | (unreleased) This package provides compile-time %macro% preprocessing. You can dynamically generate shaders based on the macros value set provided & a shader template.|
| @pixi-essentials/texture-allocator | texture atlas allocator - supports render-texture, multiple image, and canvas-backed atlases |

## Performance Optimizations :racehorse:

| Package                   | Brief          |
| ------------------------- | -------------- |
| @pixi-essentials/cull | prevents rendering of objects outside of the viewable screen |
| @pixi-essentials/mixin-smart-mask| skips masking objects when do so has no effect    |
| @pixi-essentials/object-pool | object-pool for PixiJS applications, with niche features like array-allocation and garbage collection |
| @pixi-essentials/ooo-renderer | (unreleased) reorders display object rendering to maximize batching efficiency while preserving local z-order |
| @pixi-essentials/uber | (unreleased) uber-shader support |

## DisplayObject Kits :paintbrush:

| Package                   | Brief          |
| ------------------------- | -------------- |
| @pixi-essentials/conic | resolution-independent filled quadric curve rendering |
| @pixi-essentials/transformer | interactive interface for editing the transforms in groups |
| @pixi-essentials/svg   | a feature-rich SVG implementation |

## Integrations :atom_symbol:

| Package                   | Brief          |
| ------------------------- | -------------- |
| @pixi-essentials/react-bindings | This contains React components for essential display-objects, with [@inlet/react-pixi](https://github.com/inlet/react-pixi) |
