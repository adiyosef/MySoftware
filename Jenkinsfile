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
                sh 'click.py'
                sh 'welcome.py'
            }
       
        }
    }
}
