pipeline {
  agent any
  stages {
    stage('Build') {
      steps { echo 'Task: Compile & package, Tool: npm' }
    }
    stage('Unit & Integration Tests') {
      steps { echo 'Task: Unit & integration testing, Tool: Jest' }
    }
    stage('Code Analysis') {
      steps { echo 'Task: Static code quality checks, Tool: ESLint' }
    }
    stage('Security Scan') {
      steps { echo 'Task: Dependency vulnerability scan, Tool: npm audit' }
    }
    stage('Deploy to Staging') {
      steps { echo 'Task: Deploy to staging server, Tool: Docker' }
    }
    stage('Integration Tests on Staging') {
      steps { echo 'Run integration tests on the staging environment, Tool: Postman' }
    }
    stage('Deploy to Production') {
      steps { echo 'Task: Release deployment, Tool: AWS CLI' }
    }
  }
}
