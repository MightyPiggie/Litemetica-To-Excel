# About this project
This is a python script to generate an excel sheets from a litemetica material list. [Litemetica](https://modrinth.com/mod/litematica) is a mod that can be used within Minecraft to overlay a blueprint that shows you were to build.
The generated excel sheets contains the amount of blocks remaining to be gathered and also converted into shulkers, stacks and items remaining.
This project was made for the purpose to be used by [Canopy](https://www.canopymc.net/), a vanilla Minecraft server focused around the comunity, and this project should help with gathering the materials for the community projects build on the server.

## How to use
To currently use it you need [Python](https://www.python.org/) installed. You also will need to install [openpyxl](https://openpyxl.readthedocs.io/en/stable/).
Then open the `main.py` and change the `filename` variable to be the name of your material list without the file extension. The material list should be located within the same folder of the main.py. Then just run `python main.py`. Now there should be an excel file with the same name inside the same folder.

## Future
Eventualy the project will be more user friendly. How this will be achieved is currently unclear.
Another thing worth looking into is automatic uploads to google drive so the excel sheets can be automaticly uploaded as well.