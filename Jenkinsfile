pipeline {
    agent any
    tools {
        maven 'Maven 3.9.9' // This should match what you named in the Jenkins UI
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}
