
# Anchor
*ANCHOR detects fatigue-driven gait changes in maritime workers in real-time, alerting them via wearable IoT to prevent slips and falls while mapping high-risk zones across the vessel.*

## Project Components

### CAD Files (STL)
Two STL files for CAD (Computer-Aided Design) of the shoe: internal and external components.  
> **Tip:** Click the **“View in 3D”** button in the top right corner to explore the design.

- **Internal CAD:** [View on Tinkercad](https://www.tinkercad.com/things/46U1N8oUxad-stable-redesign-1?sharecode=OG6LbkThn3Wb57vXWL62F9TYeadp3q-ar7RBWBMiuVo)  
- **Exterior CAD:** [View on Tinkercad](https://www.tinkercad.com/things/lvyw53suT2L-stable-redesign-2?sharecode=BXeA5KTb9yUF4DtWIMENSM9CNgfN1p1fH3T_BuieiSo)

### Arduino Code
Code written for the Arduino Uno R3. Handles component connections and data collection.

### Data Files
Four CSV files representing walking patterns 1–4. Each file captures a different gait pattern for classification purposes.

### Detection Algorithm
Implemented in Python & PyTorch. Classifies gait patterns with **> 90% accuracy** using a 1D CNN.

### Web App
`index.html` – App for maritime workers that processes the data, provides actionable feedback, and displays key metrics.
**Direct link to use the app:** [https://arshj599.github.io/Anchor/](https://arshj599.github.io/Anchor/)

## Additional Resources
- **Blueprint:** [Google Drive](https://drive.google.com/file/d/1Vz2iM6o0mhUT4oa-eQICUak0AmUm4gR_/view?usp=sharing)  
- **Circuit Diagram:** [Google Drive](https://drive.google.com/file/d/12ykVddvXq81e2DQqB_T4c1SWnft1MVsT/view?usp=sharing)  
- **Flowchart (Ideaization):** [Google Drive](https://drive.google.com/file/d/11RSiCuDzKjLSgIs1NFllLkbtEmJ4IzDZ/view?usp=sharing)
