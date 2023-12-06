# ComfyUI_LoadImageFromPath

## Load Image From Path
ComfyUI's built-in `Load Image` node can only load uploaded images, which produces duplicated files in the input directory and cannot reload the image when the source file is changed. `Load Image From Path` instead loads the image from the source path and does not have such problems.

Useful for automated or API-driven workflows.

The image path can be in the following format:
- Absolute path:

  `D:\ComfyUI\output\ComfyUI_00001_-assets\ComfyUI_00001_.png`

- Relative to the input directory:

  `ComfyUI_00001_-assets\ComfyUI_00001_.png [input]`

- Relative to the output directory:

  `ComfyUI_00001_-assets\ComfyUI_00001_.png [output]`

- Relative to the temp directory:

  `ComfyUI_00001_-assets\ComfyUI_00001_.png [temp]`