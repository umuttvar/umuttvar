# Hi, I'm Umut 👋

Aspiring **DevOps engineer** who learns by building. I take a platform from bare metal to a running app, and every step is written as code: infrastructure, configuration and deployments.

🔍 **Open to junior DevOps / Cloud / Platform engineering roles.**

---

## 🛠️ Tools I've used in my projects

**Infrastructure as Code & config**
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)

**Containers & orchestration**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat&logo=traefikproxy&logoColor=white)
![MetalLB](https://img.shields.io/badge/MetalLB-4A4A4A?style=flat)

**CI/CD & GitOps**
![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=flat&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Cloud & virtualization**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat&logo=proxmox&logoColor=white)

**OS & languages**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat)

---

## 🚀 Projects

| Project | What it is | Stack |
|---|---|---|
| 🏠 **[homelab](https://github.com/umuttvar/homelab)** · 🚧 in progress | A Kubernetes platform on my own Proxmox server, rebuilt from scratch **fully as code**: Terraform creates the VMs, Ansible builds a kubeadm cluster, Terraform bootstraps Argo CD, and Argo CD deploys everything else from Git (App of Apps). | Proxmox · Terraform · Ansible · kubeadm · Argo CD · MetalLB · Traefik · Jenkins |
| ☁️ **[aws-platform](https://github.com/umuttvar/aws-platform)** · 🚧 in progress | My homelab platform rebuilt on AWS **without long-lived credentials**: GitHub Actions → OIDC → ECR, an app behind an ALB, then EKS + Argo CD with the AWS Load Balancer Controller. | AWS · Terraform · EKS · ECR · ALB · OIDC · Argo CD |
| 🧪 **[homelab-k8s](https://github.com/umuttvar/homelab-k8s)** | My first homelab Kubernetes cluster. This is where I learned the basics, and I documented every incident I hit. | Kubernetes · Argo CD · Docker |
| 🐍 **[demo-app](https://github.com/umuttvar/demo-app)** | A small FastAPI app that I deploy on all of my platforms, with a CI pipeline that builds and pushes the image. | Docker · GitHub Actions |

---

## 📌 How I work

- **Everything as code:** if I can't rebuild it with `terraform apply` and `git push`, it isn't finished.
- **No secrets in Git:** I use OIDC and SSO instead of access keys, and keep tokens out of the repo.
- **Read before apply:** I review every `plan` and diff before changing anything.
- **Write it down:** each README has a "problems I hit" table with the symptom, root cause and fix.

## 🌱 Currently learning

Jenkins pipelines · Python · Kubernetes storage and networking

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/umut-var-24545022a/)
