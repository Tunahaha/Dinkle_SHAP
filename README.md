# Dinkle_SHAP: Deep SHAP with LSTM or Other Models

This repository contains the implementation of Deep SHAP based on LSTM or other models. SHAP (SHapley Additive exPlanations) is a unified measure of feature importance that assigns each feature an importance value for a particular prediction.

[SHAP GitHub Repository](https://github.com/slundberg/shap)

## Usage

To use this project, run the following command in your terminal:

```sh
python model_example.py
```

You can use your own model, `x_train`, and `x_test`.

## Options

The script accepts several options:

- `--partNo` or `-N`: Allows you to change your part number.
- `--model_name` or `-m`: Allows you to change your model.
- `--x_train` or `-xtr`: Allows you to change your `x_train`.
- `--x_test` or `-xte`: Allows you to change your `x_test`.

You can see more options by running `model_example.py -h`.

For example:

```sh
python model_example.py -N 0162B00100 -m model.pt
```

This command means your part number is `0162B00100` and your model is `model.pt`.

All options have default values.
