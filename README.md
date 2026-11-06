<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:0a3d62,100:FF9900&height=200&section=header&text=Cesar%20Lana&fontSize=56&fontColor=ffffff&fontAlignY=38&desc=Cloud%20%7C%20DevOps%20%7C%20Infrastructure&descAlignY=58&descSize=20&descFontColor=FF9900" width="100%" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=FF9900&center=true&vCenter=true&random=false&width=600&lines=Automating+infrastructure+with+Python+%26+Bash;Building+resilient+architectures+on+AWS;Learning+IaC+with+Terraform;Always+shipping+%F0%9F%9A%80" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/cesarlana/"><img src="https://img.shields.io/badge/LinkedIn-cesarlana-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>&nbsp;
  <a href="https://github.com/CesarLana"><img src="https://img.shields.io/badge/GitHub-CesarLana-181717?style=flat-square&logo=github&logoColor=white"/></a>
</p>

<br/>

---

## Olá, eu sou o Cesar 👋

Atuei como **Analista de Infraestrutura Jr na DXC Technology** no **Projeto Itaú** — ambiente crítico do setor bancário com suporte técnico, gerenciamento de incidentes e administração de acessos com **Microsoft 365**, **Azure AD** e **ServiceNow**.

Nos meus projetos, containerizo aplicações com Docker e publico no Amazon ECR, automatizo backups de EBS com Python/Boto3, provisiono usuários IAM via Bash e pratico arquiteturas de alta disponibilidade na AWS.

Busco uma posição em **Cloud Computing, DevOps ou Dados** — aplicando o que aprendo na prática.

---

## 🛠 Stack

<p>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Windows-0078D4?style=for-the-badge&logo=windows&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure_AD-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Microsoft_365-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white"/>
  <img src="https://img.shields.io/badge/ServiceNow-62D84E?style=for-the-badge&logo=servicenow&logoColor=white"/>
</p>
<p>
  <img src="https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/Active_Directory-0078D4?style=for-the-badge&logo=microsoft&logoColor=white"/>
</p>

> 📌 Terraform e CI/CD em aprendizado ativo — próximos projetos já planejados.

**AWS:** `EC2` `ECR` `S3` `RDS` `VPC` `Route 53` `ALB` `Auto Scaling` `IAM` `CloudWatch` `SSM` `SNS`

---

## 🚀 Projetos

### Deploy de Aplicação Web com Docker & AWS ECR
> Containerização com **Nginx Alpine** (~25MB), orquestração local com Docker Compose e push autenticado para o Amazon ECR.

[![Ver Repositório](https://img.shields.io/badge/Ver%20Repositório-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CesarLana/projeto-devops-aws-docker)
&nbsp;`Docker` `Nginx` `AWS ECR` `EC2`

---

### FinPortfolio — Análise de Portfólio com Python
> Dashboard com dados de mercado via yfinance (cotações com delay), simulações de Monte Carlo para geração de carteiras, VaR histórico e visualização em Streamlit.

[![Ver Repositório](https://img.shields.io/badge/Ver%20Repositório-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CesarLana/FinPortfolio)
&nbsp;`Python` `Docker` `Streamlit` `Monte Carlo`

---

### Labs AWS — Escola da Nuvem (AWS re/Start)

Exercícios práticos do programa de formação. Seguei os roteiros e documentei as decisões de arquitetura que tomei além do guiado.

| Lab | O que foi feito |
|---|---|
| **ALB + Auto Scaling (Multi-AZ)** | ALB com Target Group, ASG via Launch Template de AMI customizada, política de escalonamento por CPU target 50% |
| **Route 53 Failover** | Health Checks HTTP a cada 10s, chaveamento ativo/standby entre AZs, alerta via SNS |
| **Right-Sizing de Instância** | Análise de utilização no CloudWatch → downsizing `t3.small → t3.micro` + redução de volume EBS |
| **SSM Session Manager** | Acesso remoto a EC2 sem inbound SSH (porta 22 fechada), Run Command em lote |
| **Migração para RDS** | Export com `mysqldump`, import em Amazon RDS Multi-AZ com credenciais no Parameter Store |
| **Backup EBS com Python** | Script Boto3 + cronjob: cria snapshot, lista existentes e remove os mais antigos mantendo os 2 últimos |
| **Provisionamento IAM em Massa** | Script Bash lê CSV, cria usuários com senha temporária e flag `--password-reset-required` |

---

## 🎓 Formação

| | |
|---|---|
| **Análise e Desenvolvimento de Sistemas** | FMU \| FIAM-FAAM — em curso |
| **AWS re/Start** | Escola da Nuvem |
| **X Escola Avançada em Big Data Analysis** | ICMC - USP |
| **AWS Certified Cloud Practitioner** | Em preparação (CLF-C02) |

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF9900,50:0a3d62,100:0d1117&height=120&section=footer" width="100%"/>

<p align="center">
  <i>Vamos conversar?</i><br/><br/>
  <a href="https://www.linkedin.com/in/cesarlana/"><b>LinkedIn</b></a>
</p>
