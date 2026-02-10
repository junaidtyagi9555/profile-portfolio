## 🏗️ **DevOps Technical Stack**

<div align="center">

### **Cloud Platforms**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

### **Infrastructure as Code**
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![AWS CDK](https://img.shields.io/badge/AWS_CDK-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

### **Containerization & Orchestration**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)

### **CI/CD & Automation**
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)

</div>

**End-to-end CI/CD pipeline with security scanning, testing, and canary deployments.**
- **Challenge**: Manual deployments were error-prone and lacked consistent quality gates.
- **Solution**: Built a Jenkins-as-Code pipeline with Dockerized agents, integrating SonarQube, Trivy security scanning, and automated testing.
- **Features**: Infrastructure testing with Terratest, canary deployments with Flagger, and automated rollback on failure.
- **Result**: Reduced deployment failures by 92% and enabled multiple daily releases with zero downtime.
- **Tech**: `Jenkins` `Docker` `Node.js` `Trivy` `Terratest` `Flagger`

### **📊 [Cloud Monitoring Dashboard](https://github.com/junaidtyagi9555/cloud-monitoring)**
**Centralized monitoring stack for cloud-native applications with custom alerts.**
- **Challenge**: Lack of visibility into application performance and infrastructure health across services.
- **Solution**: Deployed Prometheus stack with Thanos for long-term metrics, Grafana for dashboards, and Loki for logs.
- **Implementation**: Custom exporters for application metrics, CloudWatch integration, and PagerDuty alert routing.
- **Result**: Reduced MTTR by 65% with proactive alerting and achieved single-pane-of-glass observability.
- **Tech**: `Prometheus` `Grafana` `Loki` `Thanos` `AWS CloudWatch` `AlertManager`

### **🛡️ [Secure AWS Landing Zone](https://github.com/junaidtyagi9555/aws-landing-zone)**
**Compliant AWS multi-account structure with security guardrails and automation.**
- **Challenge**: Needed secure, isolated environments for development, staging, and production.
- **Solution**: Implemented AWS Control Tower with customizations, Service Control Policies (SCPs), and AWS Config rules for compliance.
- **Features**: Automated account vending, cross-account IAM roles, VPC peering, and centralized logging.
- **Result**: Achieved SOC 2 compliant infrastructure with automated security checks and cost optimization.
- **Tech**: `AWS Control Tower` `AWS Organizations` `AWS Config` `CloudTrail` `Lambda` `Step Functions`

### **📦 [Container Registry & Security](https://github.com/junaidtyagi9555/Docker-Projects)**
**Private container registry with vulnerability scanning and image signing.**
- **Challenge**: Ensuring container security and compliance in the software supply chain.
- **Solution**: Set up Harbor registry with Clair vulnerability scanning, Notary for signing, and retention policies.
- **Integration**: Automated scanning in CI/CD, blocking vulnerable images, and generating SBOMs.
- **Result**: Eliminated high/critical vulnerabilities in production containers and established trusted image provenance.
- **Tech**: `Harbor` `Clair` `Notary` `Cosign` `Trivy` `SPDX`

---

## 📈 **Certifications & Learning Path**

<div align="center">

| **Completed** | **In Progress** | **Planned** |
| :--- | :--- | :--- |
| ![AWS Cloud Practitioner](https://img.shields.io/badge/AWS_Cloud_Practitioner-FF9900?style=flat-square&logo=amazonaws&logoColor=white) | ![AWS Solutions Architect](https://img.shields.io/badge/AWS_SA_Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white) | ![CKA](https://img.shields.io/badge/Certified_K8s_Admin-326CE5?style=flat-square&logo=kubernetes&logoColor=white) |
| ![Terraform Associate](https://img.shields.io/badge/Terraform_Associate-7B42BC?style=flat-square&logo=terraform&logoColor=white) | ![AWS DevOps Pro](https://img.shields.io/badge/AWS_DevOps_Pro-FF9900?style=flat-square&logo=amazonaws&logoColor=white) | ![Google Cloud Engineer](https://img.shields.io/badge/Google_Cloud_ACE-4285F4?style=flat-square&logo=googlecloud&logoColor=white) |

</div>

**Current Focus Areas:**
- Service Mesh (Istio/Linkerd) implementation patterns
- FinOps and cloud cost optimization strategies
- Platform Engineering and Internal Developer Platforms
- Chaos Engineering with LitmusChaos

---
## 🤝 **Looking For Opportunities**

I'm actively seeking roles as:
- **DevOps Engineer**
- **Site Reliability Engineer (SRE)**
- **Cloud Infrastructure Engineer**
- **Platform Engineer**

**Open to**: Full-time positions, Contract work, Open-source collaboration

<div align="center">

[![LinkedIn Connect](https://img.shields.io/badge/Let's_Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&width=200)](https://www.linkedin.com/in/junaid-tyagi-8379b5225)
[![Schedule Chat](https://img.shields.io/badge/Schedule_a_Chat-4285F4?style=for-the-badge&logo=googlemeet&logoColor=white&width=200)](https://cal.com/junaidtyagi)
[![Email Me](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&width=200)](mailto:junaidtyagi9555@gmail.com)

</div>

---

<div align="center">

### 🎯 **"Infrastructure as Code isn't just about automation; it's about reproducibility, reliability, and velocity."**

⭐ **Thanks for visiting!** Explore my infrastructure projects and let's discuss cloud-native solutions.

![Visitor Count](https://komarev.com/ghpvc/?username=junaidtyagi9555&color=00D4AA&style=flat-square&label=INFRASTRUCTURE+VIEWS)

</div>

---

## 🧪 **Lab Environment & Experiments**

```yaml
home_lab:
  kubernetes_clusters:
    - name: homelab-k3s
      nodes: 3
      purpose: "Learning Service Mesh"
      tools: ["Istio", "Kiali", "Jaeger"]
    - name: minikube-dev
      nodes: 1
      purpose: "Local Development"
      tools: ["Skaffold", "Tilt", "Telepresence"]
    
  infrastructure:
    - proxmox_ve: "Virtualization Host"
    - terraform_cloud: "Remote State & CI"
    - vault: "Secrets Management"
    
  monitoring_stack:
    - prometheus: "Metrics Collection"
    - loki: "Log Aggregation"
    - tempo: "Distributed Tracing"

    
