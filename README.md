# Dysco Pipeline

## Description
The `dysco_pipeline` is a project for neuroimaging data analysis, focused on calculating eigenvalues and eigenvectors of neuroimaging time series data. It uses libraries such as `numpy`, `scipy`, `matplotlib`, and `seaborn` to perform analyses and visualizations.

## Project Structure
```
/home/jupiter/work/dysco_pipeline/
├── dysco_pipeline/
│   ├── __init__.py
│   └── notebooks/
│       └── scripts1.ipynb
├── main.py
├── pyproject.toml
├── README.md
└── requirements.txt
```

## Installation

### Prerequisites
- Python 3.12 or higher
- Poetry for dependency management

### Installation Steps
1. Clone the repository:
    ```bash
    git clone <REPOSITORY_URL>
    cd dysco_pipeline
    ```

2. Create a virtual environment:
    ```bash
    python3.12 -m venv .venv
    source .venv/bin/activate
    ```

3. Install dependencies using Poetry:
    ```bash
    poetry install
    ```

## Usage
### Running the Main Script
You can run the main script `main.py` to install the project's dependencies:
```bash
python main.py
```

### Using the Jupyter Notebook
The project includes a Jupyter notebook (`scripts1.ipynb`) that demonstrates how to use the `Group_dysco_analysis` class to perform data analyses.

To start the Jupyter Notebook:
```bash
jupyter notebook
```

Open the `scripts1.ipynb` file and run the cells to see the analysis in action.

## Contribution
Contributions are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
Emilie W. - [emiliegracew@gmail.com](mailto:emiliegracew@gmail.com)