<div align="center">
  <h1>Olá, eu sou Cesar Lana 👋</h1>
  <p><strong>IT Infrastructure Analyst | Cloud Computing (AWS & Azure) | DevOps Jr.</strong></p>
  
  <p>
    <a href="https://www.linkedin.com/in/cesarlana/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:cesarlana1511@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
    <a href="https://github.com/CesarLana"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white" alt="AWS" />
    <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
    <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
    <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform" />
    <img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white" alt="Azure" />
    <img src="https://img.shields.io/badge/ServiceNow-81B5A1?style=flat-square&logo=servicenow&logoColor=white" alt="ServiceNow" />
    <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  </p>
</div>

---

### 👨‍💻 Sobre Mim

Atualmente atuo como **Analista de Suporte e Infraestrutura na DXC Technology** e sou estudante de **Análise e Desenvolvimento de Sistemas** (FMU | FIAM-FAAM). 

Possuo experiência prática em suporte técnico N1/N2, administração de identidades e acessos com **Microsoft Entra ID (Azure AD)** e **AWS IAM**, gerenciamento de incidentes e requisições via **ServiceNow**, além de forte atuação em **troubleshooting** de ambientes corporativos complexos.

Minha jornada técnica é direcionada para **Cloud Computing e DevOps**, tendo construído uma base sólida de projetos práticos através da formação **AWS re/Start (Escola da Nuvem)**, com foco em arquiteturas resilientes, seguras e com governança de custos (FinOps).

---

### 🚀 Projetos Práticos & Laboratórios em Destaque

