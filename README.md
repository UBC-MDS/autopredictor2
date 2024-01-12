# autopredictor

The Autopredictor Python package streamlines the process of selecting and assessing machine learning models, presenting a simplified approach for evaluating different regression models without intricate manual setup. This tool facilitates the exploration of multiple models on a dataset, minimizing the coding required for selecting and fitting various models. Utilizing preprocessed and trained data, the package evaluates models using default settings, enabling users to swiftly comprehend model performance. By computing and showcasing diverse performance metrics for each model, it offers an efficient means to compare their effectiveness. Overall, Autopredictor provides a convenient and quick framework for initial model assessment and comparison in machine learning workflows.

This package includes four main functions:
- `fit`: Fits a clean, preprocessed training data into eight different regression models. The function returns a dictionary containing four various metric scores for each model
- `show_all`: Generates a DataFrame presenting each scoring metric alongside the respective model, while outputting a clear overview of the results in a table format
- `best_score`: Identifies the best score with respect to a specific scoring metric along with the corresponding model
- `model_result`: Returns a summary of all the scoring metrics associated with a specific machine learning model

This package focuses on eight widely used regressor models, providing a curated selection that covers a broad range of algorithmic approaches. This package are designed to be user-friendly through automation with default configurations for each model. It is catered for both beginners by eliminating complicated model arguments and for experts by providing baseline results. However, this package may not be suitable for experienced practitioner who requires customized regressor models. Within the Python ecosystem, there is an existing, well developed and maintained library named [lazypredict](https://pypi.org/project/lazypredict/) that offer similar functionality with a wider range of models, including classification models.

## Installation

```bash
$ pip install autopredictor
```

## Usage

- TODO

## Contributors

Anu Banga, Arturo Rey, Sharon Voon, Zeily Garcia

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`autopredictor` was created by Anu Banga, Arturo Rey, Sharon Voon, Zeily Garcia. It is licensed under the terms of the MIT license.

## Credits

`autopredictor` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
