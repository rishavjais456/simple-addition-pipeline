pipeline {
    agent {
        docker { image 'openjdk:17' }  // Runs build inside Java 17 container
    }
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/rishavjais456/simple-addition-pipeline.git'
            }
        }
        stage('Compile Java') {
            steps {
                sh 'javac AddTwoNumbers.java'
            }
        }
        stage('Run Java Program') {
            steps {
                sh 'java AddTwoNumbers'
            }
        }
    }
}