#### 🐳 1. DevOps & Containerização na Nuvem
* **[Deploy de Aplicação Web com Docker & Amazon ECR](https://github.com/CesarLana/projeto-devops-aws-docker):**
  * Empacotamento de aplicação web com imagem ultra-leve `nginx:alpine` (~25MB), diminuindo a superfície de ataque e acelerando deploys.
  * Autenticação temporária com AWS CLI v2 (`get-login-password`) e publicação segura no registro privado **Amazon ECR**.
  * Orquestração local simplificada com `docker-compose.yml` e deploy automatizado em instâncias **Amazon EC2**.

#### ⚡ 2. Alta Disponibilidade & Resiliência
* **Elastic Load Balancing (ALB) & Auto Scaling Group (ASG):**
  * Construção de AMI customizada para padronização de nós de aplicação.
  * Distribuição de tráfego com **Application Load Balancer** em múltiplas Zonas de Disponibilidade (AZs) e instâncias alocadas em sub-redes privadas.
  * Escalonamento automático baseado em métricas de CPU (alvo de 50%), validado sob teste de estresse de carga e monitoramento em tempo real com **Amazon CloudWatch**.
* **Roteamento de Failover Inteligente com Amazon Route 53:**
  * Configuração de arquitetura ativo/standby entre instâncias em AZs distintas.
  * **Health Check** HTTP com intervalo de 10s e limite de tolerância acoplado a notificações automáticas via **Amazon SNS**.
  * Comutação automática de tráfego sem intervenção humana após teste de queda forçada do nó primário.

#### 💰 3. FinOps & Otimização de Custos (Cost Optimization)
* **Right-Sizing de Infraestrutura Pós-Migração de Banco:**
  * Eliminação de desperdício em instâncias web com remoção de serviços residuais e redução a quente da classe de instância (`t3.small` ➔ `t3.micro`) via AWS CLI.
  * Ajuste do volume de armazenamento **Amazon EBS** de 40 GB para 20 GB.
  * Análise financeira utilizando a **AWS Pricing Calculator**, alcançando redução contínua de **~13% ao mês** no custo total de infraestrutura sem impacto no SLA.

#### 🛡️ 4. Segurança, Gestão de Acessos & Operação sem SSH
* **Administração Segura com AWS Systems Manager (SSM):**
  * Eliminação da necessidade de portas abertas de SSH (porta 22) através do **Session Manager**, permitindo acesso seguro e auditável via console/navegador.
  * Execução remota e padronizada de comandos em escala com **Run Command**.
  * Desacoplamento de credenciais e strings de conexão com o **Parameter Store**.
* **Arquitetura de Bastion Host (Salto Controlado):**
  * Isolamento de servidores de aplicação na rede privada com acesso administrativo restrito através de nó Bastion seguro.
  * Provisionamento automatizado de novas instâncias via terminal utilizando **AWS CLI** e **Parameter Store**.
* **Governança e Criação em Lote no AWS IAM com Shell Script:**
  * Script Bash automatizado para processamento de arquivos CSV, provisionamento em lote de usuários, imposição de troca de senha no primeiro login e aplicação rigorosa do **Princípio do Menor Privilégio**.

#### 🗄️ 5. Bancos de Dados Relacionais Gerenciados (Amazon RDS)
* **Migração de Banco de Dados EC2 (MariaDB) para Amazon RDS:**
  * Desacoplamento de arquitetura monolítica para modelo gerenciado, isolando a base em sub-redes privadas com **DB Subnet Groups**.
  * Extração e restauração consistente de dados via `mysqldump` e `mysql`, reconfiguração da aplicação via Parameter Store e observabilidade de CPU, conexões e IOPS com **CloudWatch**.
* **Amazon RDS MySQL com Implantação Multi-AZ:**
  * Configuração de banco de dados com replicação síncrona em múltiplas AZs e controle restritivo de tráfego via Security Groups.

#### 🐍 6. Automação, Resiliência de Dados & Finanças
* **Automação de Snapshots EBS & Retenção com Python (`boto3`):**
  * Rotina de backup de volumes alocados via AWS CLI agendada com cronjobs no Linux.
  * Script em Python utilizando o SDK **Boto3** para auditar e expurgar snapshots órfãos automaticamente, mantendo política de retenção fixa dos últimos 2 backups.
  * Sincronização e Disaster Recovery com **Amazon S3** (`aws s3 sync`) e restauração através de versionamento de objetos.
* **[FinPortfolio - Sistema Financeiro & Simulação de Monte Carlo](https://github.com/CesarLana/FinPortfolio):**
  * Aplicação analítica desenvolvida em **Python** e containerizada com **Docker**.
  * Integração com a API do Yahoo Finance para cotações em tempo real, simulações de Monte Carlo para otimização da fronteira eficiente de **Markowitz**, cálculo de **VaR/CVaR**, **Risk Parity** e stress testing de crises de mercado com dashboard interativo em **Streamlit** e **Plotly**.

#### 🔍 7. Troubleshooting & Resolução de Incidentes
* **Diagnóstico de Rede e Pilha LAMP:**
  * Resolução de incidentes práticos com inspeção de portas (`nmap`), correção de regras de firewall de Security Groups e análise de logs de inicialização (`cloud-init-output.log` e logs do Apache).

---

### 🛠️ Tecnologias & Ferramentas

```text
┌─────────────────┬──────────────────────────────────────────────────────────────┐
│ Categoria       │ Ferramentas / Tecnologias                                    │
├─────────────────┼──────────────────────────────────────────────────────────────┤
│ Cloud Computing │ AWS (EC2, S3, RDS, VPC, Route 53, ALB, ASG, SSM, IAM), Azure│
│ DevOps & IaC    │ Docker, Docker Compose, Terraform, Git, GitHub Actions       │
│ Sistemas & SO   │ Linux (Ubuntu, Red Hat, Amazon Linux), Bash Scripting        │
│ Linguagens      │ Python (Boto3, Pandas, Streamlit), SQL, JavaScript, HTML/CSS │
│ ITSM & Suporte  │ ServiceNow, Microsoft Entra ID (Azure AD), Active Directory  │
└─────────────────┴──────────────────────────────────────────────────────────────┘
```

---

### 🎓 Formação & Certificações

* **Graduação em Análise e Desenvolvimento de Sistemas** — FMU | FIAM-FAAM (Em andamento)
* **Formação AWS re/Start** — Escola da Nuvem (Cloud Computing, Infraestrutura e DevOps)
* **Extensão Universitária em Big Data Analysis** — Universidade de São Paulo (ICMC - USP)
* **Preparatório AWS Certified Cloud Practitioner (CLF-C02)**

---

### 📊 Estatísticas do GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=CesarLana&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Estatísticas do GitHub de Cesar Lana" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CesarLana&layout=compact&theme=tokyonight&hide_border=true" alt="Linguagens mais usadas" />
</div>

---

<div align="center">
  <p>Conecte-se comigo no <a href="https://www.linkedin.com/in/cesarlana/">LinkedIn</a> ou envie um e-mail para <a href="mailto:cesarlana1511@gmail.com">cesarlana1511@gmail.com</a>.</p>
</div>
