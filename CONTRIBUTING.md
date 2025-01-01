# CONTRUBUTING

## How to run the Dockerfile locally

'''
## Build image
docker build -t rest-api-flask-python .
## Run container
docker run -dp 5005:5000 -w /app -v ${PWD}:/app -e FLASK_ENV=development rest-api-flask-python sh -c "flask run -host 0.0.0.0"

'''