# Relatório: Automatize o Terraform com GitHub Actions

## Resumo

Neste relatório, exploramos a integração entre GitHub Actions e Terraform Cloud para automatizar a implantação de uma instância de servidor web EC2 acessível publicamente dentro de um espaço de trabalho do Terraform Cloud. GitHub Actions adiciona integração contínua aos repositórios do GitHub, permitindo automatizar a construção, testes e implantações de software. Automatizar o Terraform com CI/CD promove boas práticas de configuração, colaboração e simplifica o fluxo de trabalho do Terraform.

A infraestrutura é definida utilizando o Terraform, um software de infraestrutura como código (IaC) que permite definir e provisionar recursos de infraestrutura de maneira declarativa. Utilizamos recursos gratuitos da AWS para a demonstração.

O tutorial aborda os seguintes pontos:

- Configuração do Terraform Cloud e criação de um espaço de trabalho.
- Configuração de credenciais da AWS e geração de um token de API do Terraform Cloud.
- Configuração de um repositório GitHub e adição de segredos para integração com Terraform Cloud.
- Revisão dos fluxos de trabalho do GitHub Actions para planificação e aplicação do Terraform.
- Criação de um pull request para testar o fluxo de trabalho.
- Verificação da instância EC2 provisionada e destruição dos recursos e espaço de trabalho.

## Conceitos Aprendidos
- GitHub Actions: Integração contínua automatizada para repositórios do GitHub, permitindo criar fluxos de trabalho personalizados para construir, testar e implantar software.
- Terraform Cloud: Plataforma de colaboração de IaC da HashiCorp que permite armazenar, gerenciar e automatizar a implantação de infraestrutura.
- Infraestrutura como Código (IaC): Abordagem para definir e provisionar infraestrutura de computação, redes e serviços usando arquivos de configuração.
- AWS: Amazon Web Services, uma plataforma de serviços em nuvem que oferece uma ampla gama de serviços de computação, armazenamento, banco de dados, entre outros.

## Demonstração

Aqui estão os principais passos da demonstração:
- Configuração do Terraform Cloud: Criação de um espaço de trabalho no Terraform Cloud, configuração de credenciais da AWS e geração de um token de API do Terraform Cloud.
- Configuração do Repositório GitHub: Configuração de segredos para integração com o Terraform Cloud.
- Revisão dos Fluxos de Trabalho do GitHub Actions: Revisão dos arquivos de configuração YAML que definem os fluxos de trabalho do GitHub Actions para planificação e aplicação do Terraform.
- Criação de Pull Request: Criação de um pull request para testar o fluxo de trabalho.
- Verificação da Instância EC2: Verificação da instância EC2 provisionada e verificação da disponibilidade pública.
- Destruição de Recursos: Destruição dos recursos e espaço de trabalho no Terraform Cloud.

## Demonstração em Imagens


## Conclusão

Neste relatório, exploramos como automatizar o Terraform usando GitHub Actions e Terraform Cloud. Demonstramos a configuração e execução de um fluxo de trabalho completo, desde a criação do espaço de trabalho até a verificação da instância EC2 provisionada. Automatizar a infraestrutura oferece benefícios significativos, como maior eficiência, consistência e rastreabilidade das mudanças na infraestrutura. Este tutorial fornece uma base sólida para incorporar práticas de automação em projetos de infraestrutura.
