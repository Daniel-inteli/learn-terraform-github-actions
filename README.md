# Atividade ponderada - Automate Terraform with GitHub Actions

## Introdução

Este relatório resume os conceitos e tecnologias explorados no tutorial "Automate Terraform with GitHub Actions", focando na integração entre o Terraform Cloud e o GitHub Actions para criar um fluxo de trabalho de integração e entrega contínua (CI/CD).

## Tecnologia utilizadas 

### Terraform Cloud

Terraform Cloud é uma plataforma da HashiCorp que gerencia estados do Terraform, executa aplicações de configurações de infraestrutura e organiza colaboração em equipe. Oferece suporte integrado para webhooks do GitHub, permitindo a automação de workflows de Terraform diretamente através de eventos no repositório GitHub.

### GitHub Actions

GitHub Actions é uma funcionalidade do GitHub que permite a automação de workflows de software diretamente nos repositórios do GitHub. Pode ser usada para automatizar testes, builds e deployments de código através de eventos específicos como commits e pull requests.

## Configuração

Para utilizar o workflow, precisamos configurar o Terraform e o GitHub, no Terraform criamos um workspace e adicionamos as credenciais da AWS, e também geramos um token de API do Terraform para autenticação. No GitHub criamos o repositório a partir do template e adicionamos o token do terraform.

## Resultados

Após realizar as alterações que o tutorial solicita tutorial, o pull request com o terraform gera os seguintes resultados.

![Pull Request](/assets/print-terraform.png)

![Terraform](/assets/print-terraform2.png)

![Terraform](/assets/ec2-aws.png)

![Terraform](/assets/ec2-terraform.png)