# Attention Heatmap Explorer

![Python](https://img.shields.io/badge/Python-3.13-blue?style=flat&logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.10-orange?style=flat&logo=pytorch)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.10-green?style=flat&logo=plotly)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow?style=flat&logo=jupyter)

![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat)
![GitHub license](https://img.shields.io/github/license/rajghosh06-dev/attention-heatmap-explorer?color=purple&style=flat)
![GitHub repo size](https://img.shields.io/github/repo-size/rajghosh06-dev/attention-heatmap-explorer?color=blue&style=flat)
![GitHub language count](https://img.shields.io/github/languages/count/rajghosh06-dev/attention-heatmap-explorer?color=yellow&style=flat)
![GitHub top language](https://img.shields.io/github/languages/top/rajghosh06-dev/attention-heatmap-explorer?color=orange&style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/rajghosh06-dev/attention-heatmap-explorer?color=red&style=flat)

![GitHub forks](https://img.shields.io/github/forks/rajghosh06-dev/attention-heatmap-explorer?style=social)
![GitHub stars](https://img.shields.io/github/stars/rajghosh06-dev/attention-heatmap-explorer?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/rajghosh06-dev/attention-heatmap-explorer?style=social)


# Attention Heatmap Explorer

## Overview
This project demonstrates the **Self-Attention Mechanism** from Transformers.
It visualizes how words in a sentence attend to each other using PyTorch.


## Folder Structure
```
attention-heatmap-explorer/
│
├── Attention_Heatmap_Explorer.ipynb   # Main notebook with code + explanations
├── README.md                          # Project overview + instructions + screenshot
├── requirements.txt                   # Dependencies (torch, matplotlib, notebook)
├── images/
│   └── attention_heatmap.png          # Exported heatmap visualization
└── .gitignore                         # Ignore cache files (e.g., __pycache__, .ipynb_checkpoints)
```


## Features
- Implements Query, Key, Value (QKV)
- Scaled Dot-Product Attention
- Softmax normalization
- Generates a heatmap showing attention weights
- Exports visualization to `/images`

## Example
>Sentence: *"The animal didn’t cross the street because it was tired."*

The heatmap shows that the word **"it"** attends strongly to **"animal"**.

## How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook Attention_Heatmap_Explorer.ipynb
   ```
3. Run all cells to generate the attention heatmap.


## Output
The notebook will generate and save the visualization as:  
![Attention Heatmap](images/attention_heatmap.png)


> Directories for reference:
>>Click [`here`](/Attention-Heatmap-Explorer.ipynb) to check out the Notebook's directory!  
>>Click [`here`](/images/attention_heatmap.png) to check out the image's directory!

---

## Deliverables
- A **working notebook** with explanations + code.  
- A **saved heatmap image** in `/images`.  
- A **README** that looks professional on GitHub.  

## Author
**Rishit Ghosh**  
B.Tech CSE (AI & ML),  
Geethanjali College of Engineering and Technology  
GitHub Profile: [(rajghosh06-dev)](https://github.com/rajghosh06-dev/)

---