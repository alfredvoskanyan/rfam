pipeline {
    agent any
 
    stages {
        stage('Hello') {
            steps {
                echo 'Hello'
                sh "chmod +x -R ${env.WORKSPACE}"
                sh './mysql.sh'
            }
        }
    }
}
