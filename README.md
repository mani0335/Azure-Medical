---> Highly Available Medical Web Application (Deployed on Azure)

This project is a high-availability medical web application deployed on Microsoft Azure with a focus on scalability, reliability, performance, and traffic management.
The application helps users access medical services without downtime, even during heavy traffic or high user load.

✅ Project Overview
I deployed my medical web application on Azure Virtual Machines and configured a complete cloud infrastructure that ensures smooth performance when multiple users access the system simultaneously.

To avoid server overload and traffic issues, I implemented Virtual Machine Scale Sets (VMSS) along with an Azure Load Balancer.
This setup automatically creates multiple VM instances and distributes incoming user requests evenly.
If traffic increases → new VM instances are automatically created.
If traffic decreases → extra VM instances are removed to save cost.

Additionally, I configured:
Networking rules
Security group access
Application monitoring
Performance insights
All deployments and code updates were automated using GitHub Actions (CI/CD Pipeline) to push latest changes from GitHub to the Virtual Machines.

🏗️ Architecture Workflow

Application code was pushed to GitHub Repository.
A Virtual Machine was created in Azure to host the web app.
The project code was cloned from GitHub into the VM and deployed.
Networking, firewall ports, and NSG rules were configured for secure public access.
A Virtual Machine Scale Set (VMSS) was created using the VM image.
Azure Load Balancer was placed in front to distribute user traffic across multiple VM instances.
Auto-scaling rules were configured to handle traffic surges.
Application performance and logs were monitored using:
Azure Monitor
Application Insights

🌐 Key Benefits
Feature	Description
High Availability	App remains online & accessible 24/7
Auto Scaling	VMs automatically scale based on user load
Traffic Management	Load Balancer distributes requests efficiently
Continuous Deployment	GitHub Actions pushes updates with no downtime
Monitoring & Alerts	Application health is tracked in real time
🛠️ Technologies & Tools Used
Category	Tools
Cloud Platform	Microsoft Azure
Compute	Azure Virtual Machines / VM Scale Sets
Traffic Control	Azure Load Balancer
Observability	Azure Monitor, Application Insights
CI/CD	GitHub Actions
Code & Dev Tools	VS Code, Git, Azure Portal
📽️ Demo Video / Project Walkthrough

View Project Demo:
https://drive.google.com/file/d/152bSx4abNyBYpmtI9rTkDY55HfXjsytx/view?usp=sharing

📦 Repository Link

(Replace below link later with your GitHub Repo URL)
https://github.com/your-username/your-repository-name
