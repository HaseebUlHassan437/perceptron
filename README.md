
# Perceptron Placement Prediction

This project demonstrates the use of a Perceptron model to predict student placement based on CGPA and resume score. The code is implemented in Google Colab using Python, pandas, seaborn, scikit-learn, and mlxtend for visualization.

## Dataset

The dataset used (`placement.csv`) contains the following columns:
- `cgpa`: Student's CGPA
- `resume_score`: Resume score out of 10
- `placed`: Binary label indicating placement status (0 = Not placed, 1 = Placed)

The CSV file is uploaded in the repository.

## How it Works

1. The dataset is loaded from Google Drive.
2. A scatter plot visualizes the relationship between CGPA and resume score, color-coded by placement status.
3. The first two columns (`cgpa`, `resume_score`) are used as features (`X`), and the `placed` column is used as the target (`y`).
4. A Perceptron model is trained using scikit-learn.
5. The decision boundary is visualized using `mlxtend.plotting.plot_decision_regions`.
6. The model predicts placement for a new data point: `[3, 3]`.

## Requirements

- Python 3.x
- Google Colab (or Jupyter Notebook)
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- mlxtend

## Output

The script displays:
- Dataset preview and shape
- Scatter plot of the data
- Decision boundary of the Perceptron model
- Prediction result for the sample input `[3, 3]`

## Author

**Haseeb Ul Hassan**
