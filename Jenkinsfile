pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "/opt/apache-maven-3.8.1/bin/mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "/opt/apache-maven-3.8.1/bin/mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "/opt/apache-maven-3.8.1/bin/mvn package"
            }
        }
    }
}
