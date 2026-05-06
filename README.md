# 🔥 PyTorch for Deep Learning

![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)
![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)

A beginner-friendly, hands-on collection of Jupyter notebooks for learning **PyTorch** — the leading deep learning framework used in research and industry. This repository follows a structured, project-based approach to help you go from zero to building real neural networks.

---

## 📖 About This Repository

This repository contains well-commented, step-by-step notebooks designed for anyone who is new to deep learning or PyTorch. Each notebook builds on the previous one, introducing concepts gradually with working code examples and visualizations.

Whether you are a student, developer, or data scientist looking to get started with deep learning, these notebooks will give you a solid foundation.

---

## 📚 Notebooks

| # | Notebook | Topics Covered | Open in Colab |
|---|----------|---------------|---------------|
| 00 | [PyTorch Fundamentals](00_pytorch_fundamentals.ipynb) | Tensors, tensor operations, NumPy interoperability, GPU usage | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SathyaPrakashD/PyTorch-for-Deep-Learning/blob/main/00_pytorch_fundamentals.ipynb) |
| 01 | [PyTorch Workflow](01_pytorch_workflow.ipynb) | End-to-end ML workflow, data prep, model building, training & evaluation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SathyaPrakashD/PyTorch-for-Deep-Learning/blob/main/01_pytorch_workflow.ipynb) |

---

## 🧠 What You Will Learn

### Notebook 00 — PyTorch Fundamentals
The building block of every deep learning model is the **tensor**. This notebook teaches you everything you need to know:

- Creating scalars, vectors, matrices, and multi-dimensional tensors
- - Understanding tensor shapes, dimensions, and data types
  - - Performing arithmetic and matrix operations
    - - Aggregating tensors (min, max, mean, sum)
      - - Reshaping, stacking, squeezing, and permuting tensors
        - - Indexing and slicing tensors
          - - Converting between PyTorch tensors and NumPy arrays
            - - Setting random seeds for reproducibility
              - - Moving tensors to the GPU for accelerated computation
               
                - ### Notebook 01 — PyTorch Workflow
                - Learn the standard end-to-end workflow every deep learning engineer follows:
               
                - - Preparing and splitting data for training and testing
                  - - Building a model using `nn.Module`
                    - - Defining a loss function and optimizer
                      - - Writing a training loop
                        - - Evaluating model performance
                          - - Saving and loading models
                            - - Making predictions on new data
                             
                              - ---

                              ## 🚀 Getting Started

                              ### Option 1 — Run in Google Colab (Recommended for Beginners)
                              No installation required! Click any **"Open in Colab"** badge in the table above to run the notebooks directly in your browser with free GPU access.

                              ### Option 2 — Run Locally

                              **Step 1 — Clone the repository**
                              ```bash
                              git clone https://github.com/SathyaPrakashD/PyTorch-for-Deep-Learning.git
                              cd PyTorch-for-Deep-Learning
                              ```

                              **Step 2 — Create a virtual environment (optional but recommended)**
                              ```bash
                              python -m venv venv
                              source venv/bin/activate        # On Windows: venv\Scripts\activate
                              ```

                              **Step 3 — Install dependencies**
                              ```bash
                              pip install torch torchvision torchaudio
                              pip install jupyter matplotlib numpy
                              ```

                              **Step 4 — Launch Jupyter Notebook**
                              ```bash
                              jupyter notebook
                              ```
                              Then open any `.ipynb` file from the file browser.

                              ---

                              ## 🛠️ Prerequisites

                              You do not need prior deep learning experience, but the following will help:

                              - **Python basics** — variables, loops, functions, lists
                              - - **NumPy** — familiarity with arrays is helpful but not required
                                - - **Basic math** — comfortable with simple algebra and the idea of a function
                                 
                                  - ---

                                  ## 📂 Repository Structure

                                  ```
                                  PyTorch-for-Deep-Learning/
                                  ├── 00_pytorch_fundamentals.ipynb   # Tensors and core PyTorch operations
                                  ├── 01_pytorch_workflow.ipynb       # End-to-end deep learning workflow
                                  ├── LICENSE                         # MIT License
                                  └── README.md                       # This file
                                  ```

                                  ---

                                  ## 💡 Tips for Beginners

                                  - **Run every cell** — don't just read. Type the code yourself to build muscle memory.
                                  - - **Experiment** — change values, break things, and observe what happens.
                                    - - **Read error messages** — PyTorch errors are descriptive; they tell you exactly what went wrong.
                                      - - **Use Google Colab** if you don't have a GPU — it provides free GPU/TPU access.
                                        - - **Be patient** — deep learning has a learning curve, but each concept builds on the last.
                                         
                                          - ---

                                          ## 🔗 Resources

                                          - [PyTorch Official Documentation](https://pytorch.org/docs/stable/index.html)
                                          - - [PyTorch Tutorials](https://pytorch.org/tutorials/)
                                            - - [Zero to Mastery — Learn PyTorch for Deep Learning](https://zerotomastery.io/courses/learn-pytorch/)
                                              - - [fast.ai Practical Deep Learning](https://course.fast.ai/)
                                               
                                                - ---

                                                ## 📄 License

                                                This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

                                                ---

                                                ## 🙏 Acknowledgements

                                                These notebooks are created as part of the **Zero to Mastery — PyTorch for Deep Learning** course. Special thanks to the ZTM team for the excellent curriculum.

                                                ---

                                                *Happy learning! If you find this repository helpful, please consider giving it a ⭐*
