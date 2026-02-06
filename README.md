# ci-cd-pipeline-jenkins-github-actions
End-to-end CI/CD pipeline implementation using Jenkins and GitHub Actions to automate build, test, and deployment of a containerized application.
Complete Folder & File Structure
# CI/CD Pipeline using Jenkins and GitHub Actions

This project demonstrates a complete CI/CD pipeline implementation using both
Jenkins and GitHub Actions to automate the build, test, and deployment process
of an application.

## Project Goals
- Automate code build and testing
- Implement CI/CD using Jenkins
- Implement CI/CD using GitHub Actions
- Build Docker image automatically
- Deploy application using pipeline

## Tech Stack
- CI/CD: Jenkins, GitHub Actions
- Application: Node.js / Python
- Containerization: Docker
- Version Control: GitHub

## Architecture
Developer → GitHub → CI/CD Pipeline → Docker Image → Deployment

## Project Structure
app/        - Application source code docker/     - Dockerfile jenkins/    - Jenkins pipeline .github/    - GitHub Actions workflow scripts/    - Deployment scripts

## Jenkins Pipeline Flow
1. Code checkout
2. Build application
3. Run tests
4. Build Docker image
5. Deploy application

## GitHub Actions Workflow Flow
1. Code pushed to repository
2. GitHub Actions workflow triggered
3. Build and test application
4. Docker image build
5. Deployment step

## How to Run
- Jenkins: Create a pipeline job and use Jenkinsfile
- GitHub Actions: Push code to main branch

## Benefits
- Faster releases
- Reduced manual errors
- Automated deployments

## Future Enhancements
- Kubernetes deployment
- Slack notifications
- Security scanning

## Author
Anjali Singh
