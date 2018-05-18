# Daz Iray Shaders and lights
Welcome home Daz users.
Here you can download, use, create or contribute.

# How that work ?
Every shaders and lights are stored in the dedicated folders.

- `Shaders Presets/DISL`               Shaders .DUF (uncompressed) files + Render of ball scene to see how the shader look.
- `Light Presets/DISL`                Lights .DUF (uncompressed) files + Render of ball scene to see how the light look.
- `Scenes/Stress-test`           Test scene to figure out if your shader or light work in every situations.
- `Runtime/Textures/DISL`              Texture who are mostly used by shaders.

# How to download and apply shaders or lights ?

Downloading is quite simple :
- You can clone the repo entirely on your computer with the <a href="https://desktop.github.com/" target="_blank">software</a> and maintain it up to date.
- You can download entire repo (zip) by clicking on the green button up there.

Apply a shader is simple too :
- Simply drag and drop inside daz (If you don't know <a href="https://youtu.be/68EhOnllGD8" target="_blank">clic here</a>).
- If you made a fork, link into your daz database; you will get this result <a href="https://giphy.com/gifs/XUR6n6TFIyu52" target="_blank">like this</a>.

# I have a problem ... what can I do ?

Open an <a href="https://github.com/Astuceman/Daz-Iray-Shaders-and-Lights/issues">issue</a> and explain your problem in detail.

# I want to contribute

1. Be sure to read the `README.md`

2. Make a fork using <a href="https://desktop.github.com/">Github Desktop</a>

3. Make a <a href="https://help.github.com/articles/about-pull-requests/">pull request</a> (if you have a question or a problem create an <a href="https://github.com/Astuceman/Daz-Iray-Shaders-and-Lights/issues">issue</a>)

# How branches works

1. **Master** : every one will see it at first and it need to be tested and bug free. This is the stable branch.

If you don't know how github work look at this <a href="https://guides.github.com/activities/hello-world/">beginning article</a> or `ask me` for help.

**Have fun** :smiley:

# Rules

- Don't post what's not yours (duh) but you can post shaders, lights or renders if you have the direct autorisation of the creator and explain what we do here with the direct link to the project (https://github.com/Astuceman/Daz-Iray-Shaders).
- English is the default language (duh).

# Folders Rules

`Shaders Presets/DISL`               Shaders .DUF files + icon.

  - We only accept .DUF (uncompressed) files.
  - Render of ball scene to see how the shader look.
  - You need to render every shader you put in the `Shaders` folder and put it in the same folder.
  - Load `material ball scene` select (everything are allready selected by default) `DAZ Material Ball` and create or apply the shader on `OuterSphere` and `Stand` and render the scene by default.
  - The name of the render need to have the same name of the shader.
  - When you post a shader with "Emission color" (light) you need to render it without light from camera (Choose "Explore camera" then clic on "Headlamp" then "Headlamp Mode" choose "Off") and light from scene (Open "Render settings" then clic on "Environment" and choose "Scene Only" in "Environment Mode").

`Light Presets/DISL`                Lights .DUF (uncompressed) files + icon.

  - Render of ball scene to see how the shader look.
  - The same rules apply as before.

`Scenes/Stress-test`           Test scene to figure out if your shader work in every situations.

  - The scene inside the folder are for test purpose ,use this to try your shader in different lighthning and situations.

`Runtime/Textures/DISL`              Use this textures with shaders or as a standalone.

  - You need to create this textures by yourself or have the permission of the author.
  - The best value is a picture with 5000x5000 px and in PNG format.
  - With the original texture add if you can, BUMP version (black and white) and NORMAL (blue and purple).
  - For naming convention, see the files inside `Textures` folder, and how they are named.
  - Add the source file (PSD for photoshop for example) if the file is less than 100 mega. DON'T FORGET there is a file size limit : no more than 100 mega.


# Planed in the future

- material preset.
