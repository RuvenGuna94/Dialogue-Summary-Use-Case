## Project Overview
This repository contains the `dialogue_summary.ipynb` notebook, which demonstrates techniques for summarizing dialogues using the FLAN-T5 models. The project leverages libraries, such as `transformers` and `datasets`, for working with pre-trained models and datasets.

## Features
- Summarization of dialogues using pre-trained language models.
- Flexible customization of model parameters and datasets.
- Visualization and analysis of text results.

## Prerequisites
Ensure you have the following installed on your system:
- Python 3.8 or later
- Jupyter Notebook or JupyterLab

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/dialogue_summary.git
   cd dialogue_summary
   ```

2. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open `dialogue_summary.ipynb` in your browser and follow the instructions in the notebook.

## Contributing
Feel free to fork the repository and submit pull requests. Suggestions and improvements are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.


## Developer Log

### 12 Dec 2024
- Created new repo
- Added in Jupyter Notebook

### 13 Dec 2024
- Updated repo description
- Completed section 1 of the use case

### 14 Dec 2024
- Configured local env to run code
    - Installed required conda env and kernel 
- Completed the following
    - Package install
    - Load libraries
    - load dataset & exploratory analysis
    - load model & associated tokenizer
    - Performed sample text encoding and decoding

### 15 Dec 2024
- Completed notebook with zero shot, one shot and few shot inference code
