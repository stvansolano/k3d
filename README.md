# My Codespace

[Twitter: @stvansolano](https://twitter.com/stvansolano)

## Do you like it? Give a Star! :star:

If you like or are using this project to learn or start your own solution, please give it a star. I appreciate it!

A ready-to-use, templated GitHub Codespace that I regularly use for VS Code on GitHub (Codespaces).

## Batteries included

- Docker
- Kubernetes (WIP)
- NodeJS
- .NET

Extensions

- Docker
- Kubernetes

## k3d commands

```
k3d cluster create mycluster \
    && k3d kubeconfig merge mycluster --kubeconfig-switch-context
```