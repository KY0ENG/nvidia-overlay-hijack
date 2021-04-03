# nvidia-overlay-hijack

This lets you draw on top of the nvidia overlay shown in `main.cpp`.  

Pseudo functions like:  
draw_text_red  
draw_text_green  

exist to help you write your own functions, those are badly written and should just take an color as arg but i could not be bothered writing a structure for it.

## How to get visual studio project
- Type in `cmake -G` to see all your generators.
- Find the visual studio generator you want to use
- Type in `cmake -G "insert_visual_studio_generator"`
- ???
- Profit