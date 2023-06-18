pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'mvn -B -DskipTests package'
            }
        }
        stage('just like that') {
            steps {
                echo 'Helloo'
            }
        }
    }
}
