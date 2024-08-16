# Marketing-Chatbot

This Python project analyzes Amazon product reviews using natural language processing techniques to preprocess text data, compute TF-IDF vectorization, and apply linear regression to predict ratings based on text content. Additionally, it includes a functionality to find similar reviews using cosine similarity.

## Installation

To run this project, you need Python installed on your system. The required libraries can be installed via pip:

```bash
pip install pandas scikit-learn
```

## Usage

1. **Data Setup:**
   - Place your Amazon reviews dataset named `amazon.csv` in the project root. The dataset should contain columns like `review_content` and `rating`.

2. **Run Analysis:**
   - Execute the main script to perform analysis:
     ```bash
     python amazon_analysis.py
     ```

3. **Results:**
   - The script will output the Mean Squared Error of the regression model and print similar reviews for a predefined query.

## Features

- **Data Preprocessing:** Converts review texts to lowercase for uniformity.
- **TF-IDF Vectorization:** Transforms text data into a matrix of TF-IDF features.
- **Linear Regression:** Predicts ratings based on the processed text.
- **Cosine Similarity:** Finds and displays reviews similar to a given query based on content similarity.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
