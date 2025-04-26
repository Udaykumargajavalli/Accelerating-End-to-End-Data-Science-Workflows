
# GPU-Accelerated Graph Analytics

This project demonstrates the acceleration of graph analytics workflows using GPU computing. It showcases how leveraging GPU capabilities can significantly enhance the performance of graph-based computations.

## Overview

Graph analytics involves processing and analyzing data represented as graphs to uncover relationships, patterns, and insights. Traditional CPU-based processing can be time-consuming for large-scale graphs. By utilizing GPUs, this project aims to accelerate graph analytics tasks, making them more efficient and scalable.

## Repository Structure

- `task2_student.pptx`: A presentation detailing the project's objectives, methodologies, and results.

## Getting Started

### Prerequisites

- A system equipped with a compatible NVIDIA GPU.
- CUDA Toolkit installed and configured.
- Python 3.6 or higher.
- Required Python libraries:
  - `networkx`
  - `numpy`
  - `matplotlib`
  - `cudf` (for GPU DataFrames)
  - `cugraph` (for GPU-accelerated graph analytics)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Udaykumargajavalli/Accelerating-End-to-End-Data-Science-Workflows.git
   cd Accelerating-End-to-End-Data-Science-Workflows/GPU-Accelerated%20Graph%20Analytics
   ```

2. Set up a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required libraries:

   ```bash
   pip install networkx numpy matplotlib cudf cugraph
   ```

   *Note: Installing `cudf` and `cugraph` may require additional steps depending on your system configuration. Refer to the [RAPIDS AI](https://rapids.ai/start.html) documentation for detailed instructions.*

## Usage

1. Prepare your graph data or use existing datasets compatible with `cugraph`.
2. Utilize the provided scripts or develop your own to perform graph analytics tasks such as:
   - PageRank computation
   - Shortest path algorithms
   - Community detection
3. Visualize and interpret the results using tools like `matplotlib`.

## Results

The project demonstrates significant performance improvements in graph analytics tasks when utilizing GPU acceleration compared to traditional CPU-based methods. Detailed results and benchmarks are presented in the `task2_student.pptx` file.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or new features to add, feel free to fork the repository and submit a pull request.


## Acknowledgments

- [RAPIDS AI](https://rapids.ai/) for providing GPU-accelerated data science libraries.
- [NVIDIA](https://www.nvidia.com/) for CUDA and GPU technologies.

