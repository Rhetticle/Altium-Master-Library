# Altium Designer Master Libraries
PCB and schematic libraries for Altium designer containing schematic symbols and PCB footprints for components used in my other projects. I created these libraries for components I repeatedly use or cannot be found in manufacturer part search. I also found most non-passive components from manufacturer part search have ugly 3D models and wanted to change that.

# Getting Started
Start by cd'ing into your local Altium directory (Or whichever directory you want the libraries to live) in my case this is `C:/Users/Public/Documents/Altium`. Create a new folder "Libraries"
```
cd C:/Users/Public/Documents/Altium

mkdir Libraries

cd Libraries
```
Now clone this repository.
```
git clone https://github.com/TheZ0/Altium-Master-Library.git
```
Next boot up Altium in the current project you're working on. Right click your .PrjPcb file add click "Add Existing to Project".

![image](https://github.com/TheZ0/Altium-Master-Library/assets/142558812/52a5d62b-869c-4537-83eb-e22c5c6e642c)

Navigate to wherever your libraries are saved and add both the Master.SchLib and Master.PcbLib files to your project. You will now have access to the components in the master libraries.

# Using the Library
To add a component from the master library navigate to the components panel on the right hand side and change from "Simulation Generic Components" to "Master".

![image](https://github.com/TheZ0/Altium-Master-Library/assets/142558812/ba237355-4db5-4cbf-be0a-21b6fc3a22da)

You can then use any of the components from the library which are all linked to their own footprint and 3D model in Master.PcbLib.
