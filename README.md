# play-with-kotlin-dataframe
playing with kotlin dataframe


### Run it as a docker, and load ipynb file from workspace directory
`docker run -it --rm --name kotlin_notebook -v $(pwd):/home/jovyan/workspace -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -e CHOWN_HOME=yes knonm/kotlin-notebook:latest`
