# build docker image
docker_build('mill-docker', '.', dockerfile='Dockerfile')
# apply deployment
k8s_yaml('./../kubernetes/mill-deployment.yaml')
# apply service
k8s_yaml('./../kubernetes/mill-service.yaml')

