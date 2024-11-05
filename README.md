__Let's make it better:__ [<img src="https://img.shields.io/github/issues/tabmk/godot-2d-shadow-shader">](https://github.com/TABmk/godot-2d-shadow-shader/issues?q=is%3Aopen+is%3Aissue) [<img src="https://img.shields.io/github/issues-pr/tabmk/godot-2d-shadow-shader">](https://github.com/TABmk/godot-2d-shadow-shader/pulls?q=is%3Aopen+is%3Apr)

#### __Rate__ [<img src="https://img.shields.io/github/stars/tabmk/godot-2d-shadow-shader?style=social">](https://github.com/TABmk/godot-2d-shadow-shader)

# 2D shadows shader for Godot 4+

<p align="center">
<img width="80%" src="./preview/1.png">
</p>

### Features:
- Any X/Y offset
- Any color
- debug helper
- no need to prepare an image
- 🆕 uses `modulate` from parent, including alpha for shadow
- 🆕 shadow blur. Blur goes out of shadow bounds
- 🆕 new option for handling parents' rotation

## Video (clickable)

[![Click](https://img.youtube.com/vi/9rneonV7nQ0/0.jpg)](https://youtu.be/9rneonV7nQ0)

## How to use
1) Add [shadow.gdshader](https://github.com/TABmk/godot-2d-shadow-shader/blob/master/shadow.gdshader) to your project
2) Under "Material" tab in your element, add a shader as a prepared material or create a new ShaderMaterial
3) Use "Shader Parameters" to configure your shadow

⚠️ For text nodes use built-in shadows at `theme_override_constants/shadow_outline_size`
