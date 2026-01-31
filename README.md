# MLX Beginner Examples

This project demonstrates how to use the [MLX](https://github.com/ml-explore/mlx) library on Apple Silicon. It includes basic examples and a performance benchmark comparing MLX with NumPy.

## Setup

Follow these steps to set up your environment.

### 1. Create a Virtual Environment

```bash
python3 -m venv venv
```

### 2. Activate the Virtual Environment

- **On macOS/Linux:**
  ```bash
  source venv/bin/activate
  ```

- **On Windows:**
  ```bash
  venv\Scripts\activate
  ```

### 3. Install Requirements

Install the necessary packages (including Jupyter and Matplotlib) using `pip`.

```bash
pip install -r requirements.txt
```

## Running the Examples

We recommend using the Jupyter Notebook for the best experience, including interactive charts.

1.  Start the notebook server:
    ```bash
    jupyter notebook
    ```
2.  Open `1.ipynb` in the browser interface that appears.
3.  Run all cells to see the MLX vs NumPy benchmark!

## What's Included

- **Basic Operations**: Creating arrays, arithmetic, and matrix multiplication.
- **Performance Benchmark**: A direct comparison of matrix multiplication speed between MLX (GPU) and NumPy (CPU), visualized with a chart.
