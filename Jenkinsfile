pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build: Build, compile and package the code using Maven.'
                echo 'Tool: Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Unit and Integration Tests: Run unit tests and integration tests to verify the application and its components.'
                echo 'Tool: JUnit'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Code Analysis: Analyse the source code and check that it meets industry standards.'
                echo 'Tool: SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Security Scan: Scan the code and dependencies to identify security vulnerabilities.'
                echo 'Tool: OWASP Dependency-Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy to Staging: Deploy the application to a staging server for validation.'
                echo 'Tool: AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Integration Tests on Staging: Run integration tests in the staging environment.'
                echo 'Tool: Selenium'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy to Production: Deploy the validated application to the production server.'
                echo 'Tool: AWS EC2'
            }
        }
    }
}
