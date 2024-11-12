# Open WebUI running with bedrock access gateway

## Getting started
1. Clone this repo
2. Run the following commands to setup the repo:
```bash
git submodule init
git submodule update
```
3. Ensure that your AWS credentials are set as environment variables
4. Start the services by running the following command:
```bash
docker compose up --build --force-recreate -d
```
5. Access Open WebUI on localhost:8080
