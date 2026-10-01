<div align="center">
  <img src="https://mir-s3-cdn-cf.behance.net/project_modules/fs/bbefa799786133.5efa9bf3d1b49.gif" width="100%" height="300px" alt="Mastermind — Pixel Jeff" />
</div>

<br>

<h1 align="center">K I S H A N &nbsp; M I S K I N</h1>

<p align="center">
  <sub>C L O U D &nbsp;·&nbsp; D E V O P S &nbsp;·&nbsp; I N F R A S T R U C T U R E</sub>
</p>

<h3 align="center"><em>Build it. Break it. Fix it. Understand it.</em></h3>

<p align="center">
  <a href="https://linkedin.com/in/kishanmiskin">LinkedIn</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/Kishan-Miskin">GitHub</a>
</p>

<br>

---

<br>

<h6 align="center">I &nbsp;·&nbsp; A B O U T</h6>

<p align="center">
  <b>BE Graduated 2026</b>
</p>

<p align="center">
  I build real AWS infrastructure and delivery pipelines,<br>
  then break them on purpose to learn how they fail.
</p>

<p align="center">
  <sub>Open to work &nbsp;·&nbsp; Immediately available &nbsp;·&nbsp; Remote or relocation</sub>
</p>

<br>

---

<br>

<h6 align="center">II &nbsp;·&nbsp; C R A F T</h6>

<p align="center">
  <sub>CLOUD</sub><br>
  EC2 &nbsp;·&nbsp; S3 &nbsp;·&nbsp; VPC &nbsp;·&nbsp; IAM &nbsp;·&nbsp; RDS &nbsp;·&nbsp; CloudFront &nbsp;·&nbsp; ALB &nbsp;·&nbsp; Route 53
</p>

<p align="center">
  <sub>DEVOPS</sub><br>
  GitHub Actions &nbsp;·&nbsp; Docker &nbsp;·&nbsp; Compose &nbsp;·&nbsp; Bash &nbsp;·&nbsp; PM2
</p>

<p align="center">
  <sub>NETWORKING</sub><br>
  Custom VPCs &nbsp;·&nbsp; Subnets &nbsp;·&nbsp; Security Groups &nbsp;·&nbsp; NAT &nbsp;·&nbsp; Bastion
</p>

<p align="center">
  <sub>INFRASTRUCTURE AS CODE</sub><br>
  Terraform <em>(learning)</em>
</p>

<p align="center">
  <sub>TOOLS</sub><br>
  Linux &nbsp;·&nbsp; Git &nbsp;·&nbsp; Nginx &nbsp;·&nbsp; Node.js &nbsp;·&nbsp; SSH
</p>

<br>

---

<br>

<h6 align="center">III &nbsp;·&nbsp; S E L E C T E D &nbsp; W O R K</h6>

<br>

<h3 align="center">CloudDrive</h3>
<p align="center"><em>A private three-tier file storage platform on AWS</em></p>
<p align="center">
  Files go to a private S3 bucket and metadata to a private RDS database.<br>
  Every request passes through CloudFront and an ALB before reaching<br>
  an EC2 instance in a private subnet. No backend is exposed to the internet.
</p>
<p align="center"><code>Internet → CloudFront → ALB → EC2 → RDS · S3</code></p>
<p align="center">
  <sub>VPC &nbsp;·&nbsp; EC2 &nbsp;·&nbsp; S3 &nbsp;·&nbsp; CloudFront &nbsp;·&nbsp; RDS &nbsp;·&nbsp; ALB &nbsp;·&nbsp; IAM &nbsp;·&nbsp; Node.js &nbsp;·&nbsp; PM2</sub>
</p>

<br>

<h3 align="center">AWS 2-Tier Break/Fix Lab</h3>
<p align="center"><em>Infrastructure built to be broken, then debugged</em></p>
<p align="center">
  An ALB fronts two private EC2 servers across two availability zones,<br>
  backed by a private RDS database, with a bastion host and NAT gateway.<br>
  I introduced failures on purpose and traced each one to its cause.
</p>
<p align="center">
  <b>Stopped nginx on one server.</b><br>
  The ALB marked it unhealthy within 30 seconds and rerouted all traffic.
</p>
<p align="center">
  <b>Wrong route table on a private subnet.</b><br>
  Outbound internet vanished because the NAT route was missing.
</p>
<p align="center">
  <sub>VPC &nbsp;·&nbsp; ALB &nbsp;·&nbsp; EC2 &nbsp;·&nbsp; RDS &nbsp;·&nbsp; Bastion &nbsp;·&nbsp; NAT Gateway &nbsp;·&nbsp; Multi-AZ</sub>
</p>

<br>

<h3 align="center">CloudNest</h3>
<p align="center"><em>Self-hosted file storage in three containers</em></p>
<p align="center">
  Nginx as reverse proxy, Flask for application logic,<br>
  and a named Docker volume for persistence.<br>
  One command to deploy, no cloud account needed.
</p>
<p align="center"><code>Browser → Nginx → Flask → Volume</code></p>
<p align="center">
  <sub>Docker &nbsp;·&nbsp; Compose &nbsp;·&nbsp; Flask &nbsp;·&nbsp; Nginx &nbsp;·&nbsp; Python</sub>
</p>

<br>

<h3 align="center">Terraform EC2</h3>
<p align="center"><em>A complete web server from a single <code>terraform apply</code></em></p>
<p align="center">
  Key pair, security group, and instance defined in code.<br>
  A user-data script configures Nginx on first boot.<br>
  Destroy and recreate the stack without touching the console.
</p>
<p align="center">
  <sub>Terraform &nbsp;·&nbsp; EC2 &nbsp;·&nbsp; Bash &nbsp;·&nbsp; <a href="https://github.com/Kishan-Miskin/Terraform-EC2">Repository →</a></sub>
</p>

<br>

<h3 align="center">CI/CD Pipeline</h3>
<p align="center"><em>Push to main, live in about 45 seconds</em></p>
<p align="center">
  A GitHub Actions workflow installs, tests, and deploys to Vercel<br>
  on every push. Secrets stay in GitHub, never in code.
</p>
<p align="center"><code>push → checkout → install → test → deploy</code></p>
<p align="center">
  <sub>GitHub Actions &nbsp;·&nbsp; Vercel &nbsp;·&nbsp; YAML &nbsp;·&nbsp; <a href="https://github.com/Kishan-Miskin/cicd">Repository →</a></sub>
</p>

<br>

---

<br>

<h6 align="center">IV &nbsp;·&nbsp; N O W</h6>

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
