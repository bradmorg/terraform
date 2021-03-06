
This is a Terraform installation and usage cheat sheet. See full video here:
https://www.youtube.com/watch?v=ItIFWFutUCA&

# Installation

1. Install Choco
``` shell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```
2. Install Terraform installation
``` shell
choco install terraform
```

3. Verify Installation
``` shell
terraform version
```

## Starting a Terraform Project
``` shell
Terraform init
```

## Pushing out a Terraform file
``` shell
terraform apply
```