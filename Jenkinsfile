pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building the application using Maven...'
                // Tool: Maven
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running JUnit for unit tests and TestNG for integration tests...'
                // Tools: JUnit, TestNG
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Running code analysis using SonarQube...'
                // Tool: SonarQube
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Running OWASP Dependency-Check to find vulnerabilities...'
                // Tool: OWASP Dependency-Check
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying application to Staging EC2 instance...'
                // Tool: Jenkins SSH Plugin or Ansible
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running Selenium or Postman tests on Staging...'
                // Tool: Selenium or Postman CLI
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying application to Production EC2 instance...'
                // Tool: Jenkins SSH Plugin or Ansible
            }
        }
    }
}
