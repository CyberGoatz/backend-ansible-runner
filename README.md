## Planned use

`docker build -t cybergoatz-ansible-runner .`

`docker run -v /tmp/crczp-tmp/sandboxxx-666/ssh_conf:/root/.ssh -v /tmp/crczp-tmp/sandboxxx-666/inventory.ini:/app/inventory.ini:ro cybergoatz-ansible-runner -u https://github.com/nejake-repo`

## Options

- `-u <url>`: git repository URL.
- `-r <revision>`: branch, tag or commit to check out (optional).
- `-i <file>`: inventory file path.
- `-a <url>`: answers storage API.
- `-p <path>`: folder inside the repository that holds `variables.yml` and `provisioning/` (optional, default is the repository root). Must be relative, without `..`, and only contain `A-Za-z0-9._/-`.
- `-c`: clean up user answers.
