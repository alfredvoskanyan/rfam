pipeline {
    agent any
 
    stages {
        stage('rfam select') {
            steps {
                sh "chmod +x -R ${env.WORKSPACE}"
                sh './mysql.sh'
            }
        }
        stage('Mysql version') {
            steps {
                sh 'mysql --version'
            }
        }
    }
}
