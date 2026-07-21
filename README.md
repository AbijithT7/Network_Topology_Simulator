# 🖥️ Network Topology Simulator & Cost Estimator

### 📚 Project Overview

This Python-based **Network Topology Simulator** allows users to design and analyze various **network topologies** such as Bus, Star, Ring, Mesh, and Tree.  
It provides an **interactive Tkinter GUI** to visualize each topology, calculate the **total network cost**, switch seamlessly between **Light and Dark themes**, and generate a **detailed report (Word DOCX)** including all parameters and diagram results.

---

### ⚙️ Features

✅ Generate and visualize topologies: **Bus, Star, Ring (3 variants), Mesh, Tree**  
✅ Automatic cost calculation (port cost + cable cost)  
✅ Step-by-step breakdown of total cost  
✅ **Dynamic Light / Dark Mode Theme Toggle** 🌙☀️  
✅ Interactive graph view (zoom, pan, save diagram)  
✅ Built-in **Learning Mode** – theory + video references  
✅ **Full-size Credits & Contributors Window** with profile cards  
✅ Export detailed **Word report (DOCX)** with graph images embedded  
✅ Smooth and responsive **Tkinter GUI**

---

### 🧩 Tech Stack

- **Python 3.11+**
- **Tkinter** – GUI Framework
- **NetworkX** – Network graph creation
- **Matplotlib** – Graph Visualization
- **Pillow (PIL)** – Image & avatar handling
- **python-docx** – Detailed report generation

---

### 🖼️ Application Preview

![Application Screenshot](./screenshot.png)

---

### 🧮 How It Works

1. **Enter Inputs:**
   - Number of nodes
   - Select topology type
   - (For Ring) choose variant
   - Enter port cost, cable length, and cost per meter

2. **Click “Generate Topology”**
   - Visualizes your chosen topology
   - Calculates total cost
   - Displays step-by-step cost breakdown

3. **Toggle Themes (Optional)**
   - Click **🌙 Dark Mode** / **☀️ Light Mode** in the header bar to switch themes at any time

4. **Click “Download Report”**
   - Exports results and topology diagram to a formatted **Word document (.docx)**

---

### 📄 Report Generation

Each report includes:

- Input parameters
- Step-by-step cost calculations
- High-resolution topology diagram
- List of all node connections
- Footer with project details

---

### 🧑‍💻 Developed By

- **Abijith Thennarasu (24BCE1626)** – Lead Developer
- **Dharmayu Jadwani** – Project Contributor
- Guided by **Dr. Swaminathan Annadurai** – Faculty Advisor

---

### 🧠 Learning Mode

Learn the concepts of each topology right inside the app with a detailed theoretical explanation and direct access to an animated YouTube tutorial:  
🎥 [Network Topology Explanation](https://www.youtube.com/watch?v=zbqrNg4C98U)

---

### 🚀 How to Run

1. **Navigate to the repository**

   ```bash
   cd Network-Topology-Simulator
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application**
   ```bash
   python network_topology_gui.py
   ```

---

### 📦 Requirements

If installing manually without `requirements.txt`:

```bash
pip install networkx matplotlib pillow python-docx numpy
```

---

### 🧰 Folder Structure

```
Network-Topology-Simulator/
│
├── network_topology_gui.py        # Main application code
├── computer.png                   # Node icons
├── requirements.txt               # Dependencies
├── screenshot.png                 # Application GUI preview image
└── README.md                      # Project documentation
```

---

### 🏆 Credits

> Developed as part of **Computer Networks (DA Project)**  
> **VIT Chennai**  
> Faculty Guide: _Dr. Swaminathan Annadurai_

---

### 📬 Contact

**Abijith Thennarasu**  
📧 abijith.thennarasu2024@vitstudent.ac.in  
📍 VIT Chennai
