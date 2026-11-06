<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,23,43&height=180&section=header&text=Cesar%20Lana&fontSize=42&fontAlignY=38&animation=fadeIn&desc=IT%20Infrastructure%20Analyst%20%7C%20Cloud%20Computing%20%7C%20DevOps%20Jr.&descAlignY=58&descSize=18" width="100%" alt="Header Banner" />

  <p align="center">
    <a href="https://git.io/typing-svg">
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=FF9900&center=true&vCenter=true&width=550&lines=IT+Infrastructure+Analyst+%40+DXC+Technology;Cloud+Computing+%26+AWS+Infrastructure;DevOps+Enthusiast+%7C+Docker+%26+Terraform;Automating+Environments+with+Python+%26+Bash" alt="Typing SVG" />
    </a>
  </p>

  <p align="center">
    <a href="https://www.linkedin.com/in/cesarlana/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:cesarlana1511@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <img src="https://komarev.com/ghpvc/?username=CesarLana&label=Profile%20Views&color=orange&style=for-the-badge" alt="Profile Views" />
  </p>
</div>

---

### 👨‍💻 Sobre Mim

Sou **Analista de Suporte e Infraestrutura na DXC Technology** e estudante de **Análise e Desenvolvimento de Sistemas** no 4º semestre (FMU | FIAM-FAAM).

Minha rotina envolve suporte corporativo N1/N2, administração de identidades com **Microsoft Entra ID (Azure AD)** e **AWS IAM**, troubleshooting de redes e sistemas, e gestão de incidentes/mudanças via **ServiceNow**.

🎯 **Foco de Carreira:** Consolidar minha atuação como **Analista de Nuvem (AWS)** e **DevOps Jr.**, aplicando automação de infraestrutura, arquitetura resiliente, segurança por design e cultura FinOps (otimização de custos).

---

### 🛠️ Arsenal Tecnológico & Ferramentas

<div align="center">
  <img src="https://skillicons.dev/icons?i=aws,docker,linux,python,bash,azure,terraform,git,github,mysql,postgres,postman,vscode&theme=dark" alt="Skills Grid" />
</div>

<br>

<div align="center">

