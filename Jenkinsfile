pipeline {
    agent any
    tools {
        maven 'maven' // This should match what you named in the Jenkins UI
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
