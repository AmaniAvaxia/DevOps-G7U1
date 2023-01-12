
pipeline {
    agent any
    stages {
        stage('Clone source code from Git') {
            steps {
                echo "Cloning Project from GitHub; Branch : fouad"
                git branch: 'master',
                url: 'https://github.com/AmaniAvaxia/DevOps-G7U1.git'
            }
        }
        stage('MVN CLEAN') {
            steps {
                sh 'mvn -version'
                sh 'mvn clean'
            }
        }
              
             
    }     
}
