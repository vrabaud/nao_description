nao_description
===============

URDF Model description of Aldebaran NAO

Instructions - Automatic solution - (tested with Blender v2.66 - v2.69):
- Download this package
- Source the setup.sh of the workspace with this package
- if you are on Ubuntu, you need a Blender with collada support which you can get doing:
   sudo add-apt-repository ppa:irie/blender && sudo apt-get update && sudo apt-get install blender
- Download nao-v4.blend into the ./scripts/ directory
- From the ./scripts/ directory, run blender nao-v4.blend -P io_export_separate.py 
- Try the result using roslaunch nao_description rviz.launch

Instructions - Manual solution - (tested with Blender v2.66 - v2.69):
- Download this package
- Download nao-v4.blend
- Open the downloaded file with Blender after sourcing the setup.sh of the workspace with that package
- Open a Text Editor window inside Blender (shit + F11)
- Open the ./scripts/io_export_separate.py script in that editor
- Run the script in Blender
- Try the result using roslaunch nao_description rviz.launch
