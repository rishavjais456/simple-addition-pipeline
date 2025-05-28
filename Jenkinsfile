pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                echo 'Cloning repository...'
                // Jenkins does this automatically
            }
        }

        stage('Run Addition Script') {
            steps {
                echo 'Running Python script...'
                sh 'python3 add.py'  // use 'python' if Windows or Python2
            }
        }
    }
}
