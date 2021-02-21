# MyraTexturePacker
MyraTexturePacker is console utility for making a texture atlas.

# Install

# Usage
`MyraTexturePacker.exe <input_folder> <output_file>`

I.e.
`MyraTexturePacker.exe "C:\Temp" "C:\Temp\my_atlas.png`

That command will make MyraTexturePacker go over all images in the folder "C:\Temp" and create the texture atlas from it.

The texture atlas will consist of two files: my_atlas.png(atlas image) and my_atlas.xmat(atlas definition in XML format).

MyraTexturePacker supports nine patch images. In order to use that feature, the input image name must have ".9" before the extension(i.e. `image.9.png`). Also such image must have 1px border with black lines marking strechable areas. See this link for thorough explanation of this feature: https://github.com/libgdx/libgdx/wiki/Ninepatches


