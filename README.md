# Topsis-Pretrained-Model
# TOPSIS for Text Similarity Metrics

## Description

This repository provides a Python-based implementation of the **Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS)**. The script evaluates pretrained models based on various text similarity and linguistic metrics to assist in multi-criteria decision-making. The method ranks models based on their similarity to an ideal solution.

## Features

- **Text Similarity Metrics**: Includes Cosine Similarity, Jaccard Similarity, Euclidean Distance, and Manhattan Distance.
- **Linguistic Metrics**: Includes BLEU Score, ROUGE Score, and Perplexity.
- **Decision-Making**: Applies the TOPSIS method to rank pretrained models effectively.
- **Customizable Weights and Impacts**: Specify the importance and direction (maximization or minimization) for each metric.

## Installation

To set up the environment for running the TOPSIS script, ensure Python 3.x is installed. Then, install the required dependencies using:

```bash
pip install pandas numpy
```

## Usage

Run the script from the command line using:

```bash
python topsis.py <input_file> <weights> <impacts> <output_file>
```

### Parameters:

- `<input_file>`: Path to the CSV file containing data for pretrained models.
- `<weights>`: Comma-separated weights assigned to each metric (7 metrics in total).
- `<impacts>`: Comma-separated signs for each metric (`+` for maximization, `-` for minimization).
- `<output_file>`: Path to save the output CSV file with rankings.

## Output

After execution, the `results.csv` file will include performance scores and rankings for the models.

## License

This project is open-source and distributed under the MIT License. Feel free to use, modify, and distribute it as needed.

Let us know if you have any questions or need further assistance!

