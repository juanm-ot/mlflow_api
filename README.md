# mlflow_api
This script was developed to simulate put into production of a classification model

The execution was done from the Sklearn Docker facilitated in the course:
docker run --rm -it
    -name sklearn
    -p 5001:5000
    -p 8082:8082
    -p 8888:8888
    -v "$PWD":/workspace
    jdvelasq/sklearn:1.0.2
    
The notebook contains:
> Base code
> Function to change stage to productive 
> Using as model serve
> Calling API from the terminal

