pipeline {
agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/adiyosef/MySoftware.git'
            }
        }
        stage('build') {
            steps {
                sh 'python click.py'
                sh 'python welcome.py'
            }
       
        }
    }
}
