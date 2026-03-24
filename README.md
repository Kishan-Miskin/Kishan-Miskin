<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║        ██╗  ██╗██╗███████╗██╗  ██╗ █████╗ ███╗   ██╗           ║
║        ██║ ██╔╝██║██╔════╝██║  ██║██╔══██╗████╗  ██║           ║
║        █████╔╝ ██║███████╗███████║███████║██╔██╗ ██║           ║
║        ██╔═██╗ ██║╚════██║██╔══██║██╔══██║██║╚██╗██║           ║
║        ██║  ██╗██║███████║██║  ██║██║  ██║██║ ╚████║           ║
║        ╚═╝  ╚═╝╚═╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝           ║
║                                                                  ║
║               M  I  S  K  I  N                                   ║
╚══════════════════════════════════════════════════════════════════╝
```

</div>

```bash
$ whoami
```
> **kishan_miskin** — Cloud Computing Intern · AWS Architect · DevOps Builder

```bash
$ cat /etc/profile.d/kishan.conf
```

```ini
NAME        = "Kishan Miskin"
ROLE        = "Cloud Computing Intern @ Rooman Technologies"
LOCATION    = "Belgaum, India 🇮🇳"
DEGREE      = "BE — Final Year (Graduating mid-2026)"
LEARNING    = "Terraform (IaC)"
SEEKING     = "Junior Cloud Engineer / Cloud Support / DevOps Trainee"
PHILOSOPHY  = "Build it. Break it. Fix it. Understand it."
STATUS      = "🟢 Open to Work"
```

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/──%20LinkedIn%20──-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kishanmiskin)
[![GitHub](https://img.shields.io/badge/──%20GitHub%20──-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kishan-Miskin)
![Open to Work](https://img.shields.io/badge/🟢%20Open%20to%20Work-Junior%20Cloud%20Engineer-1D9E75?style=for-the-badge)

</div>

---

## `$ cat about_me.txt`

```
┌─────────────────────────────────────────────────────────────────┐
│                        ABOUT ME                                  │
├─────────────────────────────────────────────────────────────────┤
│                                                                  │
│  I'm a final-year BE student and Cloud Computing Intern at       │
│  Rooman Technologies — building real AWS infrastructure and      │
│  DevOps pipelines from the ground up.                            │
│                                                                  │
│  I don't just follow tutorials.                                  │
│  I build, break, and fix things until I understand how           │
│  they actually work.                                             │
│                                                                  │
│  From custom VPCs to GitHub Actions CI/CD — I focus on          │
│  real-world cloud skills that translate directly to the job.     │
│                                                                  │
└─────────────────────────────────────────────────────────────────┘
```

---

## `$ dpkg --list | grep tech-stack`

### ☁️ Cloud

```
aws-core          [INSTALLED]  ██████████  EC2 · S3 · VPC · IAM · EBS · CloudFront
aws-networking    [INSTALLED]  ████████░░  Route 53 · ACM · Security Groups
aws-storage       [INSTALLED]  █████████░  S3 versioning · Bucket policies · ACLs
```

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-DD344C?style=flat-square&logo=amazonaws&logoColor=white)
![EBS](https://img.shields.io/badge/EBS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

### ⚙️ DevOps & Automation

```
linux             [INSTALLED]  ██████████  Bash scripting · SSH · server admin
github-actions    [INSTALLED]  █████████░  CI/CD pipelines · YAML workflows
docker            [INSTALLED]  ████████░░  Containerisation · image management
terraform         [LEARNING]   ██████░░░░  IaC · EC2 provisioning · .tf configs
```

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-learning-7B42BC?style=flat-square&logo=terraform&logoColor=white)

### 🔧 Networking & Tools

```
nginx             [INSTALLED]  ████████░░  Reverse proxy · web server config
git               [INSTALLED]  ██████████  Version control · branching strategy
ssh               [INSTALLED]  ██████████  Key-based auth · secure tunnels
vscode            [INSTALLED]  █████████░  Extensions · remote dev · SSH plugin
```

![SSH](https://img.shields.io/badge/SSH-000000?style=flat-square&logo=openssh&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

---

## `$ ls -la ~/projects/`

### ☁️ `expense-tracker/` — AWS Static Hosting

```bash
$ terraform show expense-tracker
```

```
Resource: aws_s3_bucket.expense_tracker
  ├── static_website_hosting  = enabled
  ├── versioning              = enabled
  └── bucket_policy           = restrict_direct_access ✓

