# Run the scripts in the order showed here

## 1. Run the XGBoost project using the following commands

```
python sysargs.py --learning-rate 0.2 --colsample-bytree 0.8 --subsample 0.9
```

You can try experimenting with different parameter values

## 2. You can open MLFlow UI and compare your results

```
mlflow ui
```

## 3. Run the JUPYTER NOTEBOOK and run the experiments in the notebooks

To track experiments:
```
01_train_model.ipynb
```

To register models:
```
02_register_model.ipynb
```

## To see the jupyter results, run the MLFlow UI with the following command

```
mlflow ui --backend-store-uri sqlite:///mlflow.db
```