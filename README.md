# terraform-aws-msk

![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/tedilabs/terraform-aws-msk?color=blue&sort=semver&style=flat-square)
![GitHub](https://img.shields.io/github/license/tedilabs/terraform-aws-msk?color=blue&style=flat-square)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white&style=flat-square)](https://github.com/pre-commit/pre-commit)

Terraform module which creates resources for MSK (Managed Streaming for Apache Kafka) on AWS.

- [cluster](./modules/cluster)
- [topic](./modules/topic)
- [vpc-connection](./modules/vpc-connection)


## Target AWS Services

Terraform Modules from [this package](https://github.com/tedilabs/terraform-aws-msk) were written to manage the following AWS Services with Terraform.

- **AWS MSK (Managed Streaming for Apache Kafka)**
  - Cluster
  - Topic
  - VPC Connection


## Examples

- [topic](./examples/topic)
- [vpc-connection](./examples/vpc-connection)


## Self Promotion

Like this project? Follow the repository on [GitHub](https://github.com/tedilabs/terraform-aws-msk). And if you're feeling especially charitable, follow **[posquit0](https://github.com/posquit0)** on GitHub.


## License

Provided under the terms of the [Apache License](LICENSE).

Copyright © 2023-2026, [Byungjin Park](https://www.posquit0.com).
