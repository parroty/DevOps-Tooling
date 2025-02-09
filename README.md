[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

# DevOps-Tooling
*A repo containing toolings and software useful for a DevOps Engineer (or if you're setting up your Mac from the beginning)*

### Currently setup for macOS* - Coming soon for Windows & Linux

### Note:
- Install Brew on your macOS first. Type on your command line "brew update" & then install the required tool "brew install <PACKAGE_NAME>
- Most of the tooling can be used by using the brew package manager or other CLI tools suggested below in "". If not, use the links provided to navigate to the installation page of the tool.
- Also note that some of these tools mentioned in Productivity can be subjective based on each individual.

## Package manager
- [HomeBrew - this package manager will be used to install various toolings later](https://brew.sh/)
To install Homebrew :
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Technical tooling & CLI (main)
- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html) - "brew install awscli"
- [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-macos) - "brew install azure-cli"
- [GCP SDK](https://cloud.google.com/sdk/docs/install) - "brew install --cask google-cloud-sdk"
- [Git CLI](https://git-scm.com/download/mac) - "brew install git"
- [Terraform CLI](https://learn.hashicorp.com/tutorials/terraform/install-cli) - "brew install terraform"
- [Docker Desktop - soon to upload an alternative for Docker Desktop (Podman? Containerd?)](https://www.docker.com/products/docker-desktop) 
- [Kubernetes CLI - the famous K8s container orchestator](https://kubernetes.io/docs/tasks/tools/install-kubectl-macos/) - "brew install kubectl"
- [Helm - packagae manager for K8s](https://helm.sh/docs/intro/install/) - "brew install helm"
- [Kind - Local K8s cluster](https://kind.sigs.k8s.io/docs/user/quick-start/) - "brew install kind" & "kind create cluster --name kind-cluster"
- [minikube - Local K8s cluster](https://minikube.sigs.k8s.io/docs/start/) - "brew install minikube" & "minikube start"
- [Python](https://www.python.org/downloads/) - "brew install python3"
- [Postman - Postman is an application used for API testing](https://www.postman.com/downloads/) - "brew install postman"
- [GoLang -  The Go Programming Language](https://go.dev/doc/install) - "brew install go"
- [NodeJS - The JavaScript framework](https://nodejs.org/en/download/) - "brew install node"
- [Ansible - Ansible is an open-source software provisioning, configuration management, and application-deployment tool enabling infrastructure as code](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) - "python -m pip install --user ansible"
- [Postgres app](https://postgresapp.com/)
- [Taskfile - Task is a task runner / build tool that aims to be simpler and easier to use than, for example, GNU Make](https://taskfile.dev/#/) - "brew install task"
- [ArgoCD CLI - Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes](https://argo-cd.readthedocs.io/en/stable/cli_installation/) - "brew install argocd"
- Spacelift?

## Other useful CLIs (supplementary)
- [TFenv - Terraform version manager](https://github.com/tfutils/tfenv) - "brew install tfenv"
- [Pyenv - Pyenv lets you easily switch between multiple versions of Python](https://github.com/pyenv/pyenv) - "brew install pyenv"
- [TLDR - Simplified and community-driven man pages](https://tldr.sh/) - "npm install -g tldr"
- [jq - Lightweight and flexible command-line JSON processor](https://stedolan.github.io/jq/) - "brew install jq"
- [tmux - Terminal multiplexer. It lets you switch easily between several programs in one terminal](https://github.com/tmux/tmux/wiki/Installing) - "brew install tmux"

## Container & Security focused tools
- [kubectx]() - "brew install kubectx"
- [kubens]() - "brew install kubens"
- [Anchore-CLI](https://github.com/anchore/anchore-cli) - 
```sh
sudo easy_install pip
pip3 install --user anchorecli
export PATH=${PATH}:${HOME}/Library/Python/3.9/bin
```
- [Trivy](https://aquasecurity.github.io/trivy/v0.18.3/installation/) - " brew install aquasecurity/trivy/trivy"
- [K9s ]() - 
- [Falco]() - 
- [kube-monkey]()
- [kubesec]() - 
- [Terrascan]() -
- [Clair]() -
- [Checkov]() -

## Productivity tooling: 
- [VS Code - Visual Studio Code is a source-code editor made by Microsoft for Windows, Linux and macOS.](https://code.visualstudio.com/download) - use link or "brew install --cask visual-studio-code".
- [JetBrains Toolbox - IDE manager, used to install IntelliJ IDE and others like PyCharm](https://www.jetbrains.com/toolbox-app/) - "brew install --cask jetbrains-toolbox"
- [iTerm2 - iTerm2 is a replacement for Terminal and the successor to iTerm](https://iterm2.com/) - "brew install iterm2"
- [zsh - Zsh is a shell designed for interactive use, although it is also a powerful scripting language.](https://github.com/ohmyzsh/ohmyzsh) - "brew install zsh"
- [ohmyzsh - Oh My Zsh is an open source, community-driven framework for managing your zsh configuration](https://github.com/ohmyzsh/ohmyzsh) - "brew install ohmyzsh"
- [Notion - Notion is a notetaking software and project management software that is used for note-taking, task management, project management, knowledge management, and personal knowledge management.](https://www.notion.so/desktop) - "brew install --cask notion"
- [Magnet for Mac - An app used to move and resize windows with ease ](https://apps.apple.com/gb/app/magnet/id441258766?mt=12)
- [Spectacle App - Basically, a free version of Magnet. Important note: Spectacle is no longer being actively maintained.](https://www.spectacleapp.com/)
- [Aerial Companion ScreenSaver - Aerial is a free and open-source Mac screen saver](https://aerialscreensaver.github.io/) 

## Other useful links:

- [How to Configure your macOs Terminal with Zsh like a Pro](https://www.freecodecamp.org/news/how-to-configure-your-macos-terminal-with-zsh-like-a-pro-c0ab3f3c1156/)

## Coming soon - in the works
- A script that installs all the toolings (ones that can be automated)
- A setup for Windows & Linux
- Alternative to Docker Desktop?? Containerd? Podman? - Open to suggestions.
- Organise the repo into sub-categories & general organisation.

## Open to contributions

## Layout for collapsible section in README
<details>
  <summary>Click to expand!</summary>
  
  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>
