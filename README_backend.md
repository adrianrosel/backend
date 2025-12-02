# Backend del Proyecto – FastAPI

## Instalación

pip install -r requirements.txt

## Ejecución

python -m uvicorn main:app --reload

## Endpoints disponibles

- GET /students
- GET /students/{id}

## Testing

python -m pytest

## Docker

docker build -t daw-backend .
docker run -p 8000:8000 daw-backend

## CI/CD – GitHub Actions

Workflows ubicados en backend/.github/workflows/

- backend-test.yml
- backend-docker.yml

Requiere secrets:

- DOCKERHUB_USERNAME
- DOCKERHUB_TOKEN

## Informacion grafica del repositorio en formato reducido

* 062e266 (HEAD -> rama1_adrianRosel, github/rama1_adrianRosel) Añadir informacion grafica reducida al README de backend
* 355127d hola
* da9424f (origin/main) subir ficheros a un repositorio publico en GitHub