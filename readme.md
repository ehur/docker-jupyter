docker run -it \
-p 8888:8888 \
--mount type=bind,source=/Users/lhurley/git/docker-jupyter/data,destination=/home/jovyan/data,readonly \
--mount type=bind,source=/Users/lhurley/git/docker-jupyter/work,destination=/home/jovyan/work \
jupyter/scipy-notebook