# Scratch Networks

This repository contains implementations of various neural network architectures, including feed-forward networks using different approaches, and a diffusion model for image generation, all within a single Jupyter Notebook. This was built during my course completion of deep learning specialization at coursera.

## Project Overview

This project explores several key areas in neural network development:

*   **Feed-Forward Networks in Numpy:** Implemented using three distinct approaches:
    *   Matrix-based calculations for efficient processing.
    *   Logistic regression as a foundational building block.
    *   A dynamic neural network class for greater flexibility and customization.
*   **Diffusion Model:** A generative model designed to understand and generate 15x15 pixel character images. This demonstrates the power of diffusion processes in image synthesis.


## Technologies Used

*   Python
*   PyTorch
*   NumPy (for numerical computation)
*   Jupyter Notebook
*   Other relevant libraries (e.g., Matplotlib for visualization - to be implemented)

## Setup and Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/bhuvanmdev/scratch-networks.git
    ```

2.  Navigate to the project directory:

    ```bash
    cd scratch-networks
    ```

3. It's recommended to create a virtual environment:

    ```bash
    python3 -m venv .venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

4. Install the required dependencies (if any, specify them in a `requirements.txt` file):

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the code, you will need to open the Jupyter Notebook and configure the venv to the notebook(just open the notebook using VScode to auto config with the env).


## TODO

*   **Modularization:** Refactor the code within the notebook into more organized functions and potentially separate Python modules for better structure and reusability (This will eventually lead to multiple .py files).
*   **Visualization:** Implement graphs to visualize training progress (loss curves, accuracy, etc.) using Matplotlib or similar libraries.
*   **Documentation:** Add more comprehensive docstrings and comments within the notebook cells.
*   **Add requirements.txt:** Create a requirements file for easy dependency installation.

## Contributing

Contributions are welcome! Especially for the TODO lists. Refer to [CONTRIBUTING.md](https://github.com/bhuvanmdev/scratch-networks/CONTRIBUTING.md) for more details.

## License

This is under the [MIT license](https://github.com/bhuvanmdev/scratch-networks/License).
