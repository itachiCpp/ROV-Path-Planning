# ROV-Path-Planning
An interactive simulator that teaches a Remotely Operated Vehicle (ROV) to navigate a 2D subsea map using Q-learning. Tune hyperparameters from the UI, generate new environments, visualize the optimal path, and download the learned Q-table.
<img width="1140" height="760" alt="image" src="https://github.com/user-attachments/assets/02e0f22f-32cd-4f5a-a842-37530f932af8" />



**Features**
- ** Q-Learning on a 10×10 grid (Up/Down/Left/Right actions)

- ** Fixed grid + “Generate New Grid” → makes parameter comparisons meaningful

- ** Obstacle types (configurable):

  0: Free (−1 reward)
  
  1: Wall/Rock (−10 or blocking)
  
  2: Rock (−5 to −20 — tunable)
  
  3: Strong current (−3 — tunable)

- ** Frontend sliders: epsilon, gamma, alpha, episodes

- ** PNG render of optimal path

- ** CSV export of the learned Q-table

- ** Simple, clean React UI; FastAPI backend




**What this project demonstrates**
- ** How reinforcement learning can be used for path planning in a hazardous environment (ocean in this case)

- ** The effect of hyperparameters on learning and convergence

- ** A full-stack AI app (Python backend + React frontend)

- ** Real ROVs use more complex models/sensors; this is an educational, scalable abstraction.




**Tech Stack**
- ** Backend: Python, FastAPI, Uvicorn, NumPy, Matplotlib, Pandas

- ** Frontend: React (CRA), fetch/axios

Runtime: Windows-friendly (works cross-platform)