Resource: aws_cloudfront_distribution.cdn
  ├── origin                  = s3_bucket
  ├── https_only              = true
  └── certificate             = ACM (us-east-1) ✓

# Direct S3 access blocked — CloudFront is the only entry point.
```

`AWS S3` `CloudFront` `ACM` `IAM` `Route 53`

---

### 🗄️ `cloud-drive/` — File Storage Platform

```bash
$ aws s3 ls s3://clouddrive-bucket --human-readable
```

```
Architecture:
  ├── EC2 (app layer)
  ├── S3 (storage backend)
  ├── IAM roles with least-privilege access control
  └── Linux server administration
```

`AWS S3` `IAM` `EC2` `Linux`

---

### ⚙️ `terraform-ec2/` — Infrastructure as Code

```bash
$ terraform apply
```

```
Plan: 3 to add, 0 to change, 0 to destroy.
  + aws_instance.web_server
  + aws_security_group.allow_ssh_http
  + aws_key_pair.deployer

Apply complete! Resources: 3 added. Time: 47s ✓

# User-data script automates server setup on launch.
# Destroy and recreate infrastructure in under 60 seconds.
```

`Terraform` `AWS EC2` `Bash` `IaC` · [View repo →](https://github.com/Kishan-Miskin/Terraform-EC2)

---

### 🔄 `cicd-pipeline/` — GitHub Actions

```yaml
# .github/workflows/deploy.yml
name: Deploy to Production
on:
  push:
    branches: [main]       # ← triggers on every push

jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Deploy to Vercel
        run: vercel --prod    # ← zero manual steps ✓
```

`GitHub Actions` `CI/CD` `Vercel` `YAML` · [View repo →](https://github.com/Kishan-Miskin/cicd)

---

## `$ crontab -l   # current tasks`

```
# ┌─────── What I'm building right now
# │
# *  Deepening Terraform — writing IaC for complex AWS architectures
# *  Containerising existing projects with Docker
# *  Preparing for AWS Cloud Practitioner certification
# *  Adding CloudWatch monitoring to projects
```

---

## `$ git log --oneline --graph`

<div align="center">

![Kishan's GitHub stats](https://github-readme-stats.vercel.app/api?username=Kishan-Miskin&show_icons=true&theme=github_dark&hide_border=true&count_private=true&title_color=58a6ff&icon_color=f0883e&text_color=c9d1d9&bg_color=0d1117)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Kishan-Miskin&layout=compact&theme=github_dark&hide_border=true&title_color=58a6ff&text_color=c9d1d9&bg_color=0d1117)

</div>

---

## `$ ssh kishan@connect --hire-me`

```
Connecting to kishan_miskin...
Roles matched:
  ✓  Junior Cloud Engineer
  ✓  Cloud Support Engineer
  ✓  DevOps Trainee

If you're hiring or want to connect:
```

> 📎 [LinkedIn — linkedin.com/in/kishanmiskin](https://linkedin.com/in/kishanmiskin)
> 💻 [GitHub — github.com/Kishan-Miskin](https://github.com/Kishan-Miskin)

---

<div align="center">

```
╔══════════════════════════════════════════════════════╗
║  "The best way to learn cloud is to break things     ║
║   in it."                                            ║
╚══════════════════════════════════════════════════════╝
```

![Visitor Count](https://komarev.com/ghpvc/?username=Kishan-Miskin&color=58a6ff&style=flat-square&label=profile+views)

</div>
