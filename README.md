📌 PyPhysics

“This project was developed with the assistance of Artificial Intelligence (AI) to support the design and implementation of interactive physics simulations.”

The main goal of PyPhysics is to support educators in making physics more engaging and visually accessible through interactive simulations. It is designed for both students and teachers in Brazil and worldwide, helping to make physics concepts easier to understand through visualization and interaction.
🚀 Run on Google Colab

This project was developed and tested using Google Colab, so no installation is required.

Simply open the notebook and run the cells.

⚙️ How to Run the Code

The notebook is organized into independent sections (experiments).
To ensure good performance, it is recommended to run only the cells related to the experiment you want to explore.

▶️ Step 1 — Run the import cell

Before running any simulation, execute the first cell:

import numpy as np
import matplotlib.pyplot as plt
import ipywidgets as widgets

plt.style.use('seaborn-v0_8-darkgrid')
▶️ Step 2 — Run one experiment at a time

Each experiment is designed to work independently.

👉 Recommended workflow:

Run the import cell
Choose one experiment
Run only the cells for that experiment
⚠️ Important
Avoid using “Run all” if the notebook contains multiple simulations
Running everything at once may:
slow down execution
overload the environment
affect interactivity
🔄 If something doesn’t work
Restart the environment:
Runtime → Restart runtime
Then run only what you need
🎯 Notes
This notebook is optimized for Google Colab
Designed for interactive use, not batch execution
