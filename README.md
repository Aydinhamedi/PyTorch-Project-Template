# Classification with PyTorch

<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue"/> <img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white"/>  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/> 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

This repository provides a template for image classification projects using PyTorch. It includes a Jupyter notebook (`main.ipynb`) that contains the main code for the project.

## Getting Started

1. Clone this repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Open the `main.ipynb` Jupyter notebook and follow the instructions.

## Data Organization

Your data should be organized in the following structure:

```
├───Database
│   ├───cache # This folder will be created by the program
│   └───Data # Put all the folders with images here
#       Example ⬎
│       ├───battery
│       ├───biological
│       ├───brown-glass
│       ...
│       └───white-glass
```

Each subfolder in the `Data` directory represents a class, and should contain the images for that class. For example, the `battery` folder should contain images of batteries, the `biological` folder should contain images of biological items, and so on.

## READMEs in Folders

Each folder contains a README file that explains the contents of the folder. Please read these files for more information about the data.

## Running the Code

To run the code, simply open the `main.ipynb` Jupyter notebook and execute the cells in order.

## Contributing

Contributions are welcome! Please read the contributing guidelines before making any changes.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
<pre>
 Copyright (c) 2024 Aydin Hamedi
 
 This software is released under the MIT License.
 https://opensource.org/licenses/MIT
</pre>