## Workflow

1. update config.yml
2. update secrets.yml
3. update params.yaml
4. update the entity.yaml
5. update the configuration manager in src config
6. update the components
7. update the pipeline
8. update the main.py
9. update the dvc.yaml

NiQc483h0XEtApxeJhICGDsTzzUMYcVfd2dU6RjflF+ACRBcthXB

docker build -t stanlitoapp.azurecr.io/mlapp:latest .

docker login stanlitoapp.azurecr.io

docker push stanlitoapp.azurecr.io/mlapp:latest
