<br>

<h1 align="center">K I S H A N &nbsp; M I S K I N</h1>

<p align="center">
  <sub>C L O U D &nbsp;·&nbsp; D E V O P S &nbsp;·&nbsp; I N F R A S T R U C T U R E</sub>
</p>

<br>

<h3 align="center"><em>Build it. Break it. Fix it. Understand it.</em></h3>

<br>

<p align="center">
  <a href="https://linkedin.com/in/kishanmiskin">LinkedIn</a>
  &nbsp;&nbsp;/&nbsp;&nbsp;
  <a href="https://github.com/Kishan-Miskin">GitHub</a>
</p>

<br>

---

<br>

<h6 align="center">I &nbsp;·&nbsp; A B O U T</h6>

<br>

<p align="center">
  Cloud Computing Intern at <b>Rooman Technologies</b>.<br>
  Final-year BE student. Belgaum, India.
</p>

<p align="center">
  I build real AWS infrastructure and delivery pipelines,<br>
  then intentionally break them to learn how they fail.
</p>

<p align="center">
  <sub>Open to work &nbsp;·&nbsp; Immediately available &nbsp;·&nbsp; Remote or relocation</sub>
</p>

<br>

---

<br>

<h6 align="center">II &nbsp;·&nbsp; C R A F T</h6>

<br>

<table align="center">
  <tr>
    <td align="right"><sub>CLOUD</sub></td>
    <td>EC2 &nbsp;·&nbsp; S3 &nbsp;·&nbsp; VPC &nbsp;·&nbsp; IAM &nbsp;·&nbsp; RDS &nbsp;·&nbsp; CloudFront &nbsp;·&nbsp; ALB &nbsp;·&nbsp; Route 53</td>
  </tr>
  <tr>
    <td align="right"><sub>DEVOPS</sub></td>
    <td>GitHub Actions &nbsp;·&nbsp; Docker &nbsp;·&nbsp; Compose &nbsp;·&nbsp; Bash &nbsp;·&nbsp; PM2</td>
  </tr>
  <tr>
    <td align="right"><sub>NETWORK</sub></td>
    <td>Custom VPCs &nbsp;·&nbsp; Subnets &nbsp;·&nbsp; Security Groups &nbsp;·&nbsp; NAT &nbsp;·&nbsp; Bastion</td>
  </tr>
  <tr>
    <td align="right"><sub>IaC</sub></td>
    <td>Terraform <em>(learning)</em></td>
  </tr>
  <tr>
    <td align="right"><sub>TOOLS</sub></td>
    <td>Linux &nbsp;·&nbsp; Git &nbsp;·&nbsp; Nginx &nbsp;·&nbsp; Node.js &nbsp;·&nbsp; SSH</td>
  </tr>
</table>

<br>

---

<br>

<h6 align="center">III &nbsp;·&nbsp; S E L E C T E D &nbsp; W O R K</h6>

<br>

### CloudDrive

*A private, three-tier file storage platform on AWS.*

Files go to a private S3 bucket, metadata to a private RDS database, and every request passes through CloudFront and an ALB before reaching an EC2 instance in a private subnet. No backend resource is exposed to the internet.

```
Internet → CloudFront → ALB → EC2 (private) → RDS · S3
```

Least-privilege security groups &nbsp;·&nbsp; IAM role, no hardcoded credentials &nbsp;·&nbsp; S3 VPC endpoint &nbsp;·&nbsp; Pre-signed URLs

<sub>`VPC` `EC2` `S3` `CloudFront` `RDS` `ALB` `IAM` `Node.js` `PM2`</sub>

<br>

### AWS 2-Tier Break/Fix Lab

*Infrastructure built to be broken, then debugged.*

An ALB fronts two private EC2 servers across two availability zones, backed by a private RDS database, with a bastion host and NAT gateway. I introduced failures on purpose and traced each one to its cause.

**Stopped nginx on one server.** The ALB marked it unhealthy within 30 seconds and rerouted all traffic with no user impact.

**Wrong route table on a private subnet.** Instances lost outbound internet because the NAT route was missing. A subnet-to-route-table mismatch fails silently.

<sub>`VPC` `ALB` `EC2` `RDS` `Bastion` `NAT Gateway` `Multi-AZ`</sub>

<br>

### CloudNest

*Self-hosted file storage in three containers.*

Nginx as reverse proxy, Flask for application logic, and a named Docker volume for persistence. One command to deploy, no cloud account needed.

```
Browser → Nginx → Flask → Volume
```

<sub>`Docker` `Compose` `Flask` `Nginx` `Python`</sub>

<br>

### Terraform EC2

*A complete web server from a single `terraform apply`.*

Key pair, security group, and instance defined in code. A `user_data` script configures Nginx on first boot. The stack can be destroyed and recreated without touching the console.

<sub>`Terraform` `EC2` `Bash` &nbsp;·&nbsp; [Repository →](https://github.com/Kishan-Miskin/Terraform-EC2)</sub>

<br>

### CI/CD Pipeline

*Push to main, live in about 45 seconds.*

A GitHub Actions workflow installs, tests, and deploys to Vercel on every push. Secrets stay in GitHub, never in code.

```
push → checkout → install → test → deploy
```

<sub>`GitHub Actions` `Vercel` `YAML` &nbsp;·&nbsp; [Repository →](https://github.com/Kishan-Miskin/cicd)</sub>

<br>

---

<br>

<h6 align="center">IV &nbsp;·&nbsp; N O W</h6>

<br>

<p align="center">
  Terraform across full multi-tier VPC stacks<br>
  Containerising existing cloud projects<br>
  CloudWatch monitoring and alerting<br>
  Cost optimisation: tagging, billing alerts, right-sizing<br>
  AWS Cloud Practitioner
</p>

<br>

---

<br>

<h6 align="center">V &nbsp;·&nbsp; C O N T A C T</h6>

<br>

<p align="center">
  Looking for roles in<br>
  <b>Junior Cloud Engineering</b> &nbsp;·&nbsp; <b>Cloud Support</b> &nbsp;·&nbsp; <b>DevOps</b>
</p>

<p align="center">
  <a href="https://linkedin.com/in/kishanmiskin">linkedin.com/in/kishanmiskin</a><br>
  <a href="https://github.com/Kishan-Miskin">github.com/Kishan-Miskin</a>
</p>

<br>

<p align="center">
  <sub><em>The best way to learn cloud is to break things in it.</em></sub>
</p>

<br>
