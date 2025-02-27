# Change Log - @pixi-essentials/texture-allocator

This log was last generated on Tue, 27 Jul 2021 17:48:59 GMT and should not be manually modified.

## 1.0.9
Tue, 27 Jul 2021 17:48:59 GMT

### Patches

- Fix image loading logic

## 1.0.8
Tue, 27 Jul 2021 17:10:50 GMT

### Patches

- Fixes WebGL error when image is uploaded before it loads

## 1.0.7
Mon, 19 Jul 2021 16:31:57 GMT

### Patches

- Invalidate resource item and base-texture when image loads after being allocated in AtlasAllocator

## 1.0.6
Fri, 16 Jul 2021 22:26:37 GMT

### Patches

- Fix bugs in AtlasAllocator that caused textures to disappear if they were added in different frames

## 1.0.5
Thu, 17 Jun 2021 02:36:40 GMT

### Patches

- Upgrade to PixiJS 6

## 1.0.4
Sun, 31 Jan 2021 03:42:33 GMT

### Patches

- Upgrade build to output correct IIFE namespace

## 1.0.3
Sat, 26 Dec 2020 22:47:29 GMT

### Patches

- Upgrade to PixiJS 5.4.0 RC and generate a index.d.ts file.

## 1.0.2
Sat, 26 Dec 2020 21:49:41 GMT

### Patches

- Looser peer dependency versioning.

## 1.0.1
Sun, 08 Nov 2020 20:40:57 GMT

### Patches

- Initial release of texture allocators: TextureAllocator, AtlasAllocator, CanvasTextureAllocator, RenderTextureAllocator

