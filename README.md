# 🚀 LangGraph Practice Project

A collection of Jupyter notebooks designed to help you learn and practice LangGraph fundamentals through hands-on examples.

## 📚 Notebooks Overview

| Notebook | Description | Difficulty |
|----------|-------------|------------|
| **Hello_World.ipynb** | Basic single-node graph with greeting functionality | 🟢 Beginner |
| **Multi_Input_Graph.ipynb** | Single-node graph handling multiple inputs (name and age) | 🟡 Intermediate |
| **Sequential_Graph.ipynb** | Multi-node sequential workflow with state passing | 🟠 Advanced |

## 🛠️ Setup Instructions

### Prerequisites
- Python 3.7 or higher
- Git (optional, for cloning)

### Step-by-Step Installation

1. **Install Python**
   ```bash
   # Download the latest Python from the official website
   # https://www.python.org/downloads/
   ```

2. **Create Virtual Environment**
   ```bash
   python -m venv .venv
   ```

3. **Activate Virtual Environment**
   
   **Windows (PowerShell):**
   ```powershell
   .venv\Scripts\Activate.ps1
   ```
   
   **Linux/macOS:**
   ```bash
   source .venv/bin/activate
   ```

4. **Install Dependencies**
   ```bash
   pip install 
   ```

### 🔧 Troubleshooting

**TypedDict Import Error:**
If you encounter import errors, add this to the top of your notebook:
```python
from typing import TypedDict
```

## 🏃‍♂️ How to Run

1. **Open VS Code**
   - Launch Visual Studio Code
   - Open the project folder containing the notebooks

2. **Open Your Desired Notebook**
   - Navigate to the notebook file you want to run (`.ipynb` file)
   - Click on the file to open it in VS Code

3. **Configure Kernel**
   - When prompted to select a kernel, choose the `.venv` virtual environment
   - If not prompted, click on the kernel selector in the top-right corner and select `.venv`

4. **Execute Code Blocks**
   - Click the ▶️ play button on each code cell
   - Or use `Shift + Enter` to run cells sequentially

## 📖 Learning Path

```mermaid
graph LR
    A[Hello_World.ipynb] --> B[Multi_Input_Graph.ipynb]
    B --> C[Sequential_Graph.ipynb]
    
    style A fill:#e1f5fe
    style B fill:#fff3e0
    style C fill:#fce4ec
```

**Recommended Order:**
1. Start with `Hello_World.ipynb` to understand basic graph concepts
2. Progress to `Multi_Input_Graph.ipynb` for input handling
3. Complete `Sequential_Graph.ipynb` for advanced workflows

## 💡 Tips for Success

- 📝 **Take Notes**: Document your learnings as you progress
- 🧪 **Experiment**: Modify the code to see how changes affect output
- 🔄 **Practice**: Run each notebook multiple times with different inputs
- 💬 **Ask Questions**: Don't hesitate to seek help when stuck

## 🤝 Contributing

Found an issue or have suggestions for improvement? Feel free to:
- Open an issue
- Submit a pull request
- Share your feedback

---

**Happy Learning! 🎉**

*Building graphs has never been easier with LangGraph!*
