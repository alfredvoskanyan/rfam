pipeline {
    agent any
 
    stages {
        stage('rfam select') {
            steps {
                sh "chmod +x -R ${env.WORKSPACE}"
                sh './mysql.sh'
            }
        }
    }
    stages {
        stage('Mysql Version') {
            steps {
                sh 'mysql --version'
            }
        }
    }
}
