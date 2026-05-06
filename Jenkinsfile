pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Task: Compile and package the code. Tool: Maven." 
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo "Task: Run unit and integration tests. Tool: JUnit and Selenium." 
            }
        }
        stage('Code Analysis') {
            steps {
                echo "Task: Analyse code to meet industry standards. Tool: SonarQube." 
            }
        }
        stage('Security Scan') {
            steps {
                echo "Task: Identify vulnerabilities in the code. Tool: OWASP ZAP." 
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo "Task: Deploy to staging server. Tool: AWS EC2 / Docker." 
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo "Task: Run tests in a production-like environment. Tool: Postman/Selenium." 
            }
        }
        stage('Deploy to Production') {
            steps {
                echo "Task: Deploy application to production server. Tool: AWS EC2 / Kubernetes." 
            }
        }
    }
}
// test1
