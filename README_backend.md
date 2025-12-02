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

## Remotos configurados en el repositorio 

PS C:\Users\adrian.rosel\Desktop\proyecto-examen1_2863208\backend> git remote -v
GitLab  https://gitlab.com/adrianrosel/backend.git (fetch)
GitLab  https://gitlab.com/adrianrosel/backend.git (push)
github  https://github.com/adrianrosel/backend.git (fetch)
github  https://github.com/adrianrosel/backend.git (push)
gitlab  https://gitlab.com/adrianrosel/proyecto-examen.git (fetch)
gitlab  https://gitlab.com/adrianrosel/proyecto-examen.git (push)
origin  https://github.com/adrianrosel/proyecto-examen.git (fetch)
origin  https://github.com/adrianrosel/proyecto-examen.git (push)