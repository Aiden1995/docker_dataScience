# docker_dataScience
Containerized environment for Data Science

Build Command for windows: docker build -t <image_name> --file ./Dockefile.txt .
Run Command for Windows:docker run --name docker_ds_env -p 8889:8889 -v "cd/notebooks/opt/notebooks" -d docker_data_env
Save into conatiner: docker save -o datascience_python_env.tar docker_data_env

