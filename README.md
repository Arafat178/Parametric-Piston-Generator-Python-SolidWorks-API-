#  Parametric Piston Generator (Python + SolidWorks API)

A Python-powered automation script to generate **3D piston models** in SolidWorks based on user-defined dimensions.  
*(Note: The main automation code is private; this repository showcases the project workflow, demo, and results.)*

---

##  Features
- Fully automated piston creation in SolidWorks  
- Parametric design: input bore, height, pin hole, ring grooves, dome height, etc.  
- Educational and portfolio showcase  
- Demonstrates SolidWorks API automation workflow  
- Repeatable and consistent piston models  

---

##  Requirements
- Windows OS  
- SolidWorks 2020 or later  
- Python 3.8+  
- `pywin32` package (only if running the automation code privately)  

---
## 📸 Demo
![Piston Demo](media/Demo_piston_3D.gif)

## 📝 How it Works 
1. User manually inputs piston parameters (all in mm): bore, height, pin hole diameter, crown thickness, dome height, ring groove specs.
2. Python script (private) communicates with SolidWorks via COM API.
3. The script automatically:
     - Sketches the piston outline
     - Extrudes the body
     - Cuts pin holes and ring grooves
     - Inserts dome crown
5. SolidWorks displays the finished 3D piston.
## Example Input Table
| Parameter              | Value (mm) |
| ---------------------- | ---------- |
| Piston Bore            | 120        |
| Piston Height          | 120        |
| Pin Hole Diameter      | 25         |
| Pin Hole Center        | 35         |
| Crown Thickness        | 8          |
| Dome Height            | 5          |
| Ring Thickness         | 3          |
| Ring Distance from Top | 10         |
| Ring Land Depth        | 3          |
| Ring Spacing           | 3          |

## Result: 
Fully modeled piston, ready for analysis or manufacturing prep.

