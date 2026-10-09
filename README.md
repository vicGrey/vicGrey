<h1 align="center">Victor Okoroafor</h1>

<p align="center">
  <img src="https://img.shields.io/badge/AWS%20Certified-Solutions%20Architect%20Associate-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" />
</p>

<p align="center">
  <b>AWS Certified Solutions Architect · Cloud Security & DevSecOps</b><br/>
  I build cloud infrastructure and CI/CD pipelines where security is enforced in code, not written in a policy document.
</p>

<p align="center">
  <a href="https://linkedin.com/in/victor-okoroafor-cloud"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://victorokoroafor.hashnode.dev"><img src="https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white" /></a>
  <a href="https://dev.to/okoroaforvic"><img src="https://img.shields.io/badge/DEV.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white" /></a>
  <a href="mailto:victor.okoroafor.cloud@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/vicGrey"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

---

### 👨‍💻 About Me

AWS-certified cybersecurity graduate. Most of what I know comes from building systems and breaking them.

- 📝 **Writing at**: [victorokoroafor.hashnode.dev](https://victorokoroafor.hashnode.dev) & [dev.to/okoroaforvic](https://dev.to/okoroaforvic)
- 🛠️ **Core Tools**: AWS (Lambda, API Gateway, IAM, DynamoDB, Cognito, Config), Terraform, Open Policy Agent (Rego), Docker, Kubernetes, GitHub Actions, Linux, Python, Bash.
- 🌱 **Learning**: Advanced cloud security controls, threat detection, and runtime security.
- 🎯 **Looking for**: Junior Cloud, Cloud Security, or DevSecOps roles.

---

### 🚀 Key Projects

#### 🛡️ [aws-serverless-zero-trust-governance](https://github.com/vicGrey/aws-serverless-zero-trust-governance)
Three-layer Zero Trust governance for a serverless financial API. Terraform defines the infrastructure, GitHub Actions runs the pipeline, and OPA with Conftest evaluates every plan before it reaches AWS. Unauthenticated API endpoints, over-privileged IAM roles, and publicly exposed S3 buckets are blocked at the pull request. AWS Config catches configuration drift after deployment.  
*Tested against four misconfiguration scenarios: 100% enforcement rate, 7.3 seconds added to the pipeline.*  
📖 **[Read write-up →](https://victorokoroafor.hashnode.dev/how-to-block-over-privileged-iam-roles-in-aws-using-policy-as-code)**

#### 🐳 [fastapi-demo](https://github.com/vicGrey/fastapi-demo)
FastAPI service where data validation runs inside the Docker build. A malformed `data.json` fails `docker build` itself, so an engineer working locally without the pipeline still can't produce a bad image. Multi-stage build keeps build tools out of the final layer.

#### 🤖 [AI-image-recognition](https://github.com/vicGrey/AI-image-recognition)
Serverless image recognition web application built with Amazon Rekognition, AWS Lambda, and CloudFront.

---

### 📚 Writing

*I write about cloud security and the edge cases I hit building it. Open to technical writing, guest posts, and security write-ups.*

- 📝 **How to Block Over-Privileged IAM Roles in AWS Using Policy-as-Code**  
  *A breakdown of Rego array iteration, exit codes, and pipeline blocking in GitHub Actions.*  
  Read on: [Hashnode](https://victorokoroafor.hashnode.dev/how-to-block-over-privileged-iam-roles-in-aws-using-policy-as-code) • [DEV.to](https://dev.to/okoroaforvic/how-to-block-over-privileged-iam-roles-in-aws-using-policy-as-code-1k8)

---

### 🧰 Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Open_Policy_Agent-7D9199?style=for-the-badge&logo=openpolicyagent&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>
