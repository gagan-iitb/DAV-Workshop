# 🛠️ Installation Guide

This guide will help you set up your development environment for hands-on training in:

- 📊 Plotly, Matplotlib & Seaborn for Visualization
- ⏱️ Time Series Analysis using Pandas and Statsmodels
- 📈 Power BI for dashboarding


## 📌 Step 1: Install Python (Windows / macOS / Linux)

### ➤ Recommended Version: **Python 3.8 or later**

- 🔗 [Download Python from official website](https://www.python.org/downloads/)
- During installation:
  - ✅ Check the box that says **"Add Python to PATH"**
  - Click **Install Now**

To confirm installation:
```bash
python --version
````

## 📌 Step 2: Install Anaconda (Recommended)

Anaconda provides an all-in-one package with Python, Jupyter, and common data science libraries.

* 🔗 [Download Anaconda](https://www.anaconda.com/products/distribution)
* Choose Python 3.x version for your OS.
* Install and open **Anaconda Navigator** or use the terminal/command prompt.

To verify:

```bash
conda --version
```

## 📌 Step 3: Set Up Virtual Environment (Optional but Recommended)

```bash
# Create a new environment named 'dav'
conda create -n dav python=3.9

# Activate the environment
conda activate dav
```

## 📌 Step 4: Install Required Python Libraries

Run the following command inside your environment:

```bash
pip install pandas matplotlib seaborn plotly statsmodels jupyter
```

To check installation:

```bash
python -c "import pandas, matplotlib, seaborn, plotly, statsmodels; print('All packages installed successfully!')"
```

## 📌 Step 5: Launch Jupyter Notebook

To start working on notebooks:

```bash
jupyter notebook
```

This will open Jupyter in your browser at:
`http://localhost:8888`


## 📌 Step 6: Install Power BI (Windows Only)

Power BI Desktop is available for free for Windows users.

### 🔗 [Download Power BI](https://powerbi.microsoft.com/en-us/downloads/)

* Choose **Power BI Desktop**.
* Once installed, launch it from the Start menu.
* Sign in with your **Microsoft account** (free signup available).
* You’re now ready to import data (CSV, Excel, or JSON) and build dashboards.


## 💡 Troubleshooting Tips

* Use `pip install --upgrade` if a package is outdated.
* Use `jupyter notebook --no-browser` if working on remote servers.
* Use Anaconda Navigator GUI for non-terminal-based installations.
* Restart the kernel in Jupyter if new libraries are installed during runtime.


## 📦 Optional (For Advanced Users)

To install with `requirements.txt`, use:

```bash
pip install -r requirements.txt
```

Example contents of `requirements.txt`:

```
pandas
matplotlib
seaborn
plotly
statsmodels
```

## ✅ You're All Set!

Once the tools are installed:

* Try importing your dataset using `pandas.read_csv()`
* Generate a simple line plot using `matplotlib.pyplot.plot()`
* Launch Power BI and try loading the same dataset

You’re now ready for the **Day 3 workshop** and beyond! 🚀

```
Feel free to reach out if you encounter any issues during installation or need further assistance.

```
