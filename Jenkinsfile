pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Clone your GitHub repo with the Java file
                git 'https://github.com/yourusername/your-java-repo.git'
            }
        }
        stage('Compile Java') {
            steps {
                // Compile the Java code
                sh 'javac AddTwoNumbers.java'
            }
        }
        stage('Run Java Program') {
            steps {
                // Run the compiled Java program and display output
                sh 'java AddTwoNumbers'
            }
        }
    }
}
