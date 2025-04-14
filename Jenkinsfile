pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('git ckeckout') {
            steps {
                git 'https://github.com/devopswithdayanand/gmail.git'
            }
        }
        
         stage('build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
