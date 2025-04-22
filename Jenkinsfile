pipeline {
    agent {
        docker {
            image 'maven:3.8.8-openjdk-16'
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
