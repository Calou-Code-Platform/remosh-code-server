# Remosh-Code-Server
A simple Code-server environment for docker.

# Environment
| Name | Description |
|---|---|
| ``username`` | Your name, default is ``linux`` |
| ``password`` | Your password, default is ``password`` |
| ``sudo_password`` | Sudo password, default is ``sudo_password`` |

# Port
We just using port ``3100`` make ssh port.

# Push
```sh
docker run --name=ccp -e username=username password=password -p 3100:3100 --restart always ghcr.io/calou-code-platform/remosh-code-server
```