# Daz Iray Shaders and lights
Welcome home Daz users

Here you can download, use, create or contribute

# How that work ?
Every shaders and lights are stored in the dedicated folders

- `Shaders`               Shaders <a href="https://youtu.be/wvOotDR_cuI" target="_blank">.DSA</a> files + Render of ball scene to see how the shader look
- `Lights`                Lights .DSA files + Render of ball scene to see how the light look
- `Example-renders`       Example render of one shader or light in many situation (no rules)
- `Stress-test`           Test scene to figure out if your shader or light work in every situations
- `Textures`              Texture who are mostly used by shaders

# How to download and apply shaders or lights ?

Downloading is quite simple :
- You can clone the repo entirely on your computer with the <a href="https://desktop.github.com/" target="_blank">software</a> and maintain it up to date
- You can download entire repo (zip) by clicking on the green button up there
- You can download manually by right clicking on a shader or light (XXX<a href="https://youtu.be/wvOotDR_cuI" target="_blank">.DSA</a>) (find "Raw") and "clic save as"

Apply a shader is simple too :
- Simply drag and drop inside daz (If you don't know <a href="https://youtu.be/68EhOnllGD8" target="_blank">clic here</a>)
- If you made a fork, link into your daz database; you will get this result <a href="https://giphy.com/gifs/XUR6n6TFIyu52" target="_blank">like this</a>

# How branches works for now

1. **Master** : every one will see it at first and it need to be tested and bug free. This is the stable branch
2. **New_Yourname** : When you want to upload a new shader or light create a new branch named `New_Yourname` from `Master` and don't forget to ask some feedbacks if you need it. Your branch will be merged with the `Master` branch at the end
3. **Update_Yourname** : Basicaly when you want to polish or update any file. Create a new branch from `Master` branch, name it `Update_Yourname` and add modification to something that exist allready. Don't forget to ask some feedbacks if you need it. Your branch will be merged with the `Master` branch at the end

If you don't know how github work look at this beginning article https://guides.github.com/activities/hello-world/ or `ask me` for help

**Have fun**  :smiley:

# Rules

- Don't post what's not yours (duh) but you can post shaders, lights or renders if you have the direct autorisation of the creator and explain what we do here with the direct link to the project (https://github.com/Astuceman/Daz-Iray-Shaders)
- English is the default language (duh)

# Folders Rules

`Shaders`               Shaders <a href="https://youtu.be/wvOotDR_cuI" target="_blank">.DSA</a> files + icon

  - We don't accept .DUF files (default format) because it's unreadeable by an text editor.
  - You need to export shaders in <a href="https://youtu.be/wvOotDR_cuI" target="_blank">.DSA</a> format
  - Render of ball scene to see how the shader look
  - You need to render every shader you put in the `Shaders` folder and put it in the same folder
  - Load `material ball scene` select (everything are allready selected by default) `DAZ Material Ball` and create or apply the shader on `OuterSphere` and `Stand` and render the scene by default
  - The name of the render need to have the same name of the shader
  - When you post a shader with "Emission color" (light) you need to render it twice. One time like everyone. Second without light from camera (Choose "Explore camera" then clic on "Headlamp" then "Headlamp Mode" choose "Off") and light from scene (Open "Render settings" then clic on "Environment" and choose "Scene Only" in "Environment Mode"). The second render will have the same name like the first with one difference : Need to place (DARK) after the name like this : XXX (DARK).png

`Lights`                Lights .DSA files + icon

  - Render of ball scene to see how the shader look
  - The same rules apply as before

`Example-renders`       Example render of one shader in many situation (no rules)

  - The name of the render need to have the same name of the shader
  - The dimension of the render need to be 1280 x 720 (16:9) or 720 x 1280 (9:16)

`Stress-test`           Test scene to figure out if your shader work in every situations

  - The scene inside the folder are for test purpose ,use this to try your shader in different lighthning and situations

`Textures`              Use this textures with shaders or as a standalone

  - You need to create this textures by yourself or have the permission of the author
  - The best value is a picture with 5000x5000 pix and in PNG format
  - DON'T FORGET there is a file size limit : no more than 100 mega
  - With the original texture add if you can, BUMP version (black and white) and NORMAL (blue and purple)
  - For naming convention, see the files and how they are named
  - Add the source file (PSD for photoshop for example) if the file is less than 100 mega

# Planed in the future

- shaders with texture
- material preset
