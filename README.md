## 👕 3D Virtual Try-On System
This project demonstrates a basic 3D virtual try-on system that fits a t-shirt mesh onto a 3D human body mesh using Python libraries like Open3D and Trimesh. The system loads 3D assets, performs alignment and scaling, and visualizes the results.

## 📁 Project Structure
python
Copy
Edit
Try 3D Mesh/
├── tryon.ipynb             # Jupyter Notebook with full implementation
├── results.pdf             # Report file
├── results/
│   └── virtual_tryon_result.html  # Optional: HTML preview of results

## 🛠️ How It Works
Mesh Extraction

Extracts body and t-shirt meshes from the zip files provided.

Mesh Loading

Loads 3D body mesh (.obj) and t-shirt mesh (.glb) using Trimesh and Open3D.

Alignment & Scaling

Scales and aligns the t-shirt to fit the body mesh using bounding box normalization.

Visualization

Displays the body and t-shirt together in a 3D scene using Plotly or Open3D.

## 📦 Dependencies
Install requirements using pip:

bash
Copy
Edit
pip install open3d trimesh plotly numpy
You may also need:

bash
Copy
Edit
pip install pygltflib
## 🚀 Run the Project
Extract the zip files:

body_samples.zip → body_samples/

tshirt_samples.zip → tshirt_sample/

Open the tryon.ipynb notebook and run all cells.

## 🧠 Bonus Areas (Mentioned in Report)
This project can be extended with:

Cloth Simulation using Blender or NVIDIA Flex

UV Mapping for applying textures to the shirt

SMPL-X Support for morphable body shapes and poses

Collision Detection to handle mesh intersections

## 👤 Author
Salah Hossam
Machine Learning & Embedded Systems Engineer
🔗 LinkedIn
📊 Kaggle
