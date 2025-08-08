








pipeline {
    agent any
    tools {
        maven 'Maven3'  // Name from Global Tool Configuration
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
    }
}

