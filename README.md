To run docker with build context:

docker build git@github.com:mominux/my_docker_train.git#master -t build_context_gitub:latest
docker run --rm build_context_gitub:latest
