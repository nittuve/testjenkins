pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'mvn -B -DskipTests clean package'
            }
        }
        stage('just like that') {
            steps {
                echo 'Helloo'
            }
        }
    }
}
