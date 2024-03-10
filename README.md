# Football Analyst - Data Science Project

This project focuses on data processing, data merging, data imputation, and testing various machine learning models for predicting the price categories of football players based on their data from the last 3 seasons and league prices. The machine learning models developed have an average accuracy of approximately 56% due to limited statistical data availability.

## Using

To obtain the required datasets, please download the data from [Kaggle](https://www.kaggle.com/datasets/davidcariboo/player-scores) and export it in its original form to the `data/raw_data` directory. The directory structure should resemble the following:

* data/raw_data/appearances.csv
* data/raw_data/players.csv
* etc.


## Project Structure

- **data**: Contains the datasets used in the project.
- **models**: Includes both test and production models and model.pkl.
- **notebooks**: Contains Jupyter notebooks used for data preprocessing and model development.

## Requirements

To replicate this project, you will need to install the following Python libraries:

```
pandas
numpy
scikit-learn
matplotlib
seaborn
```

You can install these libraries using pip:

```bash
pip install -r requirements.txt
```

## Additional Information

If you need further information or have any questions regarding the project, feel free to contact [kamilf827@gmail.com]. 

This project is open-source and contributions are welcome. Please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for more details on how to contribute.

## License

This project is licensed under the [MIT License](LICENSE).
