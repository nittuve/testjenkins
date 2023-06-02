pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'maven -B -DskipTests clean package'
            }
        }
    }
}
