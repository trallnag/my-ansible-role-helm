> This role is not meant to be shared. It is only used by myself.
> I use this role in my playbooks by adding the repo as a Git submodule.

# Ansible Role `helm`

- <https://github.com/helm/helm>

## FAQ

## How to change Helm version?

Get the version reference you want.

- <https://github.com/helm/helm/releases>

Go to [`tasks/main.yaml`](tasks/main.yaml) and set the version in the
"Install with asdf" task.
