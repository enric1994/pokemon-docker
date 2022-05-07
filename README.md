# Dockerized pokemon generation using ruDALL-E

## Setup
* In order to run the code [Docker, Docker-Compose](https://gist.github.com/enric1994/3b5c20ddb2b4033c4498b92a71d909da) and [NVIDIA-Docker](https://github.com/NVIDIA/nvidia-docker) are required. The code has been tested on a NVIDIA RTX 2080 Ti (8 images per minute)
* Download `pytorch_model.bin` from [here](https://huggingface.co/minimaxir/ai-generated-pokemon-rudalle/tree/main) and place it in the root folder.

## Generating endless pokemons

1. In the `docker` folder run `docker-compose up -d`
2. Access the container `docker exec -it main bash`
3. Start the script `python main.py`.

Now your GPU will generate pokemons forever :)

## Reference

https://github.com/minimaxir/ai-generated-pokemon-rudalle