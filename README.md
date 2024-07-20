# Football Player Analysis

## Introduction
This project analyzes a dataset of football players to draw insights about their attributes, wages, and more. The data includes variables like players' mentality, foot preference, position, potential rating, and wages.

## Data Source
To understand how variables like players' mentality were measured, further investigation into the data source is needed.

## Conclusions
Based on the analysis, we can conclude that:

1. **Messi is the best player**.
2. **Kevin De Bruyne is currently the highest paid**.
3. **Majority of football players are right footed**.
4. **Majority of football players are centerbacks/central defenders**.
5. **There is generally a positive relationship between players' potential rating and wages**.
6. **However, among the top 15 players, this relationship is not consistent.**
7. **England has the most representation among countries in the data, followed by Germany**.

## Project Structure
The project is structured as follows:

- `football_players.csv`: The dataset containing information about football players.
- `Football_Player_Analysis.ipynb`: Jupyter Notebook containing the code and analysis.
- `README.md`: This file.

## How to Run the Project
1. **Clone the repository**:
    ```bash
    git clone <repository-url>
    ```
2. **Navigate to the project directory**:
    ```bash
    cd <project-directory>
    ```
3. **Install the necessary libraries**:
    ```bash
    pip install pandas matplotlib seaborn
    ```
4. **Open the Jupyter Notebook**:
    ```bash
    jupyter notebook Football_Player_Analysis.ipynb
    ```
5. **Run the cells in the notebook to see the analysis and visualizations**.

## Code and Analysis
The Jupyter Notebook `Football_Player_Analysis.ipynb` contains the following sections:

1. **Load necessary libraries**:
    - Import libraries such as `pandas`, `matplotlib`, and `seaborn`.

2. **Load the dataset**:
    - Read the `football_players.csv` file into a pandas DataFrame.

3. **Display the first few rows of the dataset**:
    - Use the `head()` method to preview the dataset.

4. **Best player analysis**:
    - Identify and display the best player based on overall rating.

5. **Highest paid player analysis**:
    - Identify and display the highest paid player based on wage.

6. **Foot preference analysis**:
    - Visualize the distribution of players' preferred foot.

7. **Position analysis**:
    - Visualize the distribution of players' positions.

8. **Relationship between potential rating and wages**:
    - Visualize the relationship between players' potential rating and wages.

9. **Top 15 players analysis**:
    - Visualize the relationship between potential rating and wages for the top 15 players.

10. **Country representation analysis**:
    - Visualize the top 10 countries by player representation.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgements
- The dataset was provided by [data source].
- This analysis was conducted using Python, pandas, matplotlib, and seaborn.
