# Automating Data Narratives with Intelligent Agents

## Project Overview

This project aims to develop a small-scale intelligent agent that generates data narratives or summaries from structured datasets. By analyzing the Iris dataset, the agent provides insights into flower species based on key measurements. The project demonstrates skills in intelligent agents, data analysis, and narrative generation.

## Project Description

The project leverages the Iris dataset to perform basic data analysis, including calculating summary statistics, identifying trends, and generating natural language narratives. It uses the following features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species

The intelligent agent analyzes the dataset and presents findings in a clear, understandable format.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

This project uses the [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) from the UCI Machine Learning Repository. It contains measurements of iris flowers across three species: Setosa, Versicolor, and Virginica.

## Getting Started

To run this project, you will need Python and the required libraries installed on your system. You can set up your environment by following these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/clizar5302/Simple-Intelligent-Agent-ColeLizar.git
   cd Simple-Intelligent-Agent-ColeLizar
   ```

2. **Create a virtual environment (optional):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required libraries:**

   ```bash
   pip install pandas matplotlib seaborn
   ```

## Usage

1. Open the Jupyter Notebook file `intelligentAgentDataNarrative.ipynb`.
2. Run each cell sequentially to execute the code.
3. The notebook will generate a data narrative and visualizations based on the Iris dataset.

## Example Output

After running the notebook, you will see a generated data narrative similar to the following:

```
This dataset contains measurements of iris flowers across three species: Setosa, Versicolor, and Virginica.
The average sepal length of Setosa is 5.01 cm, the average sepal width is 3.42 cm, the average petal length is 1.46 cm, and the average petal width is 0.24 cm.
The average sepal length of Versicolor is 5.94 cm, the average sepal width is 2.77 cm, the average petal length is 4.26 cm, and the average petal width is 1.33 cm.
The average sepal length of Virginica is 6.59 cm, the average sepal width is 2.97 cm, the average petal length is 5.55 cm, and the average petal width is 2.03 cm.
```

Additionally, a pair plot visualization of the dataset will be displayed.

## License

This project is licensed under the MIT License.
