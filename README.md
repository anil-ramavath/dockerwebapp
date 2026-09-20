🚀 Built an end-to-end CI/CD pipeline for a containerized application

Instead of learning Jenkins, Docker, SonarQube, Nexus and Trivy as isolated tools, I put them together into one working delivery pipeline.

Pipeline:

GitHub
↓
Jenkins
↓
SonarQube
↓
Maven Build
↓
Nexus Artifact Repository
↓
Docker Build
↓
Trivy Image Scan
↓
Docker Hub
↓
Docker Swarm Deployment

What I implemented:

🔹 Automated source checkout from GitHub
🔹 Maven build and packaging
🔹 SonarQube code-quality analysis
🔹 WAR artifact publishing to Nexus
🔹 Docker image build for application and database
🔹 Trivy vulnerability scanning
🔹 Docker Hub image publishing
🔹 Docker Swarm stack deployment
🔹 Private application infrastructure with controlled external access

The goal was not just to make the pipeline run, but to understand how these pieces connect in an actual delivery workflow.

One successful pipeline run now takes the code from commit → quality check → artifact → container → security scan → registry → deployment.

Still improving the project with stronger environment separation, approvals, observability and infrastructure automation.

#DevOps #Azure #Jenkins #Docker #DockerSwarm #Terraform #SonarQube #Trivy #Nexus #CI #CD #CloudEngineering
