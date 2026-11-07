# Cesar Barbosa de Lana

**Analista de Infraestrutura | Cloud & DevOps**  
São Paulo, SP · [cesarlana1511@gmail.com](mailto:cesarlana1511@gmail.com) · [LinkedIn](https://www.linkedin.com/in/cesarlana) · [GitHub](https://github.com/CesarLana)

---

## 👤 Sobre Mim & Resumo Profissional

Profissional de tecnologia com sólida base em suporte e infraestrutura de TI em ambiente corporativo crítico do setor bancário (Itaú) e financeiro (B3). Possuo conhecimentos práticos em Windows Server/Desktop, Linux, Microsoft 365, Microsoft Entra ID (Azure AD), AWS, Docker, Git, Python e ServiceNow (ITSM). Busco atuar na área de Infraestrutura, Cloud & DevOps, implementando soluções escaláveis em nuvem e automação de processos operacionais.

---

## 💼 Experiência Profissional

### **DXC Technology** *(Novembro de 2025 – Novembro de 2026)*

#### **Analista de Suporte Técnico — Projeto B3**
*Outubro de 2026 – Novembro de 2026 (Projeto Temporário / Rollout)*
- Atuação com escopo fechado no projeto de modernização do parque tecnológico da **B3 (Bolsa de Valores)**, prestando suporte técnico presencial de hardware e conectividade de rede.
- Gerenciamento e acompanhamento de chamados corporativos utilizando as plataformas de ITSM **Helix** e **InvGate**.
- Preparação, configuração e troca de **4 máquinas por dia (cerca de 80 equipamentos entregues no projeto)**, incluindo imagens de SO, perfis de usuário, backup, restore e troubleshooting.

#### **Analista de Infraestrutura Jr — Projeto Itaú**
*Novembro de 2025 – Setembro de 2026*
- Atuação em ambiente crítico do setor bancário, prestando suporte técnico presencial e remoto com estrito cumprimento de SLAs operacionais.
- Administração de identidades, grupos e permissões de acesso utilizando **Microsoft 365**, **Microsoft Entra ID (Azure AD)**, **Active Roles** e **ServiceNow (ITSM)**.
- Diagnóstico de conectividade, troubleshooting de redes e configuração de estações de trabalho e sistemas corporativos.

---

### **AeC Contact Center — Agente de Suporte Técnico N1/N2**
*Abril de 2025 – Julho de 2025*
- Atendimento técnico e suporte N1/N2 a usuários corporativos, com diagnóstico remoto de problemas de rede e conectividade.
- Registro, categorização e acompanhamento de chamados e incidentes por meio da plataforma **Salesforce**.

---

## 🚀 Projetos em Destaque

### 📦 [Deploy de Aplicação Web com Docker & Amazon ECR](https://github.com/CesarLana/projeto-devops-aws-docker)
- Conteinerização de aplicação web com imagem leve baseada em **Nginx Alpine (~25MB)**.
- Orquestração local simplificada via **Docker Compose**.
- Autenticação e publicação de imagens no registro privado **Amazon ECR** via AWS CLI v2 com tokens temporários.
- **Tecnologias:** `Docker` `Docker Compose` `Nginx` `Amazon ECR` `AWS CLI v2` `Linux`

### 📜 [Infraestrutura como Código (IaC) com AWS CloudFormation](https://github.com/CesarLana/aws-lab-cloudformation)
- Provisionamento declarativo e gerenciamento de ciclo de vida de recursos de nuvem em YAML (VPC, Subnets, S3 e EC2).
- Resolução dinâmica de AMIs mais recentes via **AWS Systems Manager Parameter Store**.
- Atualizações incrementais de pilha (Change Sets) sem downtime de infraestrutura.
- **Tecnologias:** `CloudFormation` `IaC` `YAML` `AWS SSM` `VPC` `EC2` `S3`

---

## ☁️ Labs Práticos de Arquitetura AWS (Escola da Nuvem · AWS re/Start)

Repositórios contendo os códigos executáveis, scripts de automação, políticas IAM e documentação de arquitetura desenvolvidos durante a formação técnica AWS re/Start:

| Laboratório Prático | Arquitetura & Implementação | Tecnologias |
|:---|:---|:---|
| 🌐 **[Balanceamento de Carga & Auto Scaling](https://github.com/CesarLana/aws-lab-alb-autoscaling)**<br>`aws-lab-alb-autoscaling` | Alta disponibilidade multi-AZ com Application Load Balancer, Target Groups e Auto Scaling Group com política de escalabilidade baseada em alvo de 50% de CPU. | `ALB` `ASG` `EC2` `CloudWatch` |
| 🔄 **[Alta Disponibilidade com Failover](https://github.com/CesarLana/aws-lab-route53-failover)**<br>`aws-lab-route53-failover` | Resiliência ativo/standby entre Zonas de Disponibilidade (Multi-AZ) com Route 53 Failover Routing, Health Checks com intervalo rápido de 10s e alarmes via SNS. | `Route 53` `SNS` `Health Check` |
| 🔒 **[Acesso Remoto Seguro sem SSH](https://github.com/CesarLana/aws-lab-ssm-session-manager)**<br>`aws-lab-ssm-session-manager` | Administração remota segura de servidores EC2 sem portas de entrada abertas na internet (porta 22/SSH fechada) via AWS Systems Manager Session Manager e Run Command. | `SSM` `Session Manager` `IAM` |
| 🗄️ **[Migração de Banco de Dados para RDS](https://github.com/CesarLana/aws-lab-rds-migration)**<br>`aws-lab-rds-migration` | Migração de banco local (MariaDB no EC2) para serviço gerenciado Amazon RDS Multi-AZ em subnets privadas, com dump/restore e credenciais no Parameter Store. | `RDS` `MariaDB` `mysqldump` `SSM` |
| 🐍 **[Backup de Volumes EBS com Python](https://github.com/CesarLana/aws-lab-ebs-backup-boto3)**<br>`aws-lab-ebs-backup-boto3` | Rotina de automação de snapshots de volumes EBS em Python com Boto3, agendada via Cron, com retenção configurável e expurgo automático de backups antigos. | `Python` `Boto3` `EBS` `Cron` |
| 📜 **[Provisionamento de Usuários IAM em Lote](https://github.com/CesarLana/aws-lab-iam-automation-bash)**<br>`aws-lab-iam-automation-bash` | Script Bash para provisionamento em massa de usuários e grupos no AWS IAM via arquivo CSV, com permissões por perfil e troca obrigatória de senha no 1º acesso. | `Bash` `AWS CLI` `IAM` `Security` |
| 🌐 **[Hospedagem de Site Estático no S3](https://github.com/CesarLana/aws-lab-s3-static-website)**<br>`aws-lab-s3-static-website` | Hospedagem de site estático no Amazon S3 com AWS CLI v2, Bucket Policy de leitura pública e script Bash para deploy e sincronização contínua. | `S3` `AWS CLI` `Bash` `Web Hosting` |
| 🛣️ **[Arquitetura de Rede VPC Segura](https://github.com/CesarLana/aws-lab-vpc-networking)**<br>`aws-lab-vpc-networking` | Segmentação de rede com VPC, Subnets Pública e Privada, Internet Gateway, NAT Gateway para saída externa segura e Bastion Host para administração. | `VPC` `NAT Gateway` `Bastion Host` `Networking` |
| 📜 **[Infraestrutura como Código (IaC)](https://github.com/CesarLana/aws-lab-cloudformation)**<br>`aws-lab-cloudformation` | Infraestrutura como Código (IaC) com AWS CloudFormation em YAML: provisionamento e ciclo de vida incremental de VPC, S3 e EC2 com AMI dinâmica via Parameter Store. | `CloudFormation` `IaC` `YAML` `DevOps` |
| ⚡ **[Processamento Serverless com Lambda](https://github.com/CesarLana/aws-lab-lambda-serverless)**<br>`aws-lab-lambda-serverless` | Arquitetura Serverless orientada a eventos (*Event-Driven*): gatilho de upload no Amazon S3 executando função Python no AWS Lambda e alertando via SNS. | `AWS Lambda` `Serverless` `S3 Trigger` `SNS` |
| 📊 **[Monitoramento & Governança](https://github.com/CesarLana/aws-lab-cloudwatch-monitoring)**<br>`aws-lab-cloudwatch-monitoring` | Observabilidade e governança: CloudWatch Agent via SSM Run Command, filtros de métrica para erros HTTP 404, alarmes com SNS e regras de compliance com AWS Config. | `CloudWatch` `SSM` `AWS Config` `SNS` |

---

## 🛠 Competências Técnicas

- **Cloud & Containers:** AWS (EC2, S3, RDS, IAM, VPC, ALB, Route 53, SSM, CloudWatch, Lambda), AWS CloudFormation (IaC), Docker, Docker Compose.
- **Sistemas & Identidades:** Microsoft Entra ID (Azure AD), Active Directory, Windows Server / Desktop, Linux, ServiceNow (ITSM), Helix, InvGate, Microsoft 365.
- **Automação & Ferramentas:** Shell Script (Bash), Python (Boto3), SQL, Git e GitHub, Power BI.

---

## 🎓 Formação Acadêmica & Certificações

- **Análise e Desenvolvimento de Sistemas** — FMU | FIAM-FAAM *(em curso, 4º semestre)*
- **Programa AWS re/Start** — Escola da Nuvem / AWS *(Cloud, Redes, Segurança, Linux, Banco de Dados)*
- **X Escola Avançada em Big Data Analysis** — ICMC - Universidade de São Paulo (USP)
- **Técnico em Logística** — Etec Centro Paula Souza
- **Manutenção de Sistemas Operacionais e Redes** — SENAI
