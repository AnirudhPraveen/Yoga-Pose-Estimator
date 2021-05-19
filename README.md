#### 1. Deploy the Model

To run the docker image, which automatically starts the model serving API, run:

    docker run -e CORS_ENABLE=true -e WERKZEUG_RUN_MAIN=true -it -p 5000:5000 codait/max-human-pose-estimator

