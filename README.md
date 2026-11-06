# Cesar Lana

**Analista de Infraestrutura | Cloud Computing**  
São Paulo, SP · [LinkedIn](https://www.linkedin.com/in/cesarlana/) · [GitHub](https://github.com/CesarLana)

---

## 💼 Experiência Profissional

### **DXC Technology — Analista de Infraestrutura Jr (Projeto Itaú)**
*Novembro de 2025 – Setembro de 2026*
- Atuação em ambiente crítico do setor bancário, prestando suporte técnico e operacional presencial e remoto.
- Administração de identidades, acessos e permissões utilizando **Microsoft Entra ID (Azure AD)**, **Active Directory** e **Microsoft 365**.
- Abertura, gestão e resolução de incidentes e requisições via **ServiceNow (ITSM)**, cumprindo SLAs operacionais.
- Troubleshooting de redes, diagnóstico de conectividade, manutenção e configuração de sistemas.

### **AeC Contact Center — Agente de Suporte Técnico N1/N2**
*Abril de 2025 – Julho de 2025*
- Atendimento técnico e suporte N1/N2, diagnóstico remoto de problemas de rede e conectividade.
- Registro e acompanhamento de chamados técnicos via plataforma **Salesforce**.

---

## 🚀 Projetos em Destaque

### 📦 [Deploy de Aplicação Web com Docker & AWS ECR](https://github.com/CesarLana/projeto-devops-aws-docker)
- Containerização de aplicação web com imagem leve baseada em **Nginx Alpine (~25MB)**.
- Orquestração local simplificada via **Docker Compose**.
- Autenticação e publicação de imagens no registro privado **Amazon ECR** via AWS CLI v2 com token temporário.
- **Tecnologias:** `Docker` `Nginx` `Amazon ECR` `AWS CLI` `Linux`

### 📊 [FinPortfolio — Análise de Portfólio & Risco](https://github.com/CesarLana/FinPortfolio)
- Aplicação analítica em Python para cálculo de fronteira eficiente (Markowitz) e modelos de alocação (Risk Parity).
- Cálculo de métricas de risco de cauda: Value at Risk (VaR Histórico e Paramétrico) e CVaR / Expected Shortfall.
- Painel interativo construído em **Streamlit** com gráficos via **Plotly**.
- Cobertura com **testes unitários automatizados (pytest)** rodando via **GitHub Actions (CI)**.
- **Tecnologias:** `Python` `Streamlit` `Docker` `Pandas` `Scipy` `GitHub Actions`

---

## ☁️ Labs Práticos de AWS (Escola da Nuvem & Arquitetura)

Repositórios contendo os códigos executáveis, scripts de automação, políticas IAM e documentação de arquitetura desenvolvidos durante a formação técnica AWS re/Start:

| Lab / Repositório | Arquitetura & Implementação | Tecnologias |
|:---|:---|:---|
| 🌐 **[aws-lab-alb-autoscaling](https://github.com/CesarLana/aws-lab-alb-autoscaling)** | Alta disponibilidade multi-AZ com Application Load Balancer, Target Groups e Auto Scaling Group baseado em métricas de CPU do CloudWatch. | `ALB` `ASG` `EC2` `CloudWatch` |
| 🔄 **[aws-lab-route53-failover](https://github.com/CesarLana/aws-lab-route53-failover)** | Resiliência ativo/standby entre zonas e regiões com Amazon Route 53 Failover Routing, Health Checks HTTP de 10s e alarmes via Amazon SNS. | `Route 53` `SNS` `Health Check` |
| 🔒 **[aws-lab-ssm-session-manager](https://github.com/CesarLana/aws-lab-ssm-session-manager)** | Administração remota de servidores EC2 com Zero-Trust (porta 22/SSH fechada na internet) via AWS Systems Manager Session Manager e Run Command. | `SSM` `Session Manager` `IAM` |
| 🗄️ **[aws-lab-rds-migration](https://github.com/CesarLana/aws-lab-rds-migration)** | Migração de banco on-instance (MariaDB no EC2) para serviço gerenciado Amazon RDS Multi-AZ em subnets privadas com desacoplamento via Parameter Store. | `RDS` `MariaDB` `mysqldump` `SSM` |
| 🐍 **[aws-lab-ebs-backup-boto3](https://github.com/CesarLana/aws-lab-ebs-backup-boto3)** | Rotina de automação de snapshots de volumes EBS em Python com Boto3, agendada via Cron, com retenção automática e expurgo de backups antigos. | `Python` `Boto3` `EBS` `Cron` |
| 📜 **[aws-lab-iam-automation-bash](https://github.com/CesarLana/aws-lab-iam-automation-bash)** | Script Bash para provisionamento em massa de usuários no AWS IAM a partir de arquivo CSV, com menor privilégio e troca obrigatória de senha no 1º acesso. | `Bash` `AWS CLI` `IAM` `Security` |
| 🌐 **[aws-lab-s3-static-website](https://github.com/CesarLana/aws-lab-s3-static-website)** | Hospedagem de site estático no Amazon S3 com AWS CLI v2, Bucket Policy de leitura pública e script Bash para deploy e sincronização contínua. | `S3` `AWS CLI` `Bash` `Web Hosting` |
| 🛣️ **[aws-lab-vpc-networking](https://github.com/CesarLana/aws-lab-vpc-networking)** | Segmentação e segurança de rede com VPC, Subnets Pública e Privada, Internet Gateway, NAT Gateway e Bastion Host para acesso administrativo. | `VPC` `NAT Gateway` `Bastion Host` `Networking` |
| 📜 **[aws-lab-cloudformation](https://github.com/CesarLana/aws-lab-cloudformation)** | Infraestrutura como Código (IaC) com AWS CloudFormation em YAML: provisionamento e ciclo de vida incremental de VPC, S3 e EC2 com AMI dinâmica. | `CloudFormation` `IaC` `YAML` `DevOps` |
| ⚡ **[aws-lab-lambda-serverless](https://github.com/CesarLana/aws-lab-lambda-serverless)** | Arquitetura Serverless orientada a eventos (*Event-Driven*): gatilho de upload no Amazon S3 executando função Python no AWS Lambda e alertando via SNS. | `AWS Lambda` `Serverless` `S3 Trigger` `SNS` |
| 📊 **[aws-lab-cloudwatch-monitoring](https://github.com/CesarLana/aws-lab-cloudwatch-monitoring)** | Observabilidade e governança: CloudWatch Agent via SSM Run Command, filtros de métrica para erros HTTP 404, alarmes com SNS e regras de compliance com AWS Config. | `CloudWatch` `SSM` `AWS Config` `SNS` |

---

## 🛠 Competências Técnicas

- **Sistemas & Operações Corporativas:** Windows Server / Desktop, Microsoft 365, Azure AD (Entra ID), Active Directory, ServiceNow (ITSM), Linux.
- **Cloud & Containers:** AWS (EC2, S3, RDS, IAM, VPC, Security Groups, ECR, ALB, Route 53, SSM), Docker, Docker Compose.
- **Linguagens & Automação:** Python (Boto3, Pandas), SQL (MySQL), Bash para automação, Power BI, Git e GitHub.

---

## 🎓 Formação & Especializações

- **Análise e Desenvolvimento de Sistemas** — FMU | FIAM-FAAM *(em curso, 4º semestre)*
- **Formação AWS re/Start** — Escola da Nuvem *(Cloud, Redes, Segurança, Linux, Banco de Dados)*
- **X Escola Avançada em Big Data Analysis** — ICMC - Universidade de São Paulo (USP)
- **Técnico em Logística** — Etec Centro Paula Souza
