# Olá, eu sou Cesar Lana 👋

### IT Infrastructure Analyst | Cloud Computing (AWS & Azure) | DevOps Jr.

<p align="left">
  <a href="https://www.linkedin.com/in/cesarlana/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:cesarlana1511@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/CesarLana">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

### 👨‍💻 Sobre Mim

Atualmente atuo como **Analista de Suporte e Infraestrutura na DXC Technology** e sou estudante de **Análise e Desenvolvimento de Sistemas** (FMU | FIAM-FAAM).

* 💼 Experiência prática em suporte corporativo N1/N2, administração de identidades e acessos com **Microsoft Entra ID (Azure AD)** e **AWS IAM**, troubleshooting de redes e sistemas, e gestão de incidentes/mudanças via **ServiceNow**.
* ☁️ Formação técnica em nuvem pelo programa **AWS re/Start (Escola da Nuvem)** e extensão universitária em **Big Data Analysis (ICMC - USP)**.
* 🎯 **Foco profissional:** Consolidar minha atuação como **Analista de Nuvem (AWS)** e **DevOps Jr.**, aplicando automação de infraestrutura, arquiteturas resilientes e cultura FinOps (otimização contínua de custos).

---

### 🛠️ Tecnologias & Ferramentas

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,docker,linux,python,bash,azure,terraform,git,github,mysql,postgres,postman,vscode&theme=dark" alt="Arsenal Tecnológico" />
</p>

* **Cloud:** AWS (EC2, S3, RDS, VPC, Route 53, ALB, ASG, Systems Manager, IAM, CloudWatch) & Microsoft Azure
* **DevOps & IaC:** Docker, Docker Compose, Terraform, Git, GitHub
* **Automação & Scripting:** Python (Boto3), Shell Script / Bash
* **Sistemas & Redes:** Linux (Amazon Linux 2023, Red Hat, Ubuntu), Windows Server, Active Directory, DNS, TCP/IP
* **ITSM & Governança:** ServiceNow, Microsoft Entra ID (Azure AD), ITIL

---

### 🚀 Projetos Práticos & Laboratórios em Destaque

#### 🐳 DevOps & Containers
* **[Deploy de Aplicação Web com Docker & Amazon ECR](https://github.com/CesarLana/projeto-devops-aws-docker):**
  * Containerização de site com imagem leve `nginx:alpine` (~25MB), orquestração local com `docker-compose` e publicação autenticada no registro privado corporativo **Amazon ECR**.
* **[FinPortfolio - Sistema Financeiro & Simulação de Monte Carlo](https://github.com/CesarLana/FinPortfolio):**
  * Aplicação analítica desenvolvida em Python e containerizada com Docker, consumindo a API do Yahoo Finance em tempo real, com simulações de Monte Carlo (Markowitz), cálculo de VaR/CVaR e dashboard interativo em Streamlit e Plotly.

#### ⚡ Alta Disponibilidade, Resiliência & FinOps
* **Elastic Load Balancing (ALB) & Auto Scaling Group:**
  * Arquitetura Multi-AZ com Application Load Balancer na frente de instâncias EC2 privadas, launch template baseado em AMI customizada e escalonamento automático acionado por target de 50% de CPU.
* **Roteamento de Failover com Amazon Route 53:**
  * Implementação de resiliência ativo/standby entre Zonas de Disponibilidade distintas com Health Checks HTTP acoplados a alarmes e notificações via Amazon SNS.
* **FinOps: Otimização de Custos e Right-Sizing:**
  * Redução de custos operacionais pós-migração com análise via AWS Pricing Calculator: redimensionamento a quente de instâncias (`t3.small` ➔ `t3.micro`) e ajuste de volumes EBS (40GB ➔ 20GB), alcançando **~13% de economia mensal contínua**.

#### 🛡️ Segurança, Gestão de Acessos & Bancos de Dados
* **Administração sem SSH com AWS Systems Manager (SSM):**
  * Eliminação de portas SSH abertas na internet através do **Session Manager**, execução remota em lote com **Run Command** e centralização de parâmetros com o **Parameter Store**.
* **Migração de Banco de Dados para Amazon RDS (Multi-AZ):**
  * Migração de banco on-instance (MariaDB) para serviço gerenciado Amazon RDS em sub-redes privadas (DB Subnet Group), com strings de conexão desacopladas via Parameter Store e observabilidade no CloudWatch.
* **Automação de Backup & Snapshots com Python (`boto3`):**
  * Script em Python utilizando Boto3 para auditar a conta e manter política de retenção fixa dos últimos 2 snapshots de EBS, e sincronização para S3 com versionamento de objetos.
* **Criação em Lote no IAM via Shell Script:**
  * Automação Bash para processamento de CSV, criação em massa de usuários no AWS IAM com troca de senha obrigatória e concessão por menor privilégio.

---

### 🔍 Casos Práticos de Troubleshooting & Diagnóstico

* **Falha de inicialização em servidor web:** Diagnóstico de serviço Apache parado pós-inicialização de User Data (`systemctl status httpd`) e análise de logs no `cloud-init-output.log`.
* **Bloqueio de rede em Security Groups:** Investigação de timeout de conexão e correção de regras de firewall Inbound, migrando a administração para AWS Systems Manager para eliminar dependência de portas abertas.
* **Incompatibilidade de AMIs entre regiões:** Ajuste em scripts de automação da AWS CLI para busca dinâmica de AMI IDs via Parameter Store (`aws ssm get-parameters`), garantindo portabilidade entre regiões da AWS.

---

### 🎓 Formação & Certificações

* 🎓 **Análise e Desenvolvimento de Sistemas** — FMU | FIAM-FAAM (4º Semestre)
* ☁️ **Formação AWS re/Start** — Escola da Nuvem
* 📊 **X Escola Avançada em Big Data Analysis** — Universidade de São Paulo (ICMC - USP)
* 🎯 **Preparatório:** AWS Certified Cloud Practitioner (CLF-C02)

---

<div align="center">
  <p>Vamos conversar sobre projetos de Cloud, DevOps e Infraestrutura?</p>
  <p>
    <a href="https://www.linkedin.com/in/cesarlana/"><strong>Conecte-se comigo no LinkedIn</strong></a> • 
    <a href="mailto:cesarlana1511@gmail.com"><strong>cesarlana1511@gmail.com</strong></a>
  </p>
</div>
