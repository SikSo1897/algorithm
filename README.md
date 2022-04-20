```
docker run -it --rm \
    -p 8888:8888 \
    --user root \
    -e NB_USER="my-username" \
    -e CHOWN_HOME=yes \
    -w "/home/${NB_USER}" \
    jupyter/base-notebook
```