# adaptive-reliability
 
Raw JSON data generated from the first layer of the simulator are stored in different folders named by the UE positions in their paths.
---
Each folder contains the output of the first layer of our simulator, which produces a JSON file for each gNodeB.
Each file contains various information such as the positions (e.g., the coordinates and tile numbers) and sizes of the machines, the position of the UE, the BLER values for a given position of one UE and one gNodeB according to the different positions of the machines in their paths, the Line of Sight (LOS) condition (whether there is a LOS path between the UE and the selected gNodeB for a machine location in its path or not), the T-R distance, and the size of the factory area.
