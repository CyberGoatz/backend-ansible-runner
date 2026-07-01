## Planned use

`docker build -t cybergoatz-ansible-runner .`

`docker run -v /tmp/crczp-tmp/sandboxxx-666/ssh_conf:/root/.ssh -v /tmp/crczp-tmp/sandboxxx-666/inventory.ini:/app/inventory.ini:ro cybergoatz-ansible-runner -u https://github.com/nejake-repo`
