# unnecessary-poetry

An app to create silly, unnecessary poems out of everyday experiences or thoughts.

Credit where credit is due:
* This repo is inspired by and very heavily based upon the [hello-genai](https://github.com/docker/hello-genai) repository
* Helpful resources: [Docker Model Runner announcement](https://www.docker.com/blog/introducing-docker-model-runner/) and [dockerdocs](https://docs.docker.com/model-runner/#integrate-the-docker-model-runner-into-your-software-development-lifecycle)


## Requirements
* macOS
* [Docker Desktop](https://docs.docker.com/desktop/setup/install/mac-install/)

## Quick start
1. Clone the repository
```
git clone https://github.com/docker/unnecessary-poetry
cd unnecessary-poetry
```

2. Make any necessary changes to the parameters defined in the [`.env`](./.env) file
* `LLM_BASE_URL`: The base URL of the LLM API
* `LLM_MODEL_NAME`: The model name to use


3. Run the application - note that building the docker image can take a few minutes depending on which model you've chosen.
```
./run.sh
```

4. Have fun generating unnecessary poems with AI!
* 🎨  GenAI poet: [http://localhost:8080](http://localhost:8080)
* 🔎  Swagger docs: [http://localhost:8080/api/docs](http://localhost:8080/api/docs)