# AI-Powered-Data-Insights-and-Visualizations-using-RAG
This project leverages GPT-3.5 and LLaMA to automatically generate insightful visualizations from a dataset. Users can ask questions related to the dataset, and the system will respond with either:
- **Visualizations** (heatmaps, bar plots, box plots, etc.), along with **insights** drawn from the data.
- **Numerical outputs** with a summary or explanation.

## Key Features

- **Query-Based Data Insights**: Users can ask questions like "Give a correlation matrix for HbA1c_level, blood_glucose_level, age, and bmi" and the system will return a visualization along with insights from the LLM. (Here I used the open-source diabetic dataset)
- **Visualizations**: Automatic generation of visual outputs using libraries such as seaborn and matplotlib.
- ![image](https://github.com/user-attachments/assets/b7fc2cef-54c1-43c1-872f-f97d5ce37b43)
- **Human-Like Analysis**: The project uses GPT-3.5 and LLaMA models to provide an interpretation of the data, making it easy to understand relationships within the dataset.
- Response from the model: "The correlation matrix for HbA1c_level, blood_glucose_level, age, and bmi shows the strength and direction of the relationships between these variables. The values in the heatmap range from -1 to 1, with 1 indicating a perfect positive correlation, -1 indicating a perfect negative correlation, and 0 indicating no correlation.

From the visualization, we can see that there is a positive correlation between HbA1c_level and blood_glucose_level, which is expected as higher blood glucose levels are associated with higher HbA1c levels. There is also a positive correlation between age and blood_glucose_level, suggesting that blood glucose levels may increase with age. The correlation between age and bmi appears to be weaker, indicating a less strong relationship between these variables.

Overall, this correlation matrix provides valuable insights into the relationships between these key health indicators, which can be useful for understanding potential risk factors and informing healthcare decisions."

## Technologies Used

- **Python**: Core programming language for the project.
- **pandas**: Data manipulation and analysis library.
- **seaborn**: Statistical data visualization library.
- **matplotlib**: Comprehensive library for creating static, animated, and interactive visualizations.
- **GPT-3.5 and LLaMA**: Large language models used for generating code and insights from data.

## Installation

Follow these steps to set up the project on your local machine:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-project-name.git
    ```

2. Navigate to the project directory:
    ```bash
    cd your-project-name
    ```

3. Install the dependencies using `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

The `requirements.txt` file contains all the necessary libraries for this project, including versions of `llama-index`, `arize-phoenix`, `pyvis`, and more.
