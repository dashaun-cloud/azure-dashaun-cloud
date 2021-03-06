[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

# AZURE-DASHAUN-CLOUD

## [Getting Started](#getting-started) | [About](#about-the-project) | [License](#license)

## Getting Started

### Prerequisites

1.  [Terraform](https://terraform.io]) [CLI](https://terraform.io/downloads.html)
2.  [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)

### Step 1. Getting Started

Login to Azure using the Azure CLI

```bash
az login
```
>Login with a Service Principal will also work
 
Login using an Azure Service Principal

```bash
az login --service-principal --username APP_ID --tenant TENANT_ID --password [password || /path/to/cert]
```

### Step 2: Clone the repository

```bash
git clone https://github.com/dashaun-cloud/azure-dashaun-cloud
```

### Step 3: Initialize the repository

```bash
cd azure-dashaun-cloud
terraform init
```
>The output should include: ```Terraform has been successfully initialized```


### Step 4: Verify the plan

The 'plan' output will show you everything being created by the template.

```bash
terraform plan
```
>The plan step does not make any changes in Azure


### Step 5: Apply the plan

When the plan looks good, 'apply' the template.

```bash
terraform apply
```

### Step 6: Optionally, Cleanup

Remove the resources that were created.

```bash
terraform destroy
```

## About The Project

Just getting started.

### See Also

* [Redis Developer](https://developer.redislabs.com/create/azure/)

### Built With

* [Terraform](https://terraform.io)

### Contributing

Pull-requests are welcomed!

## License

Distributed under the MIT License. See `LICENSE` for more information.

[contributors-shield]: https://img.shields.io/github/contributors/dashaun-cloud/azure-dashaun-cloud.svg?style=for-the-badge
[contributors-url]: https://github.com/dashaun-cloud/azure-dashaun-cloud/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/dashaun-cloud/azure-dashaun-cloud.svg?style=for-the-badge
[forks-url]: https://github.com/dashaun-cloud/azure-dashaun-cloud/network/members
[stars-shield]: https://img.shields.io/github/stars/dashaun-cloud/azure-dashaun-cloud.svg?style=for-the-badge
[stars-url]: https://github.com/dashaun-cloud/azure-dashaun-cloud/stargazers
[issues-shield]: https://img.shields.io/github/issues/dashaun-cloud/azure-dashaun-cloud.svg?style=for-the-badge
[issues-url]: https://github.com/dashaun-cloud/azure-dashaun-cloud/issues
[license-shield]: https://img.shields.io/github/license/dashaun-cloud/azure-dashaun-cloud.svg?style=for-the-badge
[license-url]: https://github.com/dashaun-cloud/azure-dashaun-cloud/blob/main/LICENSE
