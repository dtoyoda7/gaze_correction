# Gaze Correction

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-1.x-orange.svg)](https://www.tensorflow.org/)

Gaze Correction is a powerful deep learning-based solution for correcting the gaze direction in images and videos. This repository provides a comprehensive implementation of a gaze correction model, along with tools for training, evaluating, and deploying the model.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Virtual Environment Setup](#virtual-environment-setup)
  - [Installing Dependencies](#installing-dependencies)
- [Usage](#usage)
  - [Training](#training)
  - [Evaluation](#evaluation)
  - [Inference](#inference)
- [Pretrained Models](#pretrained-models)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites

- Python 3.7 or higher
- [pip](https://pip.pypa.io/en/stable/) package manager
- [virtualenv](https://virtualenv.pypa.io/en/latest/) (optional, but recommended)

### Virtual Environment Setup (Recommended)

It's recommended to use a virtual environment to manage the project's dependencies. Follow these steps to set up a virtual environment:

1. Install virtualenv if you haven't already:

   ```bash
   pip install virtualenv
    ```
2. Install virtualenv if you haven't already:
   
   ```bash
   virtualenv .venv
   ```
3. Activate the virtual environment:
   
   - On Windows:
     
     ```bash
     .venv\Scripts\activate
     ```
     
   - On macOS/Linux:
     
     ```bash
     source .venv/bin/activate
     ```

### Installing Dependencies

1. Clone the repository:
   
   ```bash
   git clone https://github.com/dtoyoda7/Gaze_Correction.git
   cd Gaze_Correction
   ```
   
2. Install the required dependencies:
 
   ```bash
   pip install -r requirements.txt
   ```

   This will install all the necessary Python packages, including TensorFlow 2.x and other libraries required for the gaze correction project.
   
3. (Optional) Install additional development dependencies:
   
   ```bash
   pip install -r requirements-dev.txt
   ```

   This will install additional tools and libraries for development, such as linters, formatters, and testing frameworks.

Now you're ready to start using the gaze correction project. Proceed to the Usage section to learn how to train, evaluate, and use the gaze correction model.
