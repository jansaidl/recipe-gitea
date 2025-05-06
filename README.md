# Zerops x Gitea
The concept of a utility tool illustrates how to set up and use the technologies supported by [Zerops](https://zerops.io).

<br />

## Deploy on Zerops
You can add the latest version of Gitea to your project by clicking the ```Import Services``` button in the project details and then copying the provided code.


## How to create your first user

Open Gitea app remote web terminal and execute:

`gitea --config ./gitea.ini admin user create --username example --password example --admin --must-change-password --email admin@exmaple.com`


## How to generate RUNNER secret token

Open Gitea app remote web terminal and execute:

`gitea --c ./gitea.ini  actions generate-runner-token | zsc setSecretEnv RUNNER_TOKEN`

