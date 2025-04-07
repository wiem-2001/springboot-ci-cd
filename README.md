## 📄 Project Description:
This repository contains a Spring Boot project integrated with a Jenkins CI/CD pipeline and monitoring tools. The project demonstrates:

- **Continuous Integration (CI)**: Automated build, test, and code quality checks using **JUnit** and **Mockito** for unit testing, with **Maven** for project build and dependency management.
- **Continuous Deployment (CD)**: Automated Docker image build and deployment to DockerHub.
- **Monitoring**: Integration with **Prometheus** for application metrics and **Grafana** for visualization. **Alertmanager** is used for handling alerts.
- **Code Quality**: Integration with **SonarQube** for static code analysis and ensuring maintainable code.

This setup provides a scalable solution for automating deployment pipelines, ensuring high-quality software, and monitoring application performance.

## 💡 Key Features:
- Jenkins pipeline automating the development lifecycle, including build, test, and deployment.
- Maven for managing dependencies and building the project.
- Docker containerization for consistent deployment environments.
- Nexus as a repository manager for storing and managing project dependencies.
- Prometheus for real-time application metrics and Grafana for visualization.
- Alertmanager integrated to handle and alert on performance-related issues.
- SonarQube for static code analysis, ensuring code quality and maintainability while identifying issues early.

