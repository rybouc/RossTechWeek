# RossTechWeek
Repository in support of Ross Tech Week 2025. More details will be added prior to the workshop on 11/4. 

---

# 🧠 Pre-Workshop Setup Guide

### *Using VS Code + GitHub Copilot for Python Data Analysis*

This guide will help you get fully set up **before the workshop** so you can focus on learning, not installation!
Please complete all steps below **before the session**.

---

## 🧩 1. Install Visual Studio Code

1. Go to **[https://code.visualstudio.com/](https://code.visualstudio.com/)**
2. Download the installer for your operating system (Windows / macOS / Linux).
3. Run the installer and follow the setup prompts.

   * On Windows, check the box that says **“Add to PATH”** and **“Register Code as editor for supported file types.”**

👉 **Verify installation:**
Open a terminal (Command Prompt / Terminal / PowerShell) and run:

```bash
code --version
```

You should see a version number.

---

## 🧑‍💻 2. Create a GitHub Account

1. Go to **[https://github.com/join](https://github.com/join)**
2. Follow the prompts to create your free GitHub account.
3. Verify your email address.

---

## ⚙️ 3. Install Git (Version Control)

Git allows VS Code to interact with GitHub.

1. Download from **[https://git-scm.com/downloads](https://git-scm.com/downloads)**
2. Run the installer (use default options).
3. After installation, verify by running:

   ```bash
   git --version
   ```

---

## 🤖 4. Enable GitHub Copilot in VS Code

1. Go to **[https://github.com/features/copilot](https://github.com/features/copilot)**
2. Click **“Get Copilot”** and select either:

   * **Free Student Plan** (available via [GitHub Student Pack](https://education.github.com/pack))
   * or **Trial / Paid Plan**
3. Once activated, open VS Code and install the **GitHub Copilot** extension:

   * Open the Extensions tab (`Ctrl + Shift + X` or `Cmd + Shift + X` on Mac)
   * Search for **“GitHub Copilot”**
   * Click **Install**
4. Sign in to GitHub from VS Code when prompted.
5. Optional but recommended: also install **“GitHub Copilot Chat”** for inline explanations.

---

## 🐍 5. Install Python

1. Go to **[https://www.python.org/downloads/](https://www.python.org/downloads/)**
2. Download the latest **Python 3.x** release for your OS.
3. During installation on Windows:

   * ✅ Check **“Add Python to PATH”**
   * ✅ Select “Install for all users”
4. Verify installation:

   ```bash
   python --version
   ```

   or sometimes:

   ```bash
   python3 --version
   ```

---

## 📦 6. Install Required Python Libraries

Open a terminal or the VS Code integrated terminal and run:

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

If you get a “pip not found” error, try:

```bash
python -m pip install --upgrade pip
python -m pip install numpy pandas matplotlib seaborn jupyter
```

---

## 📔 7. Set Up Jupyter Notebooks in VS Code

1. In VS Code, open the **Extensions** tab (`Ctrl + Shift + X` / `Cmd + Shift + X`).
2. Search for **“Jupyter”** and **“Python”** extensions (by Microsoft).
3. Install both.
4. Create a new file with `.ipynb` extension or open an existing notebook.
5. Select your Python interpreter:

   * Click the **kernel selector** in the top right of the notebook and choose your Python environment.

---

## ✅ 8. Verify Everything Works

In VS Code, open a new Jupyter Notebook and run:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

print("Setup successful!")
sns.set_style("whitegrid")
plt.plot([1, 2, 3], [1, 4, 9])
plt.title("Test Chart")
plt.show()
```

If a simple line chart appears, you’re ready to go!

---

## 🧭 Optional: Helpful Extras

* **VS Code Python Tutorial:** [https://code.visualstudio.com/docs/python/python-tutorial](https://code.visualstudio.com/docs/python/python-tutorial)
* **GitHub Copilot Docs:** [https://docs.github.com/en/copilot](https://docs.github.com/en/copilot)
* **NumPy Docs:** [https://numpy.org/doc/stable/](https://numpy.org/doc/stable/)
* **Pandas Docs:** [https://pandas.pydata.org/docs/](https://pandas.pydata.org/docs/)
* **Matplotlib Docs:** [https://matplotlib.org/stable/](https://matplotlib.org/stable/)
* **Seaborn Docs:** [https://seaborn.pydata.org/](https://seaborn.pydata.org/)

---

