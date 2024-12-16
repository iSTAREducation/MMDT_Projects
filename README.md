# Project Submission Template

This template repository is designed for students to use as a base for organizing and submitting their project work. The goal is to ensure a consistent structure that makes it easy to review code, datasets, and results. Students will be required to follow the repository structure and include their code, data, and any other relevant materials in the appropriate directories. The template encourages good organization practices and clear documentation.
```
Project-Template/
├── code/                    # All source code for the project
│   ├── data_processing.py    # Scripts for data preprocessing and transformations
│   ├── model.py             # Model definition, training, and evaluation scripts
│   ├── utils.py             # Utility functions used across the project
│   └── main.py              # Main script to run the project (if applicable)
│
├── data/                    # Data used in the project
│   ├── raw/                 # Original, unprocessed data
│   ├── processed/           # Cleaned and preprocessed data
│   └── README.md            # A description of the dataset(s) and how to use them
│
├── results/                 # Results of the project (e.g., output, figures, logs)
│   ├── figures/             # Plots and visualizations
│   ├── logs/                # Logs for training or evaluation (e.g., model outputs)
│   └── final_model/         # Final trained model (e.g., .pth, .h5, or other formats)
│
├── notebooks/                # Jupyter notebooks (if used for exploratory analysis or experiments)
│   └── analysis.ipynb       # A sample Jupyter notebook for analysis and experimentation
│
├── README.md                # Project overview, setup instructions, and guidelines
├── requirements.txt         # Python dependencies and environment setup
└── LICENSE                  # Project license (if applicable)
```

## Guidelines for Students

- **Code Organization**: 
  - All project code must be placed inside the `code/` directory. Follow a logical structure and keep related scripts together.

- **Data Handling**:
  - Submit raw data in the `raw/` repository unless it is publicly available or it is small enough to include.
  - Always store processed data in the `processed/` directory.
  - Document any important information about the dataset in the `README.md` inside the `data/` directory.

- **Results**: 
  - Ensure all results, such as figures and logs, are stored in the `results/` directory. Organize the results by type (e.g., figures, logs).

- **Notebooks**: 
  - If you use Jupyter notebooks, make sure they are well-documented and demonstrate key steps of your project.

- **README**: 
  - Provide detailed documentation for your project, including how to set up and run the code, and any important observations or conclusions.

- **Final Submission**: 
  - Before submitting, ensure the repository contains all necessary components, is well-organized, and that the code runs smoothly from start to finish.
 
---

## How to Submit Your Homework

### Using VSC and GitHub

1. **Click the Homework Folder**: [Homework Folder Link](https://classroom.github.com/a/gnoG7Bjh)  
2. **Access Your Individual Folder**: After clicking the link, you should be redirected to your individual homework folder. Make sure you’re logged into your account if prompted.  
   Example (for Ben): [Ben's Folder](https://github.com/iSTAREducation/cmpt243-assignemnts-Benimo12.git)
3. **Open the Homework Folder in VSC**:  
   - In the VSC Explorer sidebar, right-click in the folder and select `Paste` to add the files/codes and your work.
4. **Save Your Changes**: Use `Ctrl + S` (Windows) or `Cmd + S` (Mac).
5. **Push Your Changes**: Use the `Source Control` panel in VSC or push using the terminal.

---

### Using a Browser

1. **Click the Homework Folder**: [Homework Folder Link](https://classroom.github.com/a/gnoG7Bjh)  
2. **Access Your Individual Folder**: After clicking the link, you should be redirected to your individual homework folder. Make sure you’re logged into your account if prompted.  
   Example (for Ben): [Ben's Folder](https://github.com/iSTAREducation/cmpt243-assignemnts-Benimo12.git)
3. **Add Files**:  
   - Click `Add Files` and then select `Upload files`.
4. **Commit Changes**: Click `Commit Changes` to finalize the submission.
