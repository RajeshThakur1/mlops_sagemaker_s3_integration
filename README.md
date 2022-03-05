##MLOPS-PIPELINE_WITH_MLFLOW_S3_RDS

step-01:-create the env
```commandline
conda create --prefix ./env python=3.7 -y
```

step-02:- activate new env

```commandline
activate new env
```
or
```commandline
source activate ./env
```
STEP 03- install the requirements

```commandline
pip install -r requirements.txt
```

STEP 04 - Create conda.yaml file -
```commandline
conda env export > conda.yaml
```
STEP 05 - Create conda.yaml file -
```commandline
 python .\main.py 0.6 0.8 

```

step 06:- To see the Evaluation metric

```commandline
mlflow ui
```
