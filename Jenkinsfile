pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/rishavjais456/simple-addition-pipeline.git', branch: 'main'
            }
        }

        stage('Compile') {
            steps {
                sh 'javac Addition.java'
            }
        }

        stage('Run') {
            steps {
                sh 'java Addition'
            }
        }
    }
}
