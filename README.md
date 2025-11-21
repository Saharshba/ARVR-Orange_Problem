# AR/VR Gym Navigation

This project contains a 3D gym environment(simulated similar to Namma Gym in PES) created in Blender, exported as a GLB file, and rendered in the browser with first-person navigation.

## Contents

- `gym_modeling.blend` – Original Blender scene for the gym.
- `gym_model.glb` – Exported GLB model of the gym.
- `gym_model_navigation.html` – HTML file that loads the GLB model and enables first-person navigation in the browser.

## Requirements

- A modern web browser (Chrome, Firefox, Edge, Brave, etc.)
- (Optional) A local HTTP server if the browser blocks local file access to `gym_model.glb`.

## How to Run the Navigation Demo

### Option 1 – Open directly (if your browser allows it)

1. Download or clone this repository.
2. Make sure `gym_model_navigation.html` and `gym_model.glb` are in the same folder.
3. Double-click `gym_model_navigation.html` to open it in your browser.
4. Use the on-screen or keyboard controls (documented below) to move around the gym.

If the GLB model **does not load** due to browser security restrictions, use Option 2.

### Option 2 – Run via a simple local server (recommended)

#### Using Python

From the project folder:

```bash  
# For Python 3  
python -m http.server 8000  
```

# Controls


Typical first‑person controls (example):

W / A / S / D – Move forward / left / backward / right
Q - to unlock sliding door at entrance 
Mouse move – Look around
Space – Jump 
Esc – Release mouse lock / cursor


## High-Resolution Assets

The full-resolution 3D assets are stored in Google Drive because they are larger than GitHub’s file size limit.

- Blender source file (`gym_modeling.blend`):  
  [Download from GoogleDrive](https://drive.google.com/file/d/1G9BNgqXFgbqC38rtw_PMjJknlJVdQFlj/view?usp=sharing)

- High-resolution GLB model (`gym_model.glb`):  
  [Download from GoogleDrive](https://drive.google.com/file/d/12lPFk8HZfvIb_6R-lw7SMm0vdAIqAVH4/view?usp=sharing)

After downloading, place these files in the same folder as `gym_model_navigation.html` on your local machine to use them with the Namma gym demo.
