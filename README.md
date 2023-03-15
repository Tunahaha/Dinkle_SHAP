# Dinkle_SHAP
This repository is for Deep SHAP based on LSTM or other model.

[SHAP](https://github.com/slundberg/shap).
### How to use?
you can use `python model_example.py` on CMD
### Options
you can use your own model、x_train and x_test

Use `--partNo` or `-N` means you can change your part number.

Use `--model_name` or `-m` means you can change your model.

Use `--x_train` or `-xtr` means you can change your part number.

Use `--x_test` or `-xte` means you can change your part number.

You can see more when you use `model_example.py -h`.

For example:

Use `python model_example.py -N 0162B00100 -m model.pt` means your part number is 0162B00100 and your model is model.pt.

Of course all of them have defaults.