| Categoria | Tecnologias |
|---|---|
| **Cloud Computing** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white) (EC2, S3, RDS, VPC, Route 53, ALB, ASG, SSM, IAM, CloudWatch) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) |
| **DevOps & Automação** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **Sistemas & SO** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) (Amazon Linux 2023, Red Hat, Ubuntu, Debian) ![Windows Server](https://img.shields.io/badge/Windows_Server-0078D4?style=flat-square&logo=windows&logoColor=white) |
| **ITSM & Governança** | ![ServiceNow](https://img.shields.io/badge/ServiceNow-81B5A1?style=flat-square&logo=servicenow&logoColor=white) ![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![Microsoft Entra ID](https://img.shields.io/badge/Entra_ID-225B99?style=flat-square&logo=microsoftazure&logoColor=white) |
| **Banco de Dados** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-CC292B?style=flat-square&logo=microsoftsqlserver&logoColor=white) |

</div>

---

### 🚀 Vitrine de Projetos Práticos de Engenharia

#### 🏗️ 1. Infraestrutura em Nuvem, Alta Disponibilidade & FinOps (AWS)

| Projeto / Solução | Descrição da Arquitetura & Decisões de Engenharia | Stack Tecnológica |
|---|---|---|
| **[Auto Scaling & Elastic Load Balancing](https://github.com/CesarLana)** | Arquitetura multi-AZ com Application Load Balancer na frente de instâncias EC2 privadas. Launch Template baseado em AMI customizada, com escalonamento automático acionado por target de 50% de CPU e alarmes no CloudWatch. | `AWS ALB`, `Auto Scaling`, `CloudWatch`, `EC2` |
| **[Route 53 DNS Failover Automatizado](https://github.com/CesarLana)** | Implementação de resiliência ativo/standby entre Zonas de Disponibilidade. Health Check HTTP (10s/2 tentativas) acoplado a notificações de alarme via Amazon SNS e chaveamento automático de tráfego. | `Route 53`, `Amazon SNS`, `Health Checks`, `EC2` |
| **[FinOps: Cost Optimization & Right-Sizing](https://github.com/CesarLana)** | Redução de custos operacionais pós-migração com análise via AWS Pricing Calculator: eliminação de banco local, redimensionamento a quente de `t3.small` ➔ `t3.micro` e redução de volume EBS (40GB ➔ 20GB) resultando em **~13% de economia contínua**. | `FinOps`, `AWS CLI`, `Right-Sizing`, `EBS` |
| **[Arquitetura de Bastion Host & SSM sem SSH](https://github.com/CesarLana)** | Administração remota segura eliminando a exposição de portas SSH (porta 22) com **AWS Systems Manager (Session Manager)**, execução remota via **Run Command** e bastion host controlado para provisionamento em rede privada. | `AWS SSM`, `Bastion Host`, `Parameter Store`, `IAM` |
| **[Migração para Amazon RDS & Multi-AZ](https://github.com/CesarLana)** | Desacoplamento de banco de dados legado on-instance (MariaDB) para serviço gerenciado Amazon RDS em sub-redes privadas (DB Subnet Group), com strings de conexão centralizadas no Parameter Store e réplica Multi-AZ. | `Amazon RDS`, `MySQL`, `MariaDB`, `mysqldump` |

<br>

#### 🐳 2. DevOps, Automação & Engenharia de Software

| Projeto / Solução | Descrição da Solução | Repositório |
|---|---|---|
| **Containerização Web com Docker & AWS ECR** | Empacotamento de website em container com **Nginx Alpine** (~25MB), orquestração com Docker Compose e pipeline de publicação autenticado no registro privado corporativo **Amazon ECR**. | [🔗 Ver Projeto](https://github.com/CesarLana/projeto-devops-aws-docker) |
| **FinPortfolio (Python, Docker & Monte Carlo)** | Sistema analítico financeiro consumindo API do Yahoo Finance, rodando simulações de **Monte Carlo (Markowitz)**, cálculo de **VaR/CVaR**, **Risk Parity** e stress testing de crises com dashboard interativo em Streamlit/Plotly. | [🔗 Ver Projeto](https://github.com/CesarLana/FinPortfolio) |
| **Automação de Snapshots EBS & Retenção com Python** | Rotina automatizada de backup de volumes alocados via cronjob e script em Python (`boto3`) que audita a conta e expurga snapshots órfãos automaticamente, mantendo política de retenção dos últimos 2 backups. | `Python`, `Boto3`, `Linux Cron` |
| **Provisionamento em Massa no IAM via Shell Script** | Script Bash com tratamento Unix (`dos2unix`) para processamento de arquivos CSV, criação automatizada de usuários no IAM, senhas temporárias com troca obrigatória e alocação de grupos de menor privilégio. | `Bash`, `AWS CLI`, `IAM Security` |

---

### 🔍 Casos Práticos de Troubleshooting & Diagnóstico

<details>
<summary><strong>Clique para expandir exemplos de incidentes resolvidos na prática</strong></summary>

<br>

1. **Diagnóstico de Conexão Recusada no Apache HTTPD:**
   * *Sintoma:* Servidor web provisionado não respondia requisições HTTP na porta 80.
   * *Investigação:* Conexão interna via terminal, inspeção com `systemctl status httpd` e análise de `cloud-init-output.log`.
   * *Solução:* Identificado serviço parado após script de User Data; inicialização e habilitação do serviço no boot (`systemctl enable --now httpd`).

2. **Bloqueio de Tráfego por Security Groups:**
   * *Sintoma:* Falha de comunicação SSH / timeout no acesso à instância.
   * *Investigação:* Inspeção detalhada de regras Inbound do Security Group da VPC e portas abertas via `nmap`.
   * *Solução:* Correção das regras de entrada e transição da administração para **AWS Systems Manager Session Manager**, eliminando a necessidade de expor a porta 22 para a internet.

3. **Incompatibilidade de AMI ID por Região na AWS CLI:**
   * *Sintoma:* Script de automação retornando erro `InvalidAMIID.NotFound`.
   * *Solução:* Ajuste da lógica do script para consultar dinamicamente a AMI mais recente da região ativa via **AWS SSM Parameter Store** (`aws ssm get-parameters`), tornando os scripts portáveis para qualquer região AWS.

</details>

---

### 🎓 Formação & Certificações

* 🎓 **Análise e Desenvolvimento de Sistemas** — *FMU \| FIAM-FAAM* (4º Semestre)
* ☁️ **Formação AWS re/Start** — *Escola da Nuvem* (Computação em Nuvem, Redes, Segurança, Linux e Banco de Dados)
* 📊 **X Escola Avançada em Big Data Analysis** — *Universidade de São Paulo (ICMC - USP)*
* 🎯 **Preparação Ativa:** *AWS Certified Cloud Practitioner (CLF-C02)*

---

### 📊 Métricas & Atividade no GitHub

<div align="center">
  <table border="0">
    <tr>
      <td>
        <img src="https://github-readme-stats.vercel.app/api?username=CesarLana&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Estatísticas do GitHub" />
      </td>
      <td>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CesarLana&layout=compact&theme=tokyonight&hide_border=true" alt="Top Linguagens" />
      </td>
    </tr>
  </table>
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,23,43&height=100&section=footer" width="100%" alt="Footer Banner" />

  <p>Vamos conversar sobre projetos de Cloud, DevOps e Infraestrutura? Conecte-se comigo no <a href="https://www.linkedin.com/in/cesarlana/">LinkedIn</a>!</p>
</div>
