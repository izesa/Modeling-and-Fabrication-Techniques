# 7. Activity of Day 7: Digital Fabrication III: CNC Router Milling & Cutting.
##  PCB Milling Process using Carbide Nomad 3 CNC.

### 1. Introduction to PCB Milling.
PCB Milling is a substractive manufacturing process that uses CNC machines to physically remove copper from PCB blanks.

#### Advantages:
1. Ideal of Rapid prototyping and small-batch production
2. Eliminates the need for messy chemical etching processes.
3. Provides quick turnaround times for design Iterations.

### 2. Overview of the Carbide Nomad 3

![Image](../images/Nomad.jpeg){ width=400 Height=300 align=middle }
#### Observational View of this PCB Milling machine That is used to put to life the PCB Board designed in the Day 3 activity.

There are the main Parts or Key parts that makes the essentiality of this device.
#### Desktop CNC Milling Machine
Compact and powerful,designed for precisionin smaller footprint.
#### Enclosure for safety and Dust Control
Ensures a safer working environment and minimizes airbone particles.
#### High Precision for PCB Milling
Capable of intricate details required for complex Circuit Boards.
#### Compatible with Carbide Software.
seamless integration with carbide create for design and carbide Motion for machine control.
### 3. Essential Components for PCB Milling.
1. **PCB BLANKS** : FR-1 and FR-4 Copper-Clad Board, this is the base material for my circuit that i designed in **day 3** activity using **KiCad**. FR-1 IS Papper-based, easier to mill and for FR-4 is the fiberglass-based which is more durable.
2. **End Mills and Drill Bites** : According to the notes, 0.2-0.4 mm Flat End Mill which for precise trace isolation. Then for the drill bites is according to the various sizes for the component holes.
3. **Securing Materilas**: a double-sided tape which is for temporary, secure board mounting.
4. **Cleaning Tools** :Vacuum or Brush for removing milling dust nad debris, maintaining machine cleanliness.
### 4. PCB Design Preparation
Before Milling, i have used a dedicated PCB design software known as "**KiCad**"for creating the SChematic and board layout which is shown bellow in the pictures:

![Image](../images/Jabo_KiCad_schema.png){ width=400 Height=300 align=middle }
#### Schematic design done in Day 3 activity.

![Image](../images/kiCad_PCB_Design.png){ width=400 Height=300 align=middle }
#### PCB Layout Design done in Day 3 Activity.

### 5. Toolpath Generation for Milling.
Toolpath generation translates your PCB design into machine instructions. Software like Carbide ctreate is used for this step. those steps are:
#### Import Gerber files
Loa your exported Gerber and Drill files into my CAM software.
#### Generate Toolpaths
Create seperate toolpaths for **Trace isolation** and **Drilling**
#### Set Cutting Parameters.
Defining cutting depth, Tool diameter and Feed rate based on my materia and Tool specification.
#### Export G-code
Generate the Final G-CODE FILE that the Nomad 3 will execute.

### 6. Machine Setup and Calibration.
#### The PCB Milling Process
1. **Isolation Milling**: The machine begins by cutting the isolation traces, separating copper pads and times.
2. **Drilling Holes**: drill bits are used to create all necessary component holes
3. **Board Outline Cut**:Finally, the machine cuts out the overallshape of My PCB Milling Board.