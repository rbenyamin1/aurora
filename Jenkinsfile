 pipeline {
  agent any

    stages {
        stage('Git') {
            steps {
                git branch: 'main', url: 'https://github.com/rbenyamin1/aurora.git'
            }
        }
        stage('Test') {
            steps {
                    // Run the Python script
                sh 'python main.py'
            }
        }
    }   
}