# Hi there, I'm Trey Petgrave 👋

### 🚀 About Me
I am a Cloud Security Engineering fellow at The Knowledge House and a creative producer based in New York. I specialize in building secure cloud infrastructure, automating DevSecOps pipelines, and engineering robust cloud solutions using modern Infrastructure-as-Code (IaC) workflows.

* 🎯 **Target Roles:** Cloud Security Engineer | DevSecOps Engineer | Technical Product Developer
* 📍 **Location:** Queens, New York
* 💼 **Connect with me:** [LinkedIn Profile](https://www.linkedin.com) | [Resume](https://your-resume-link.com)
 
---

### 🛠️ Technical Skills
* **Cloud & Infrastructure:** AWS (VPC, EC2, IAM, Route Tables, Internet Gateways, ECR, Lambda), Terraform
* **Security & DevSecOps:** Static Application Security Testing (SAST), `tfsec`, GitHub Actions CI/CD pipelines, container hardening, IAM least-privilege policies
* **Systems & Scripting:** Linux, Bash, Git, GitHub, Python, macOS, UTM Virtual Machines
* **Post-Production & Media Tech:** DaVinci Resolve, Adobe Premiere Pro, Avid Media Composer, Final Cut Pro

---

### 📌 Pinned Projects

* **[TKH-Final-Capstone](https://github.com/tpetgrave12-dotcom/TKH-Final-Capstone)**
  * *Cloud Security Engineering Capstone:* Provisioned an isolated AWS Virtual Private Cloud (VPC) with custom subnets, route tables, and locked-down security groups. Integrated an automated `tfsec` security scan via GitHub Actions CI/CD to enforce DevSecOps quality gates before deployment, complete with live EC2 instance verification and resource teardown compliance.

* **[TLAB 8: The Fleet Command](https://github.com/tpetgrave12-dotcom/TLAB8-Fleet)**
  * *Container Hardening & Serverless IAM Least Privilege:* Built and pushed a hardened `node:alpine` container with scan-on-push enabled to a private Amazon ECR repository. Deployed a Python AWS Lambda function ("Fleet-Auditor") and surgically rewrote its IAM execution role to enforce strict least-privilege security, restricting access exclusively to CloudWatch logging and ECR image description.

* **[TLAB 9: The Full Spectrum Breach](https://github.com/tpetgrave12-dotcom/TLAB9-Breach)**
  * *Incident Response & Threat Containment:* Executed a live-fire security incident response exercise. Queried CloudTrail flight data via Amazon Athena using SQL to hunt down a compromised IAM user and rogue EC2 instance, performed network quarantine using lockdown security groups, and paralyzed compromised credentials with explicit IAM Deny policies.
